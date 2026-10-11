# Craft of Each Marketing Email Component, and Email Length/Depth

Method caveat: WebFetch and direct HTTP were unavailable in this environment (DNS failures; a curl workaround was blocked), so every finding below comes from WebSearch result summaries, not full-page reads. Most stats are vendor-blog figures with undisclosed methodology. Primary reports (Litmus State of Email, Mailchimp, Klaviyo, Omnisend, Campaign Monitor, Phrasee, Validity, Barilliance, Baymard, Email on Acid) were NOT reached; I found no figures from them. Treat all numbers as directional.

## Subject lines: length, personalization, emojis, numbers, questions, lowercase, curiosity vs clarity

### Takeaway
No credible source settles one best length; 2024-25 vendor data leans short (about 2-6 words, or 61-70 characters, depending on source). Emoji and personalization evidence is mixed-to-negative on average. Curiosity wins in some tests and loses in others, so audience-specific A/B testing is the only dependable guide.

### Cited Findings
- Subject length, conflicting: GetResponse 2024 benchmarks report the best open rate (43.38%) at 61-70 characters, while Belkins (5.5M B2B cold emails) reports 2-4 words best at 46%, and Twilio SendGrid's 2025 Cyber Week data says the average subject was 6 words with top performers at 2-4 words. These are different populations (newsletters/marketing vs B2B cold email vs promo) and different metrics, so they should not be averaged. — [Webtonic roundup](https://www.webtonic.io/blog/email-subject-lines), [Twilio](https://twilio.com/en-us/blog/ideal-email-subject-length) (search summary only; secondary citations of GetResponse and Belkins)
- Older length data (2014, MailerMailer, 62,000 campaigns, ~1.18B emails): shorter subjects had higher opens (4-15 characters 16.8% vs 40-50 characters 10.7%). Alchemy Worx (undated) found 70+ character subjects gave the highest click-to-open rate, a different metric from opens. — [Smartlead summary](https://www.smartlead.ai/blog/how-the-length-of-a-subject-line-can-affect-open-rates-and-engagement), [MediaPost](https://www.mediapost.com/publications/article/86030/alchemy-email-marketing-favors-longer-subject-lin.html)
- Mobile truncation: one source says mobile devices display only about 25-30 characters of subject, so front-load the key words. — [Hatchbuck help article](https://intercom.help/hatchbuck-0fe342c41fb9/en/articles/2383225-email-subject-lines)
- Emojis, mostly negative or neutral: GetResponse analysis (about 7B emails, 2021) found emoji subjects had lower average open and click rates than non-emoji; a small 9 Clouds test (12 emails) had no-emoji at 29.01% vs emoji 20.81% open rate (author calls it small); Search Engine Journal compared 17 campaigns month-over-month (not a true A/B) and no-emoji won 52.94% to 47.06%, often marginally. A "56% of brands using emojis saw higher opens" claim (Experian, via a vendor blog) is second-hand and old. — [Lebesgue](https://lebesgue.io/email-marketing/should-you-use-emojis-in-email-subject-lines), [9clouds](https://9clouds.com/blog/data-drop-november-2018-inaugural-post/), [SEJ](https://www.searchenginejournal.com/emojis-in-subject-lines/), [MarketingProfs chart 2022](https://www.marketingprofs.com/charts/2022/47361/email-subject-line-benchmarks-for-common-tactics-and-words)
- Personalization in subject: the same GetResponse analysis found personalized subjects underperformed non-personalized on open rate, CTR and unsubscribe rate on average. This conflicts with the common vendor claim that name personalization lifts opens; I did not find the Experian/Campaign Monitor-style pro-personalization figures in a verifiable form. — [Lebesgue](https://lebesgue.io/email-marketing/should-you-use-emojis-in-email-subject-lines), [MarketingProfs](https://www.marketingprofs.com/charts/2022/47361/email-subject-line-benchmarks-for-common-tactics-and-words)
- Curiosity vs clarity, conflicting: NextAfter nonprofit test (n=81,631), vague "This is great news" beat specific "100,000... and counting" on click rate 2.7% vs 1.6% (4.3% open lift); Ian Brodie test, curiosity subject raised opens 36.7% vs 32.3% and clicks 5.4% to 6.5%; Atticus Li review of ~1,000 A/B tests says curiosity-gap lines averaged ~22% higher opens than descriptive lines, but purely vague lines did ~8% worse than descriptive. A second NextAfter test (clear "new, free course for you" vs vague control) result was not visible. — [NextAfter](https://www.nextafter.com/?p=47660), [NextAfter 2](https://www.nextafter.com/?p=19173), [Ian Brodie](https://www.ianbrodie.com/tag/subject-lines/), [Atticus Li](https://www.atticusli.com/blog/posts/email-subject-line-testing-lessons-1000-ab-tests/)
- Questions: Atticus Li's review says a specific question tied to the recipient's known interest performs best. — [Atticus Li](https://www.atticusli.com/blog/posts/email-subject-line-testing-lessons-1000-ab-tests/)
- Numbers/specificity: Dyspatch cites Dan Pink's golf example ("4 tips to improve your golf swing this afternoon" opened more than "Improve your golf swing"); no large-scale numbers study found. — [Dyspatch](https://dyspatch.io/?p=471)
- Word categories: a ReturnPath study (via Hatchbuck, undated) says urgency, benefit and command words performed best. — [Hatchbuck](https://intercom.help/hatchbuck-0fe342c41fb9/en/articles/2383225-email-subject-lines)
- Open-rate benchmarks are inflated by Apple Mail Privacy Protection; OptinMonster says realistic benchmark is about 20-30% for most industries. Use clicks/conversions, not opens, as the test metric. — [OptinMonster](https://optinmonster.com/101/)

### Inferences
- Because Apple MPP inflates opens and opens are ~62% Apple (see mobile section), subject-line tests judged on open rate alone are unreliable; judge by click/revenue per send.
- The "short wins" and "curiosity wins" claims likely depend on list type (cold B2B, nonprofit, ecommerce promo); present them as hypotheses to test, not rules.

### Gaps
- No lowercase / "ugly" subject style test data found (one source listed zero-capitalization as a tactic with no results).
- No accessible Phrasee, Validity, Barilliance, Klaviyo, Omnisend, Mailchimp or Campaign Monitor subject-line datasets (fetch failures; searches returned vendor blogs). The Omnisend search returned no Omnisend study.
- No verified numbers-in-subject-line large-scale study.

## Subject line formulas and examples (30+ requested)

### Takeaway
I could verify only a handful of examples from sources; the rest below are illustrative formula patterns I wrote, clearly labeled, not sourced real-world sends. A report writer needing 30+ real examples will need Really Good Emails / Milled / swipe-file research, which I could not access.

### Cited Findings
- OptinMonster's six-formula framing (curiosity gap, direct benefit, urgency, personalization, etc.) with examples: curiosity "We found something surprising in your data"; benefit "How to double your email list in 30 days"; urgency "Last day: 40% off ends at midnight"; personalization "[First name], your guide is ready." — [OptinMonster](https://optinmonster.com/101/)
- B2B non-clickbait curiosity example: "Quick question about your Q4 planning"; source warns curiosity must be authentic. — [Enginy](https://www.enginy.ai/blog/email-subject-lines-sales)
- Specificity pair: "4 tips to improve your golf swing this afternoon" vs "Improve your golf swing." — [Dyspatch](https://dyspatch.io/?p=471)
- Tested pairs: "This is great news" (vague) vs "100,000... and counting"; "exciting news for you" vs "new, free course for you." — [NextAfter](https://www.nextafter.com/?p=47660)
- Urgency/benefit words that performed (ReturnPath via Hatchbuck): "expiring," "hurry," "running out"; "fastest," "easiest." — [Hatchbuck](https://intercom.help/hatchbuck-0fe342c41fb9/en/articles/2383225-email-subject-lines)

### Inferences
Illustrative patterns (my own, unsourced, for formula structure only): Curiosity: "The one thing I'd change about your welcome email"; Benefit: "Cut your onboarding time in half"; Number: "7 subject lines we A/B tested (3 lost)"; Question: "Is your cart still thinking it over?"; Urgency: "Ends tonight: free shipping"; Social proof: "Why 12,000 teams switched"; Story: "I almost quit last March"; Negative: "Stop doing this in your emails"; Personal/plain: "quick question"; How-to: "How to write a CTA that gets clicked"; Command: "Steal this template"; Newsjack/timely: "Black Friday starts early."

### Gaps
- Real, attributed examples from brands (e.g., Really Good Emails, Milled) were not collected; the 30+ real-example goal is unmet.

## Sender name / from line

### Takeaway
A real person's name usually beats a brand-only name in reported tests, with "Person from Brand" as the common compromise; the lift magnitudes are second-hand.

### Cited Findings
- BlaBlaCar test: real people's first names produced 20+% higher opens than "BlaBlaCar" (via Braze). Other summaries cite roughly 19% and 27% lifts, which I could not trace to originals. — [Braze](https://www.braze.com/resources/articles/how-smart-testing-boosts-open-rates), [Benchmark Email](https://www.benchmarkemail.com/blog/email-sender-name-person-or-brand/)
- Guidance: use "Person at Brand," commit to one person for consistency, test 3-4 campaigns; brand name is better for transactional email or where the "person" would be fake. — [Benchmark Email](https://www.benchmarkemail.com/blog/email-sender-name-person-or-brand/)

### Inferences
Opens-based lifts are subject to MPP inflation; sender recognition mostly matters for trust/recall, so measure replies and clicks.

### Gaps
No original study for the 19%/27% claims; no data on deliverability effects of sender name beyond a vendor Q&A.

## Preview text (preheader)

### Takeaway
No independent controlled study found; vendor guidance converges on writing it deliberately (not letting the client pull "View in browser") and front-loading the key words.

### Cited Findings
- Recommended lengths conflict: 40-130 characters, 40-100 (MailCharts), 85-100; mobile often shows only about 30-55 characters. — [MailCharts](https://www.mailcharts.com/blog/email-preheader-text), [Brevo](https://www.brevo.com/blog/email-preheader/), [Moosend](https://moosend.com/blog/email-preheader/)
- Front-load the most important points; if too short, clients pull body text into the preview. — [Mailchimp](https://mailchimp.com/resources/email-preheader/), [ActiveCampaign](https://www.activecampaign.com/blog/email-preheader)
- Brevo claims effective preheaders give "up to 7% higher open rates" with no named research. — [Brevo](https://www.brevo.com/blog/email-preheader/)

### Inferences
Pair strategies commonly recommended: extend the subject (don't repeat it), add the offer detail or deadline, or deliver the payoff of a curiosity subject. These are practice conventions, not test-proven here.

### Gaps
No A/B data on preview-text strategies; no Litmus/Email on Acid truncation tables retrieved.

## Opening hook / first lines, body copy, tone, readability

### Takeaway
Readers scan; short, specific, plain-language copy at about a 6th-8th grade level is the consensus guidance, backed by vendor claims and old NN/g research rather than recent controlled tests. Hook-type examples with data were not found.

### Cited Findings
- NN/g newsletter research (2006; five rounds, 270 newsletters, 124 participants): only 19% of newsletters were read thoroughly, 69% skimmed; average scan under a minute (51 seconds per ClickZ). Old, so directional. — [NN/g](https://www.nngroup.com/articles/e-mail-newsletters-usability/), [ClickZ](https://www.clickz.com/51-seconds-to-e-newsletter-success/58236/)
- Mailchimp says about 8th-grade reading level performs better than more complex text; Regie.ai (sales email) cites a study claiming 8th grade or below had 36% higher opens than 12th grade+, and says ~3rd-grade sales emails got best replies; Send2 suggests Flesch-Kincaid roughly 7-9. All vendor claims. — [Mailchimp](https://mailchimp.com/resources/email-readability/), [Regie.ai](https://www.regie.ai/blog/how-to-write-readable-sales-emails-that-get-results), [Send2](https://send2.co/glossary/what-is-readability-score-for-email-content)
- If grade-level score exceeds 8, check for long sentences/paragraphs. — [PropertyCasualty360](https://propertycasualty360.com/2015/05/01/4-tips-to-create-must-read-client-emails)

### Inferences
Practical targets: 1-3 sentence paragraphs, one idea per email, headings or bold only for scannable skeletons. Hook categories (my taxonomy, unsourced): story/anecdote, bold claim, question, specific stat, direct benefit, pattern interrupt, personal note.

### Gaps
No tested hook-type data; no Copyhackers material retrieved; no tone/voice A/B evidence beyond plain-text-style tests below.

## CTAs: button vs link, wording, placement, number

### Takeaway
Single focused CTA is the consistent recommendation; button vs link evidence is genuinely conflicting; first-person button copy often lifts clicks but is not universal.

### Cited Findings
- Campaign Monitor A/B: a button beat a text link by 28% more click-throughs; AWeber reported buttons led early but after 40 tests text links consistently outperformed (novelty effect). Conflict, not averaged. — [Campaign Monitor](https://www.campaignmonitor.com/blog/email-marketing/buttons-email-marketing-campaigns/), [Econsultancy](https://econsultancy.com/three-case-studies-to-help-improve-your-email-marketing-conversion-rates/)
- Whirlpool: one focused CTA gave 42% more clicks (single case). The "371% more clicks with a single CTA" figure circulates in roundups but I could not trace its source. — [Econsultancy](https://econsultancy.com/three-case-studies-to-help-improve-your-email-marketing-conversion-rates/), [Bloggerspassion](https://bloggerspassion.com/call-to-action-statistics/)
- Practitioner pattern: one prominent button plus one or two supporting text links. — [Vero](https://www.getvero.com/resources/email-marketing-calls-to-action/)
- "Start my free trial" vs "your": 90% more clicks (Unbounce/ContentVerve, landing page, not email); Joanna Wiebe replication ~24%; a payment-page test where "your" lost by 24.95%; reported non-replication in Danish tests (unverified). — [Mail Blaze](https://mailblaze.com/thinking/email-cta-copy-first-person-second-person), [ClickZ](https://clickz.com/me-vs-you-how-pronouns-affect-click-conversion-rates/32596/)

### Inferences
Button copy should name the outcome ("Get my guide") rather than "Submit"/"Click here"; repeat the same CTA link in the opening and the close for long emails. Placement guidance is my synthesis, not tested here.

### Gaps
No placement (above-the-fold vs bottom) study found; no multi-CTA-count dataset from a primary source.

## P.S. lines and sign-offs

### Takeaway
Sources agree a P.S. should be one or two sentences with a single job (restate offer from a new angle, add urgency, or give a secondary action) and not be in every email. I found no data or named-copywriter quotes beyond vendor guides.

### Cited Findings
- Restate the main selling point from a different angle because some readers jump to the bottom; do not repeat body copy verbatim; do not introduce unrelated ideas; don't apologize for length; overuse kills its effect. — [HubSpot](https://blog.hubspot.com/blog/tabid/6307/bid/16909/6-awesome-email-marketing-powers-of-the-p-s.aspx), [Mailmodo](https://mailmodo.com/guides/ps-in-email), [SmartrMail](https://www.smartrmail.com/blog/ps-in-email-guide)
- Examples: "Get a 20% discount on your first order using code PS20 at checkout!"; "Reply and tell us your #1 goal this year - a real person reads every message." — [Mailmodo](https://mailmodo.com/guides/ps-in-email)

### Inferences
A reply-inviting P.S. in a welcome email also helps deliverability signals (my inference, unsourced here).

### Gaps
Nothing found on how top copywriters (Halbert, Kennedy, Wiebe, etc.) write P.S. lines or sign-offs; no sign-off data.

## Links, images, plain text vs HTML

### Takeaway
Simpler, more plain-text-looking emails often win on opens/clicks in vendor tests, but a 700-reader newsletter test went the other way; it depends on audience and purpose.

### Cited Findings
- HubSpot: in every A/B test the simpler-design email won; more HTML-rich emails had lower open rates. — [HubSpot](https://blog.hubspot.com/marketing/plain-text-vs-html-emails-data)
- Campaign Creators (700+ readers): HTML gave about 2% higher opens and 2.71% higher CTR than plain text. Conflicts with HubSpot. — [Campaign Creators](https://www.campaigncreators.com/blog/html-vs-plain-text-emails)
- Litmus ran an HTML vs plain-text webinar-registration test; result not visible in my results. A Notion-hosted self-report of 21% higher CTOR for plain text (50K sends) is unverified. — [Litmus](https://www.litmus.com/blog/the-results-are-in-a-b-testing-html-vs-plain-text-emails)

### Inferences
Always include a plain-text MIME part and alt text; keep image-to-text ratio text-led. (Standard practice, unsourced here.)

### Gaps
No image-blocking or link-count (number of links vs deliverability) data retrieved.

## Email length and depth

### Takeaway
Click-focused data points to about 100-250 words for marketing email; very long emails underperform on clicks in that data, but reply-rate and internal-email studies suggest different optima. No evidence found that long-form wins, though long-form is plausible for high-intent/story sales sequences.

### Cited Findings
- NP Digital (Jan 2024): 100-249 words had the highest click rate (3.84%; a companion page reports 3.57%, from 26 companies); emails over 500 words fell below 1%. — [Neil Patel/NP Digital](https://neilpatel.com/marketing-stats/email-click-rates-by-email-length/)
- Constant Contact (2.1M+ customers, undated): about 20 lines of text had the highest CTR (~150-200 words per one summary). — [Drip](https://drip.com/blog/ideal-email-length)
- Boomerang (2016, 40M emails, reply rate): 75-100 words had highest response rate (51%), the origin of 50-125 word advice; PoliteMail (2018, internal email): under two minutes (~400-500 words) did best. Different outcomes and contexts, so do not apply to marketing clicks. — [MailUp](https://mailup.com/blogs/email-length/), [Ragan](https://www.ragan.com/study-6-best-practices-for-email-success/)
- Reported "95 words highest CTR" (MarketingExperiments) is second-hand and old. — [Drip](https://drip.com/blog/ideal-email-length)

### Inferences
Match length to goal: clicks to a page (short, 50-200 words), nurture/storytelling and high-consideration offers can justify longer copy but need strong structure. This is a hypothesis; no cited test compared long vs short by goal.

### Gaps
No study of long-form sales/launch emails vs short; no Litmus/Klaviyo length data.

## Mobile, dark mode, accessibility

### Takeaway
Most opens are on mobile or Apple clients; design for small screens, dark mode and screen readers. Mobile share estimates conflict widely.

### Cited Findings
- Mobile share conflicts: one aggregator reports 42% of opens and another 46%, a third says opens rose from 49% (2022) to 55% (2025), another 61.9%; Litmus 2021 reported 72% of subscribers opened exclusively on mobile (different measure: share of subscribers). Not averaged. — [Mailmodo](https://www.mailmodo.com/guides/mobile-email-statistics), [Genesys Growth](https://genesysgrowth.com/blog/mobile-email-engagement-stats-for-marketing-leaders), [Marketing Dive](https://www.marketingdive.com/news/66-of-email-opens-now-come-from-mobile/261744/)
- Client share (Litmus Email Client Market Share, July 2026, via Courier; secondary): Apple 62.26%, Gmail 27.03%, Outlook 5.83%; dark mode usage cited as over 25%. Earlier Litmus: dark mode about 34-35% of opens in 2022. Potential methodology difference; not reconciled. — [Courier](https://www.courier.com/blog/dark-mode-email-design), [Litmus](https://www.litmus.com/blog/the-state-of-email-engagement-when-where-and-how-people-engage-with-email/)
- Accessibility (vendor guidance): contrast 4.5:1 normal text, 3:1 large text; body font 14px minimum, 16px recommended (these are practice recommendations; WCAG sets no pixel minimum); meaningful alt text; test light and dark; transparent PNG/SVG for dark mode; European Accessibility Act in force June 2025. — [Email Love](https://help.emaillove.com/plugin/getting-started/accessibility), [Adobe](https://experienceleague.adobe.com/en/docs/journey-optimizer-b2b/user/content-management/emails/email-accessible-content), [Really Good Emails](https://reallygoodemails.com/school/feedback-fridays/accessible-email-makeovers)

### Inferences
Single-column layout, 16px body, tappable buttons (commonly 44px height; unsourced here), and lang attribute are safe defaults.

### Gaps
Litmus State of Email 2025/2026 and Baymard/Email on Acid pages not retrieved; no primary mobile-share figure.
