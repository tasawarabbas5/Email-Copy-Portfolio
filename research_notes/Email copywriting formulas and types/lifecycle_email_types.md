# Lifecycle and Automated (Behavior-Triggered) Email Types

Method note: WebFetch failed (DNS errors) for every domain tried (omnisend, klaviyo, litmus, attribuly, poweredbysearch), so everything below comes from WebSearch result summaries of the linked pages, not full-page reads. Nearly all sources are vendor/agency blogs with commercial interest; stats are vendor-reported. No search surfaced Flowium, Really Good Emails, Milled, Copyhackers or Chase Dimond material directly. No per-email "teardown" of a named brand welcome/win-back/replenishment email was verified. Pages dated where the search showed a date.

## 1. What is the job and single goal of each email type? (and trigger/timing)

### Takeaway
Each lifecycle email maps to one trigger and one job: welcome = first purchase/relationship; cart = recover intent; browse = nudge lighter intent; post-purchase = reassure then build the next purchase; review/referral = social proof/growth; win-back/sunset = reactivate or remove; replenishment = timed reorder; trial = activation then conversion. Timing is anchored to the behavior (or predicted behavior), not the calendar.

### Cited Findings
- Welcome: flow introduces brand story, delivers the discount code, and guides to first purchase — [Retainful](https://www.retainful.com/blog/welcome-email-series)
- Abandoned cart: first email typically ~1 hour after abandonment (30 min for high-intent/high-AOV; 1-4 hours for standard carts); follow-ups ~12-24h and ~24-72h; three emails is the usual recommendation; 4-5 for high-value purchases over about a week; more than 3-4 for standard products can raise unsubscribes without lifting conversion — [Omnisend](https://www.omnisend.com/blog/cart-abandonment-email), [Attribuly 2026 guide](https://attribuly.com/blogs/abandoned-cart-email-sequences-cadence-copy/), [Retainful](https://www.retainful.com/blog/send-multiple-shopify-abandoned-cart-emails) (as summarized by search; vendor sources vary: Shopify uses 1 day and 3 days)
- Cart variant: Klaviyo-style sequence cited as reminder at 2-4h, discount at 24h, last push at 48h — [Enrich Labs 2026](https://www.enrichlabs.ai/blog/abandoned-cart-email-complete-guide-2026)
- Checkout abandoners (higher intent) argued to need first email at 30-60 min; Klaviyo's default cart template may fire only on Added to Cart, missing checkout abandoners, so build a separate checkout flow — [Attribuly 2026](https://attribuly.com/blogs/browse-abandonment-vs-cart-abandonment-comparison/)
- Browse abandonment: starts ~2-4h after view, then +24-48h, lighter cadence; educational tone; discounting less common/necessary; runs off Viewed Product event so only reaches identified subscribers — [Attribuly](https://attribuly.com/blogs/browse-abandonment-vs-cart-abandonment-comparison/), [FirstPier](https://www.firstpier.com/glossary/browse-abandonment). A Klaviyo benchmark (cited by CodeCrew) says top browse flows sent 2 emails or fewer, within a few hours — [CodeCrew](https://codecrew.us/?p=2977) (secondhand; original not verified)
- Post-purchase: sequence includes order/shipping confirmation, product tips/how-to, review request, cross-sell/replenishment, loyalty/referral invitation; lead with helpfulness, time to delivery/use, then next-purchase nudge — [Litmus](https://www.litmus.com/blog/post-purchase-emails), [Moosend](https://moosend.com/blog/post-purchase-email-strategies/), [Mailmunch](https://www.mailmunch.com/blog/post-purchase-emails)
- Review requests: most agency guidance is 7-14 days post-delivery, with a reminder 5-7 days later for non-responders; Klaviyo's help center notes timing by delivery is limited (Shopify only; WooCommerce based on fulfillment date); Klaviyo's standard integration does not track delivery — [Top Growth Marketing](https://topgrowthmarketing.com/tools/klaviyo-flow-checklist/), [Klaviyo help](https://help.klaviyo.com/hc/en-us/articles/115002779391-How-to-create-a-product-review-flow), [Klaviyo community](https://community.klaviyo.com/questions/5287)
- Referral: standard part of post-purchase alongside loyalty invites; only send if a program exists. Guidance is thin — [Moosend](https://moosend.com/blog/post-purchase-email-strategies/)
- Win-back: trigger delay should exceed average buying cycle (Klaviyo example 75 days); keep to 3 emails; first email short with top sellers/new releases plus incentive; deadline on discount; can use predicted next-order date — [Klaviyo help: Winback flow](https://help.klaviyo.com/hc/en-us/articles/115002775192)
- Sunset: based on all engagement (not purchases); last chance to reaffirm interest or opt out; ask to update preferences or unsubscribe to protect deliverability; keep still-engaged contacts — [Klaviyo help](https://help.klaviyo.com/hc/en-us/articles/115002775192), [Klaviyo Academy](https://academy.klaviyo.com/en-us/courses/automating-the-customer-journey-with-flows/lessons/say-goodbye-to-unengaged-customers)
- Transactional-as-marketing: customers expect them, so opens are high (order confirmations cited up to 70-90% depending on industry — vendor claim, no year/original); confirmation = reassurance with items, tracking, address, support contact, delivery window; shipping notices give tracking and cut support contacts — [Vero](https://blog.getvero.com/transactional-email/), [Bird](https://bird.marketing/blog/digital-marketing/guide/email-marketing-strategies/role-transactional-emails-marketing/)
- Compliance for promo in transactional: CAN-SPAM exempts transactional, but advice is state purpose in the subject line, keep transactional content substantially larger than promo and placed first (not legal advice) — [Vero](https://blog.getvero.com/transactional-email/), [iubenda](https://www.iubenda.com/en/blog/transactional-email-vs-marketing-email-whats-the-difference/)
- Birthday/anniversary: collect birthday at signup (optional field); send morning of or a few days before (free items) / on the day or start of month (discounts); offer valid ~1 week to 3-4 weeks; 20-25% suggested to feel like a gift; one prominent CTA; reminder for unredeemed (Chandon "Birthday Savings End Soon!"); examples Munk Pack 25% code, Manchester United 10%, Care/of first-year anniversary with recap + discount — [Omnisend birthday](https://www.omnisend.com/blog/birthday-emails-tips-and-best-practices/), [Omnisend anniversary](https://www.omnisend.com/blog/anniversary-email/), [Mailjet](https://www.mailjet.com/blog/email-best-practices/the-best-anniversary-emails/). Sources disagree on timing.
- Back-in-stock: Klaviyo recommends 1-3 messages, pre-built flow, Smart Sending; triggered by integration metric, custom catalog or API — [Klaviyo help](https://help.klaviyo.com/hc/en-us/articles/115003872251-How-to-build-a-back-in-stock-flow). Price drop: show old and new price with urgency CTA, needs catalog integration, target viewers — [Top Growth Marketing](https://topgrowthmarketing.com/tools/klaviyo-flow-checklist/). Stats: ~65% open (Barilliance) and 7.28% conversion (ConvertCart), unverified secondhand via [Glazed Digital](https://glazedigital.com/blogs/news/get-back-in-business-guide-to-klaviyo-back-in-stock-flows)
- Replenishment: first nudge a few days before expected run-out (e.g., ~day 25 of a 30-day supply; or 5-7 days before run-out); follow-up 3-5 days later; small incentive only in final email after predicted depletion; separate flows by product cycle; survey buyers to segment 20/30/45-day flows — [Repeat](https://getrepeat.io/plays/replenishment-reminder-email-flow), [Retainful](https://help.retainful.com/automations/use-cases/reorder-reminder), [Stamped](https://connect.stamped.io/plays/replenishment-reminder), [1-800-DTC](https://1800dtc.com/resources/guides/replenishment-flows-repeat-orders-d2c-guide)
- Upsell/cross-sell: best within days to a week of purchase; pair an owned product with one not owned; use social proof; frame by customer benefit; a cross-sell block can ride in review request emails — [Litmus](https://www.litmus.com/blog/post-purchase-emails), [Stamped](https://connect.stamped.io/use-cases/cross-sell-related-products-in-review-requests)
- SaaS trial: Customer.io-style cadence template 0/1/3/5/7/14 days, each email tied to an aha moment/activation event that advances or exits the user; 6-email trial sequence with a middle block of three educational emails; behavioral triggers preferred over time-only; unverified claim that 40-60% of signups log in once and never return — [HowdyGo](https://web.howdygo.com/blog/saas-onboarding-email-examples), [Powered by Search](https://www.poweredbysearch.com/blog/customer-lifecycle-emails-b2b-saas-trials/), [Sequenzy](https://www.sequenzy.com/blog/saas-email-sequence-examples)
- Trial expiry: start 3-4 days before end (Bento) or 3-7 days (Sequenzy); show what user accomplished and tie to what they'd lose; one button, clear pricing; send general expiry only to users who saw value (Encharge); paid trials must disclose charges (Userlist); follow-up 2 days later with incentive or feature recap — [Bento](https://bentonow.com/posts/trial-expiration-email-best-practices), [Encharge](https://encharge.io/trial-expiration-email-templates/), [Userlist](https://userlist.com/blog/trial-expiration-emails-saas/), [User.com](https://testusere.user.com/use-cases/trial-expiry-conversion). Sequenzy claim of 2-5% vs 8-15% conversion with sequence is vendor-reported ([Sequenzy](https://sequenzy.com/blog/free-trial-expiring-email-sequence)).

### Inferences
- The single-goal framing (one CTA per email) is consistent across sources (birthday, trial, welcome) and can be generalized to all types.
- Incentives are best sequenced late (cart email 3, replenishment final, win-back first-only for lapsed buyers) to protect margin; sources agree for cart and replenishment, win-back guidance differs (Klaviyo puts an incentive in email 1).

### Gaps
- No primary Klaviyo/Omnisend benchmark pages could be fetched, so timing figures are agency/vendor consensus, not tested data.
- No sourced timing for the "anniversary" of customer relationship beyond general guidance.
- Referral request email structure and performance: only thin, generic guidance found.

## 2. What does the best-performing structure look like (sections, order, flow size, spacing)?

### Takeaway
Short flows with one job per email win: 3-email welcome (story+offer, social proof/bestsellers, deadline), 3-email cart (reminder, objection handling/social proof, urgency or incentive), 1-3 for back-in-stock, 2 or fewer for browse, 3 for win-back.

### Cited Findings
- Welcome 3-email DTC template: email 1 brand story + offer, email 2 social proof and bestsellers, email 3 deadline reminder; send immediately, +2 days, +2 days; typical 10-15% incentive, one-line brand story, single CTA — [Top Growth Marketing](https://topgrowthmarketing.com/welcome-email-template-dtc-brands/)
- Story can beat discount for considered purchases or thin margins — [Darkroom](https://www.darkroomagency.com/observatory/welcome-email-examples)
- Cart: email 1 simple product-focused reminder; email 2 addresses hesitation (reviews, product details, social proof); email 3 urgency and optional incentive — [Omnisend](https://www.omnisend.com/blog/cart-abandonment-email), [Attribuly](https://attribuly.com/blog/abandoned-cart-email-examples)
- Win-back email 1: short and light, top sellers/new releases, acknowledge the lapse, personalize, deadline discount; max three emails — [Klaviyo help](https://help.klaviyo.com/hc/en-us/articles/115002775192)
- Replenishment: gentle reminder, follow-up +3-5 days, final with small incentive — [Repeat](https://getrepeat.io/plays/replenishment-reminder-email-flow)
- Trial: 6 emails including three single-problem educational emails; trial expiry reminders escalate in directness — [Powered by Search](https://www.poweredbysearch.com/blog/customer-lifecycle-emails-b2b-saas-trials/), [Bento](https://bentonow.com/posts/trial-expiration-email-best-practices)

### Inferences
- Anatomy pattern across flows: personalized hook tied to the trigger, the item/context, one CTA, a single objection-handler (reviews, shipping/returns), then a deadline only where relevant.

### Gaps
- No verified A/B-tested data on optimal flow length per type; Klaviyo's "2 emails or fewer" browse finding is secondhand.
- Typical word counts per email type were not found in sources.

## 3. Copy tactics, benchmarks and real examples

### Takeaway
Specificity wins: product name, first name, trigger-aware references, and on-brand voice beat generic "you left something behind." Benchmarks are vendor-reported and vary hugely.

### Cited Findings
- Cart subject lines: product name plus first-name personalization associated with highest opens; categories of tone: charm, urgency, gentle reminder; examples from MOSCHINO, Casper, Jack Wills (free-shipping hook, playful "basket" joke) (OptimonK, Oct 2024); Boka (pun), On (name plus finish-line theme), Tentree, Magic Spoon, Headspace; Kohl's (name in subject), Fast Growing Trees (body copy personalized to cart item) — [OptimonK](https://www.optimonk.com/abandoned-cart-subject-lines), [Creoate](https://blog.creoate.com/abandoned-cart-email-examples), [Zapier](https://zapier.com/es/blog/abandoned-cart-email-examples/), [Attribuly June 2026](https://attribuly.com/blog/abandoned-cart-email-examples)
- Welcome benchmarks conflict: Klaviyo 2025 report 51% avg open, top click ~15%, placed-order rate nearly 10% for top welcome emails; GetResponse 83.6% open and 16.6% CTR; Constant Contact 2026 68-84% vs ~30.8% marketing emails; Blackbaud 2019 nonprofit 19.32% — [Klaviyo/summary via Neal Schaffer](https://nealschaffer.com/welcome-email/), [Constant Contact 2026](https://community.constantcontact.com/empowerment-hub/post/welcome-email-benchmarks-why-they-get-4x-the-opens-2026-data-PFyIToDw7b0vVX7), [Blackbaud](https://institute.blackbaud.com/explorer/welcome-series/). Apple Mail Privacy Protection inflates opens in many datasets.
- Series vs single welcome: 51% more revenue claimed from Mailchimp case data (secondhand) — [Neal Schaffer](https://nealschaffer.com/welcome-email/)
- Birthday: make the offer feel like a gift (not the usual discount), reference purchase history/favorite categories — [Omnisend](https://www.omnisend.com/blog/birthday-emails-tips-and-best-practices/)
- Trial expiry: honest urgency over pressure — [Sequenzy](https://sequenzy.com/blog/free-trial-expiring-email-sequence)
- Upsell: keep suggestions focused and relevant — [Litmus](https://www.litmus.com/blog/post-purchase-emails)

### Inferences
- Because metrics differ 4x between sources, the report writer should present benchmarks as ranges and flag Apple MPP inflation.

### Gaps
- No directly retrieved teardowns from Really Good Emails, Milled, Flowium, Copyhackers or Chase Dimond; Customer.io's own docs not retrieved.
- Real-brand subject/body examples for welcome, win-back, replenishment, upsell are missing.

## 4. What mistakes kill performance?

### Takeaway
Common failures: wrong timing, missing suppression, over-discounting, too many emails, trigger setup gaps, and promo-heavy transactional emails.

### Cited Findings
- Too many cart emails (>3-4 for standard products) raise unsubscribes without conversion gain — [Attribuly](https://attribuly.com/blogs/abandoned-cart-email-sequences-cadence-copy/)
- Cart flow set on Added to Cart only misses checkout abandoners — [Attribuly](https://attribuly.com/blogs/browse-abandonment-vs-cart-abandonment-comparison/)
- Replenishment: sending too early/late, identical cadence for all, and not suppressing customers who already reordered; many reorder at full price after a mere reminder — [Repeat](https://getrepeat.io/plays/replenishment-reminder-email-flow)
- Review requests triggered by order/fulfillment date rather than delivery arrive before the product — [Klaviyo community](https://community.klaviyo.com/questions/5287)
- Sunset: keeping unengaged contacts hurts deliverability — [Klaviyo help](https://help.klaviyo.com/hc/en-us/articles/115002775192)
- Referral emails sent without a program — [Moosend](https://moosend.com/blog/post-purchase-email-strategies/)
- Transactional emails where promotional content outweighs or precedes transactional content risk losing exemption — [Vero](https://blog.getvero.com/transactional-email/)
- Trial emails: aggressive pressure backfires; sending expiry email to users who never saw value — [Sequenzy](https://sequenzy.com/blog/free-trial-expiring-email-sequence), [Encharge](https://encharge.io/trial-expiration-email-templates/)
- Birthday: using the same everyday discount — [Omnisend](https://www.omnisend.com/blog/birthday-emails-tips-and-best-practices/)
- Welcome flows break on complexity — [Top Growth Marketing](https://topgrowthmarketing.com/welcome-email-template-dtc-brands/)

### Inferences
- A cross-flow rule: add exit conditions and cross-flow suppression (purchase, reply, activation) so recipients are never in conflicting flows.

### Gaps
- Mistake lists for back-in-stock, price-drop, and browse flows are thin (mostly scale/trigger setup).
