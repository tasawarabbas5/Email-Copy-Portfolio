# Email sequencing, deliverability, segmentation, metrics and benchmarks (as they affect email copywriting)

Research caveat: direct page fetches (WebFetch, curl) were blocked in this session (DNS failure / proxy 403 for klaviyo.com, mailchimp.com, omnisend.com, support.google.com, senders.yahooinc.com). All findings below come from WebSearch result summaries, so primary-source wording (Google, Yahoo, FTC, Litmus, Klaviyo, HubSpot) was NOT verified directly. Vendor blogs are marked as such. Today's date for context: Oct 2026.

## What are current benchmark open/click/conversion rates by email type and by industry, and how do the platforms differ?

### Takeaway
Platform benchmarks are not comparable: open rates range from about 21% to 43% overall depending on vendor, method and MPP handling, and flows (welcome, abandoned cart) outperform campaigns several-fold on clicks and revenue per recipient. Quote benchmarks only with source, year, platform and campaign-vs-flow label. Several vendors (HubSpot, Campaign Monitor, Brevo, Litmus) yielded no verifiable current per-industry tables.

### Cited Findings
- Klaviyo 2025 Benchmark Report (official PDF, garbled extraction, partial): average campaign open rate about 37.93%, click rate about 1.29%, placed order rate about 0.08%; Klaviyo excludes bot clicks from click rate. Figures only partly confirmed — [Klaviyo 2025 Benchmark Report PDF](https://klaviyocms.wpengine.com/wp-content/uploads/2025/02/2025-Benchmark-Report_AMER.pdf)
- Klaviyo 2025 report is based on 167,000+ customers (per search summary; per-industry numbers not retrieved) — [Klaviyo benchmarks (search result)](https://klaviyo.com/blog/ecommerce-benchmarks-2021)
- "Klaviyo 2026" figures via a third-party agency blog: campaigns 31% open, 1.69% click, 0.16% placed order rate, $0.11 revenue per recipient (RPR); flows 42%+ open, 5.58% click, 2.11% placed order rate, $1.94 RPR. Conflicts with the 2025 PDF figures above (37.93% / 1.29%); treat as secondary — [Needle](https://www.askneedle.com/blog/klaviyo-email-benchmarks-for-ecommerce-open-rates-ctr-revenue-per-send); similar 31% open / $0.10 campaign RPR in [Threadpoint](https://www.threadpoint.agency/blogs/learn-e-mail-marketing/whats-a-good-email-open-rate-for-ecommerce-2026-benchmarks)
- Flow-level (agency blogs, not Klaviyo directly): welcome flow RPR about $2.65 with 45-60%+ opens; abandoned cart RPR about $3.07. Landing Partners gives welcome email 1 at 48-62% opens and 4-7% clicks, abandoned cart 38-52% opens and 5-9% clicks — [Needle](https://www.askneedle.com/blog/klaviyo-email-benchmarks-for-ecommerce-open-rates-ctr-revenue-per-send); [Threadpoint](https://www.threadpoint.agency/blogs/learn-e-mail-marketing/whats-a-good-email-open-rate-for-ecommerce-2026-benchmarks); [Landing Partners](https://www.landing.partners/blog/klaviyo-email-benchmarks-fashion-brands-2025)
- Abandoned cart conversion average 3.33%, high performers 7.69%; abandoned cart open rate 50.5% attributed to Klaviyo (via a 2026 roundup, not verified at source) — [Ringly](https://www.ringly.io/blog/ecommerce-email-marketing-statistics-2026)
- Prospeo (vendor blog) RPR: abandoned cart $3.65, welcome $2.65, post-purchase $0.41 — [Prospeo](https://prospeo.io/s/email-automation-examples)
- Omnisend 2025 dataset (20B+ campaign emails, 27,000+ brands): welcome 35.53% open, 3.94% CTR, $6.16 per email; abandoned cart 37.12% open, 4.13% CTR, $3.59 per email; back-in-stock highest revenue per email $9.14; shipping confirmation highest open rate 62.67%. Cross-industry campaign averages: CTR 0.74%, CTOR 2.44% — [Omnisend benchmarks](https://www.omnisend.com/blog/email-marketing-benchmarks/?bbpage=1) (CTR/CTOR figures reported via search summary of same dataset family)
- Older/undated Omnisend infographic gives higher numbers (welcome 42.2% open, 10.5% click; cart 40.1% open, 9% click) — treat as outdated; contradicts the 2025 table — [Omnisend infographic](https://www.omnisend.com/blog/ecommerce-email-marketing-statistics-infographic/)
- Mailchimp (last updated Dec 2023; campaigns to 1,000+ subscribers; flags MPP distortion): all users 35.63% open / 2.62% click / 0.22% unsub; Business+Finance 31.35/2.78/0.15; Non-profits 40.04/3.27/0.18; Education+Training 35.64/3.02/0.18; Ecommerce 29.81/1.74/0.19 — [Mailchimp benchmarks](https://mailchimp.com/resources/email-marketing-benchmarks/)
- MailerLite 2025 (3.6M campaigns, 181,000 accounts, Dec 2024-Nov 2025, 46 industries): open 43.46% (2024: 42.35%), CTOR 6.81%, click 2.09%, unsubscribe 0.22% (2024: 0.08%). MailerLite attributes the unsubscribe rise to easier Gmail one-click unsubscribe. Industry open rates (secondary newsletter, unverified): Religion about 59.7%, Non-profit about 53.2%, Health & Fitness about 48.9%, Retail about 37.5%, Travel lowest about 22.6% — [MailerLite benchmarks](https://www.mailerlite.com/blog/email-marketing-benchmarks); [secondary](https://inboxempire.beehiiv.com/p/newsletter-benchmarks)
- Brevo 2025: 44B+ emails analyzed, says data accounts for Apple MPP; Brevo 2026 automation/transactional average 30.63% open, 7.39% CTR. A third-party table lists Brevo 31.22% open / 3.64% CTR (unverified). Another report cites Brevo standard open 20.73% vs 33.87% when MPP opens included — [Brevo](https://www.brevo.com/blog/email-marketing-benchmarks/); [Thunderbit](https://www.thunderbit.com/de/blog/newsletter-statistics-email-open-rates); [Benchmark Email](https://www.benchmarkemail.com/blog/mail-privacy-protection)
- Campaign Monitor (undated/older, via MediaPost and Rasa.io): CTR 2.69%, CTOR 14.10%; industry-table average open 21.5%, click 2.3%; Education 4.4% click, Restaurant/Food/Beverage 2.0% click — [MediaPost](https://www.mediapost.com/research/article/337376); [Rasa.io](https://help.rasa.io/what-are-average-open-and-click-rates-by-industry)
- HubSpot-attributed (via roundups, unverified): 65% of opens on mobile; B2B average open 39.5% and CTR 3.18% in one roundup vs 42.35% open / 3.25% CTR "all industries" in another — [InboxAlly](https://inboxally.com/blog/the-most-important-email-marketing-statistics); [InsideA](https://insidea.com/blog/hubspot/b2b-email-marketing-benchmarks)

### Inferences
- Source differences are driven by (a) MPP handling, (b) campaign vs flow mix, (c) store/B2B composition of the platform's customers, (d) mean vs median. E.g. MailerLite 43% open vs Klaviyo 2026 campaign 31% vs Mailchimp 36%.
- Reasonable portfolio framing: compare your result to the same platform's benchmark for the same email type and say so.
- Directional pattern across sources: triggered/flow emails (welcome, cart, back-in-stock) beat batch campaigns on open, click and revenue per recipient by large multiples.

### Gaps
- No verified per-industry tables from Klaviyo, Brevo, Campaign Monitor, HubSpot, Litmus (charts or gated; fetch blocked).
- No verified newsletter-specific benchmark (beyond MailerLite overall) and no verified promotional-campaign split by industry.
- Litmus State of Email and Validity reports were not retrieved.

## Which metrics still matter after Apple Mail Privacy Protection, and how should a copywriter measure success?

### Takeaway
Open rates are inflated and unreliable for Apple Mail users (and partly Gmail image caching); use clicks, click-to-open on cautious terms, conversions, revenue per recipient, replies, plus unsubscribe and complaint rates. Use subject-line tests on click or revenue outcomes, not raw opens.

### Cited Findings
- MPP pre-loads tracking pixels, inflating opens; a Benchmark Email post (June 2025) citing Litmus's May 2025 report says MPP now drives roughly 50-60% of opens — [Benchmark Email](https://www.benchmarkemail.com/blog/mail-privacy-protection)
- Litmus help documentation: its tests found MPP opens inflated and should be excluded from campaign success counts — [Litmus](https://help.litmus.com/article/405-apple-mail-opens-reported-in-email-analytics)
- A Webtonic article attributes 62.26% of tracked opens to the Apple client family (Gmail 27.03%, Outlook 5.83%) in a Litmus report it dates July 2026; not verified at source — [Webtonic](https://www.webtonic.io/blog/open-rate-statistics)
- Clicks proposed as replacement since they require a human action; Gmail also caches images so the issue is not Apple-only — [Pinpointe](https://blog.pinpointe.com/mail-privacy-protection-email-open-rate-tracking); [Suped](https://www.suped.com/knowledge/email-deliverability/technical/how-accurate-is-email-client-market-share-data-when-apple-mail-intentionally-opens-messages)
- Klaviyo excludes bot clicks from click rate (security scanners also generate false clicks) — [Klaviyo 2025 PDF](https://klaviyocms.wpengine.com/wp-content/uploads/2025/02/2025-Benchmark-Report_AMER.pdf)
- Mailchimp itself warns open-rate comparisons are affected by MPP — [Mailchimp](https://mailchimp.com/resources/email-marketing-benchmarks/)
- Brevo reported 20.73% standard open vs 33.87% with MPP opens — [Benchmark Email](https://www.benchmarkemail.com/blog/mail-privacy-protection) (secondary)

### Inferences
- Metric hierarchy for copy: revenue per recipient / placed-order rate > click rate (unique, bot-filtered) > CTOR (interpret carefully since the denominator is inflated) > unsubscribe and complaint rate (guardrails) > open rate (only for non-Apple segments or directional).
- A subject line can only be judged via downstream click or revenue; preview text/subject changes affecting opens may be invisible for 50%+ of the list.

### Gaps
- Exact current MPP share of opens varies by source (50-62%); original Litmus report not retrieved.
- No verified source on how Gmail image proxying affects opens.

## How should sequences be planned (cadence, spacing, length, branching, exit conditions), and what do send frequency and timing data show?

### Takeaway
Evidence is largely vendor guidance: 3-email cart flows (about 1-4h, 24h, 48-72h) and 3-7 email welcome series over 5-14 days are the common recommendations; send-time and frequency findings are inconsistent and should be tested on one's own list. Branching/exit rules had no rigorous sourced data.

### Cited Findings
- Abandoned cart: three emails commonly recommended; timing 1-2h or 2-4h, then 24h (often with incentive), then 48-72h. A Campaign Monitor-cited comparison: three cart emails produced $24.9M vs $3.8M for one (methodology unverified) — [Campaign Monitor guide](https://www.campaignmonitor.com/resources/guides/email-marketing-for-e-commerce/amp/); [Woobox](https://cdn.woobox.com/articles/ecommerce-email-sequences)
- Welcome series: typically 3-7 emails over 5-14 days, first immediately, then 24-72h gaps; one case study claims a 17% increase in unique open rate moving from a seven-day to a three-day schedule; advice to hold discount until email 4-5 — [TrueFuture Media](https://www.truefuturemedia.com/articles/email-automation-sequences-that-convert); [Attn Agency](https://www.attnagency.com/blog/email-welcome-series-optimization)
- Klaviyo says its flow timing recommendations reflect the average brand and advises A/B testing flow time delays — [Klaviyo Help](https://help.klaviyo.com/hc/en-us/articles/10948996125083-How-to-optimize-your-flow-sending-frequency)
- Klaviyo offers no out-of-the-box frequency holdout test (community thread) — [Klaviyo Community](https://community.klaviyo.com/marketing-30/holdout-test-for-email-sending-frequency-testing-9186)
- Send day/time: Tuesday most frequently cited (Thursday close); weekends weakest; time windows disputed (8-11am and 4-6pm; Moosend 10B-email analysis found click peaks 8-9pm); B2B work hours, B2C evenings/weekends possible; many sources are vendor roundups or aggregate old studies — [BloggingWizard](https://bloggingwizard.com/best-time-send-emails); [Customer.io](https://customer.io/blog/best-time-to-send-email/); [OptinMonster](https://optinmonster.com/the-best-time-to-send-emails-heres-what-studies-show/)
- Unsubscribe rate doubled in MailerLite 2025 data (0.08% to 0.22%), plausibly easier unsubscribe — [MailerLite](https://www.mailerlite.com/blog/email-marketing-benchmarks)

### Inferences
- Design sequences with exit conditions at the conversion event (purchase/booking/reply), suppress cart flow if purchase occurs, and branch on click/no-click engagement; this is standard practice but I found no sourced quantitative evidence for branching lift.
- Spacing should front-load (fast first emails) then lengthen; test delays rather than trusting universals.
- For a portfolio, present sequence logic (trigger, delay, exit, branch) as a diagram, label as design rationale rather than proven.

### Gaps
- No rigorous data on optimal send frequency vs unsubscribe/complaint rates (searches returned none).
- No verified evidence on optimal number of welcome emails or on branching lift.
- Send-time claims are not independently validated.

## Segmentation, personalization and list hygiene

### Takeaway
Klaviyo's segmentation data is old (2017) but directionally shows large gains from segmentation; personalization claims in roundups are mostly unverified. List hygiene guidance (sunset at 90-180 days) is mainly from one verification vendor.

### Cited Findings
- Klaviyo segmentation benchmark (2.5B emails, Oct-Dec 2017): highly segmented campaigns generate 3X revenue per recipient ($0.19 vs $0.06) and about 2x open and click rates — [Klaviyo report](https://www.klaviyo.com/marketing-resources/segmentation-benchmark-report); [Klaviyo blog](https://www.klaviyo.com/blog/new-report-email-segmentation-benchmark); [Klaviyo Academy](https://academy.klaviyo.com/en-us/courses/getting-started-with-segments/lessons/build-a-segmentation-strategy)
- Roundup claim (unverified): personalized subject lines yield 26% higher opens — [InsideA](https://insidea.com/blog/hubspot/b2b-email-marketing-benchmarks)
- Sunset policies: windows of 90, 180 or 12 months; engagement odds drop sharply after 90-180 days; daily senders need shorter windows; source is one list-validation vendor (commercial interest) — [EmailListValidation](https://emaillistvalidation.com/blog/sunset-policy-timeline-90-vs-180-vs-12-months/)
- MailerLite notes removing unengaged subscribers lifts open/click percentages (so rates partly reflect list pruning, not copy) — [MailerLite](https://www.mailerlite.com/blog/email-marketing-benchmarks)

### Inferences
- When presenting results, note audience segment and list state; copy lift is confounded by segmentation and pruning.

### Gaps
- No current (2024-2026) segmentation benchmark found; no verified bounce-rate threshold or annual list-decay figure.

## Deliverability fundamentals relevant to copy (authentication, Gmail/Yahoo/Microsoft rules, spam triggers)

### Takeaway
Since Feb 2024 bulk senders (about 5,000+/day to Gmail) need SPF, DKIM, DMARC, one-click unsubscribe (RFC 8058) honored within 2 days, and spam complaints under 0.3% (aim under 0.1%); Gmail moved to active rejection of non-compliant mail in Nov 2025 and Microsoft Outlook planned rejection from May 2025. For copy, engagement and complaints matter far more than "spam words"; avoid deceptive/clickbait subjects that raise complaints.

### Cited Findings
- Requirements effective Feb 1, 2024: SPF, DKIM, DMARC (p=none satisfies Gmail/Yahoo, not BIMI); RFC 8058 one-click List-Unsubscribe; unsubscribe within 2 days; complaint rate target below 0.1%, never above 0.3% (one source notes 0.3% not spelled out in Google's original blog post) — [Resend](https://www.resend.com/blog/gmail-and-yahoo-bulk-sending-requirements-for-2024); [Sender.net](https://www.sender.net/blog/new-google-rules-for-bulk-email-senders/); [Bird](https://bird.com/explained/deliverability/what-are-the-gmail-and-yahoo-bulk-sender-requirements)
- Yahoo: complaint feedback loop and DKIM keys of at least 1024 bits — [Emailable](https://emailable.com/blog/new-requirements-for-gmail-and-yahoo-bulk-senders/)
- Google Nov 2025: shifted from warnings/spam-foldering to delays and rejections for non-compliant bulk mail; smaller senders can still be deferred — [PowerDMARC](https://powerdmarc.com/gmail-enforcement-email-rejection/); [Valimail](https://www.valimail.com/?p=11424); [Red Sift](https://redsift.com/blog/gmails-enforcement-ramps-up-what-bulk-senders-need-to-know)
- Microsoft: bulk mail from non-compliant domains rejected from May 5, 2025 (per IRONSCALES) — [IRONSCALES](https://ironscales.com/blog/googles-november-2025-dmarc-crackdown-what-security-and-marketing-leaders-need-to-know)
- Spam trigger word lists are largely a myth; filters weigh sender reputation, engagement, authentication; one vendor test showed trigger-free email still got 37.3% inbox placement from a weak-reputation domain; Mailjet says some subject-line words can raise complaints/lower engagement — [Suped](https://www.suped.com/knowledge/email-deliverability/technical/are-spam-trigger-word-lists-accurate-and-should-i-be-concerned-about-them); [InBXR](https://inbxr.beehiiv.com/p/the-spam-trigger-myth-that-s-crippling-your-sales); [Mailjet](https://www.mailjet.com/?p=7591)

### Inferences
- Copy practices that plausibly hurt deliverability via complaints/low engagement: misleading subjects ("Re:", fake urgency), mismatched from-name, hard-to-find unsubscribe (drives spam-button clicks), over-frequency. These are inferences; no source retrieved quantified them.

### Gaps
- Google/Yahoo primary documents not read directly; image-to-text ratio, link shorteners, ALL CAPS/punctuation effects not found in sources.
- Exact bulk-sender thresholds for Yahoo/Microsoft not verified.

## Legal requirements a copywriter must respect (CAN-SPAM, GDPR, CASL)

### Takeaway
CAN-SPAM is opt-out (no deceptive headers/subjects, physical address, working unsubscribe honored within 10 business days); GDPR and CASL are opt-in regimes needing provable consent. Penalty figures come from vendor blogs; verify with FTC/EU/CRTC primary sources.

### Cited Findings
- CAN-SPAM: honor opt-out within 10 business days; opt-out mechanism works at least 30 days; no B2B exemption; transactional/relationship messages exempt; opted-out addresses can't be sold. Max penalty $53,088 per email (Jan 2025 inflation adjustment; older figures $16,000/$51,744 appear in stale sources). Verkada paid about $2.95M (Aug 2024) — [Prospeo CAN-SPAM](https://prospeo.io/s/can-spam-act-unsubscribe); [Prospeo penalties](https://prospeo.io/s/can-spam-penalties); [HubSpot](https://blog.hubspot.com/marketing/what-is-can-spam-ht)
- GDPR: greater of EUR 20M or 4% global turnover; CASL: up to CAD 10M per violation for organizations (individuals CAD 1M); both opt-in; CASL distinguishes express vs implied consent; keep consent records — [Adaptive Security](https://www.adaptivesecurity.com/blog/email-compliance-penalties); [Lerners](https://www.lerners.ca/?p=3333); [AllClients](https://allclients.com/blog-resources/staying-compliant-can-spam-casl-gdpr)
- Conflict: one source claims recipients must stay opted out 60 days (unverified); "2 days" unsubscribe is a mailbox-provider rule, not statute — [AllClients](https://help.allclients.com/article/338-staying-compliant-with-can-spam-casl-gdpr)

### Inferences
- Copy-level duties: accurate From/Subject (no deception), clear identification as advertising where applicable, visible unsubscribe, sender postal address, no pre-checked consent language in signup copy.

### Gaps
- FTC, GDPR and CRTC primary texts not retrieved; ad-identification wording, CASL implied-consent timeframes not verified.

## A/B testing methodology and sample sizes

### Takeaway
Required sample depends on baseline rate and minimum detectable lift; low baselines (click, conversion) need thousands to tens of thousands per variant. Use a calculator, test one variable, don't peek, and judge on clicks/revenue.

### Cited Findings
- Examples: 30% baseline open, 10% relative lift needs about 3,692 contacts; 3.43% baseline reply rate, 20% lift needs about 1,560 per variant; 2% CTR baseline with 20% relative lift needs about 20,000 per variant (40,000 total) at 95% confidence; rule-of-thumb 1,000 minimum, 5,000-10,000 for small differences — [Webit](https://www.webit.de/en/marketing-automation/samples-ab/); [Unify](https://www.unifygtm.com/explore/cold-email-ab-testing-statistical-rigor); [Suped](https://www.suped.com/learn/email-deliverability/how-long-should-email-ab-tests-run-and-what-statistical-significance-is-needed-for-subject-line-)
- Confidence 90-95% acceptable; lists under 10,000 use 50/50 split, larger lists 10-30% test group; peeking early is the most common way teams invalidate tests — [Suped](https://www.suped.com/learn/email-deliverability/how-long-should-email-ab-tests-run-and-what-statistical-significance-is-needed-for-subject-line-); [Prospeo](https://prospeo.io/s/ab-test-email-variations)

### Inferences
- Structure: hypothesis (change, reason, metric), single variable, pre-set sample size and duration, primary metric = click or revenue, guardrails = unsubscribe/complaint; log results including losers. Small lists can only detect big effects, so say "directional" in a portfolio.

### Gaps
- All figures are vendor/blog estimates, not peer-reviewed; Evan Miller calculator referenced by search summary but not fetched.

## AI-generated email copy: what works, pitfalls, disclosure

### Takeaway
Limited evidence: one academic-style field test suggests AI emails perform comparably to human emails at far lower cost, and vendor tests suggest AI is better at subject lines/CTAs while humans win on body copy and brand voice. No reliable data on disclosure.

### Cited Findings
- Chicago Booth Review (wine retailer, one recurring campaign): AI and human emails performed similarly; hybrid AI-draft/human-edit estimated to save 83% (trained model) and 75% (Claude) of cost; recipients did not notice a difference — [Chicago Booth](https://www.chicagobooth.edu/review/is-email-marketing-about-be-automated)
- Mailercloud 50,000-email test: humans stronger on body copy, AI on subject lines and CTAs; AI output was unedited (vendor study) — [Mailercloud](https://www.mailercloud.com/e-book/ai-vs-human-email-test-research-report)
- Stripo (Q3 2026) notes effectiveness percentages are largely self-reported, directional — [Stripo](https://research.stripo.email/ai-in-email-marketing-2026)
- Generative AI tends toward smooth, generic style; common workflow is AI first draft plus human tone/brand edit — [Marketrithm](https://marketrithm.com/insights/ai-email-copy-vs-human-writers-what-works)
- Retail marketers: 58.85% use AI for email optimization (retail report via roundup, unverified) — [InsideA](https://insidea.com/blog/hubspot/b2b-email-marketing-benchmarks)

### Inferences
- Portfolio should state where AI was used and what human edits changed; accuracy/claims checking is essential.

### Gaps
- No sourced guidance on disclosing AI use to recipients (FTC/other); no verified 2025-26 controlled studies beyond those above.

## How should a portfolio present email results credibly?

### Takeaway
No source directly addressed portfolio presentation; the following is derived from the measurement findings above.

### Cited Findings
- Benchmarks differ by platform, MPP handling and email type, so comparisons need like-for-like context — [Mailchimp](https://mailchimp.com/resources/email-marketing-benchmarks/); [Klaviyo 2025 PDF](https://klaviyocms.wpengine.com/wp-content/uploads/2025/02/2025-Benchmark-Report_AMER.pdf)
- Rates can rise from list pruning alone — [MailerLite](https://www.mailerlite.com/blog/email-marketing-benchmarks)

### Inferences
- Present: send type (flow vs campaign), list size/segment, date range, platform, metric definitions (unique vs total; bot-filtered), baseline or control, test sample sizes and significance, and benchmark source/year. Lead with clicks, conversions, revenue per recipient; avoid open-rate-only claims; disclose confidentiality redactions, spec/sample work, and AI assistance. Report losers/learnings.

### Gaps
- No authoritative source on portfolio best practice found.
