# SB Enterprise: Meta Ads Professional Playbook
### B2B lead generation for window & door hardware: getting fabricators, builders, contractors, architects and distributors

> **Who this is for:** the owner and sales team of SB Enterprise.
> **Goal:** use Meta (Facebook, Instagram, WhatsApp) to get **big, repeat B2B buyers**, not small one-time retail customers.
> **Assumptions:** you sell window/door hardware (rollers, locks, handles, hinges, fittings) in India and spend in ₹. Wherever you see **[X]**, put your real number. Never put fake numbers in ads.
> **Note:** Meta changes button names and menus often. If a menu name here doesn't match exactly, look for the closest option. The strategy stays the same.

---

## Table of contents
1. [The core rules that make B2B Meta Ads work](#1-the-core-rules)
2. [Infrastructure setup (do this once, properly)](#2-infrastructure-setup)
3. [Tracking & data: Pixel, Conversions API, UTMs, CRM feedback](#3-tracking--data)
4. [Account & campaign architecture](#4-account--campaign-architecture)
5. [Budget math & bidding](#5-budget-math--bidding)
6. [Audience strategy (advanced)](#6-audience-strategy)
7. [Lead form engineering: filtering for big buyers](#7-lead-form-engineering)
8. [Click-to-WhatsApp system](#8-click-to-whatsapp-system)
9. [Offer engineering for big buyers](#9-offer-engineering)
10. [Creative system: angles, hooks, formats, testing](#10-creative-system)
11. [Ready-to-use ad copy bank](#11-ad-copy-bank)
12. [Video scripts & shot lists](#12-video-scripts)
13. [Full-funnel & retargeting sequences](#13-full-funnel--retargeting)
14. [Account-Based Marketing (ABM) for named big accounts](#14-account-based-marketing)
15. [Speed-to-lead & sales process](#15-speed-to-lead--sales-process)
16. [Lead scoring system](#16-lead-scoring)
17. [Measurement: KPIs, unit economics, dashboard](#17-measurement)
18. [Optimization rules: daily, weekly, monthly](#18-optimization-rules)
19. [Scaling playbook](#19-scaling-playbook)
20. [Account safety & policy](#20-account-safety--policy)
21. [Other channels that multiply Meta results](#21-other-channels)
22. [90-day roadmap with budgets](#22-90-day-roadmap)
23. [Templates & checklists](#23-templates--checklists)

---

## 1. The core rules

These ten rules matter more than any setting.

1. **Creative is the new targeting.** Meta's algorithm decides who sees your ad mostly from **what the ad says and shows**. An ad showing a warehouse full of stock, truck dispatch and "for bulk/project orders" will be shown to business buyers. An ad saying "cheap price" will be shown to bargain hunters.
2. **Optimize for the event you actually want.** If you optimize for "any lead", Meta finds people who fill forms easily (often low quality). Send Meta signals of **qualified leads and sales** (Section 3), so it learns who your *real* buyers are.
3. **Add friction on purpose.** For B2B, a slightly harder form gives **fewer, much better leads**. A cheap lead is not the goal; a cheap **customer** is.
4. **Consolidate, don't fragment.** Few campaigns, few ad sets, enough budget each. Ten tiny ad sets at ₹200/day each never exit the learning phase.
5. **Speed-to-lead beats everything.** A B2B lead called within 5 minutes converts far better than one called next day. Ads only open the door.
6. **Judge on the right timeline.** B2B sales take 2–12 weeks. Judge ads on **cost per qualified lead weekly** and on **revenue monthly/quarterly**, not on likes or clicks.
7. **Volume of creative testing = growth.** Accounts that grow launch **3–5 new creatives every week**. Most fail; a few winners pay for everything.
8. **Proof beats claims.** "Tested 50,000 cycles" with a video > "Best quality".
9. **Your data is your moat.** Customer lists, lead stages and video viewers become audiences competitors can't copy.
10. **Meta is one part of the system.** Meta creates demand and leads. Google Search captures ready buyers. LinkedIn and personal sales close big accounts.

---

## 2. Infrastructure setup

### 2.1 Business assets checklist (professional level)

| Asset | Setting / detail | Why it matters |
|---|---|---|
| **Meta Business Portfolio** (business.facebook.com) | Legal business name exactly as on GST | Needed for verification |
| **Business verification** | Security Center → Start verification → GST certificate / utility bill / bank document with same name & address | Higher trust, fewer restrictions, access to more features (e.g., WhatsApp API) |
| **2 admins minimum** | Owner + one trusted person, both with 2-factor authentication | If one profile gets locked, you don't lose the business |
| **Ad account** | Currency **INR**, time zone **Asia/Kolkata**. *These can't be changed later* | Correct reporting & billing |
| **Backup ad account** | Create a second ad account inside the portfolio, keep it idle | If main account gets restricted, you don't stop |
| **Payment** | Card/UPI + backup card. For larger spends, consider prepaid funds | Failed payment = ads stop = learning reset |
| **Facebook Page** | Category: "Hardware Store" / "Industrial Company" / "Building Materials". Complete About, phone, WhatsApp, address, website, hours | Buyers check your Page before calling |
| **Instagram Professional account** | Linked to the Page in Business Settings → Accounts | Instagram placements + DMs |
| **WhatsApp Business** | App for small scale; **WhatsApp Business Platform (API)** via a provider (e.g., Interakt, WATI, AiSensy, Gupshup) for automation | Auto-replies, tagging, conversion feedback to Meta |
| **Domain verification** | Brand Safety → Domains (if you have a website) | Control of link previews and events |
| **Pixel / Dataset** | Events Manager → Connect data source → Web | Website tracking + retargeting |
| **Conversions API** | See Section 3 | Accurate tracking + lead quality feedback |
| **Lead CRM** | Google Sheet to start; later a real CRM (Zoho CRM, LeadSquared, HubSpot, Pipedrive, etc.) | Track lead stage, send stages back to Meta |

### 2.2 Page "trust layer" before spending a rupee

A big buyer will open your Page after seeing an ad. Make sure they see:
- **Pinned post:** company intro video (owner on camera, 45–60 sec).
- **Highlights on Instagram:** `Products` · `Factory/Warehouse` · `Dispatch` · `Projects` · `Tests` · `Clients` · `Catalog`.
- **At least 12 posts** covering products, tests, dispatch, projects, team.
- **Reviews/recommendations** from 10+ real customers (ask fabricators who like you).
- **Same logo, colours, phone number** everywhere: Page, Instagram, WhatsApp, visiting card, packaging.

### 2.3 Sales assets you must have ready (big buyers will ask)

- [ ] **Company profile PDF** (4–8 pages): about, years, capacity, warehouse, range, clients/projects, certifications, contact.
- [ ] **Full catalog PDF** with codes, sizes, finishes, materials, load ratings.
- [ ] **Project price list** with volume slabs (e.g., up to 1,000 units / 1,000–5,000 / 5,000+).
- [ ] **Test reports / warranty letter / material certificates** (whatever you genuinely have).
- [ ] **Sample kit box**: 8–12 best products, branded box, catalog + visiting card inside.
- [ ] **Case studies**: 3 short stories: "Builder X, 400 flats, supplied [X] units in [Y] days."
- [ ] **GST, PAN, bank details, cancelled cheque**: the "vendor registration pack" builders' procurement teams ask for.

---

## 3. Tracking & data

This is the **professional difference**. Most small businesses skip it and get junk leads.

### 3.1 Naming convention (use from day 1)

```
CAMPAIGN:  SB | {Objective} | {Funnel} | {Audience type} | {Geo} | {MMYY}
           SB | LEADS | BOFU | PROSPECTING | GUJ+MH | 1026

AD SET:    {Audience} | {Placement} | {Optimization} | {Budget type}
           BROAD-ADV+ | AUTO-NO-AN | LEADS | CBO

AD:        {Date} | {Angle} | {Format} | {Hook ID} | {Version}
           2610 | SCALE | VID-9x16 | H07 | v2
```
Why: when you have 60 ads, you instantly know which **angle** and **hook** wins.

### 3.2 UTM parameters (for website traffic ads)

In the Ad → **URL parameters** field, paste:
```
utm_source=meta&utm_medium=paid_social&utm_campaign={{campaign.name}}&utm_content={{ad.name}}&utm_term={{adset.name}}&placement={{placement}}
```
Meta fills the `{{ }}` values automatically. In Google Analytics/your website forms, you'll see exactly which ad brought each enquiry.

### 3.3 WhatsApp source tracking (simple but powerful)

Give each ad a **pre-filled message with a code**:
- Ad H07 scale video → pre-filled text: `Hi SB Enterprise, I want bulk price list. (Ref: M-H07)`
- Ad H03 test video → `... (Ref: M-H03)`

Your team records the Ref in the CRM. Now you know **which ad brings orders**, not just chats.

### 3.4 Pixel + Conversions API (CAPI)

- **Pixel** = browser tracking. Gets blocked by ad blockers, iOS privacy, etc.
- **Conversions API** = your server/CRM sends events directly to Meta. More reliable.
- Set up both, with **deduplication** (same `event_id` on both), so Meta doesn't double count.
- Easiest routes: website builder integrations (Shopify, WordPress plugins), Google Tag Manager server-side, or partners in **Events Manager → Partner integrations**.
- Check **Event Match Quality** in Events Manager. Aim for "Good" or better by sending hashed email + phone + name + city.

Website events to track:

| Event | When |
|---|---|
| `PageView` | Every page |
| `ViewContent` | Product/category page |
| `Contact` | Click on call / WhatsApp button |
| `Lead` | Enquiry form submitted |
| `DownloadCatalog` (custom) | Catalog PDF downloaded |
| `SubmitApplication` | Dealer / vendor registration form submitted |

### 3.5 The big one: send lead **stages** back to Meta (CRM feedback loop)

This is what makes Meta find **big buyers** instead of form-fillers.

**How it works:**
1. Lead comes from an Instant Form (Meta gives it a `lead_id`).
2. Your team updates the stage in CRM: `New → Contacted → Qualified (A/B) → Sample sent → Quote sent → Won`.
3. CRM sends each stage change back to Meta via **Conversions API for CRM** (Events Manager → Connect data → CRM; many CRMs and tools like Zapier/Make/LeadsBridge have connectors).
4. In your campaign, choose optimization **"Conversion leads"** (available once data flows), and pick your quality stage (e.g., `Qualified`) as the target.
5. Meta now optimizes toward people who look like **qualified buyers**, not form-fillers.

**Requirements (approximate, check Meta's current guidance):**
- Consistent volume, roughly **200+ leads per month** recommended.
- Upload stage updates **at least daily**.
- Target stage should be reached by a meaningful share of leads (not 0.1%, not 90%).

**Before you have that volume:** still record stages in a sheet. Every month, upload your **Qualified + Won** leads as a Custom Audience and build Lookalikes from them (Section 6).

### 3.6 Same feedback for WhatsApp (advanced)

If you use the **WhatsApp Business Platform (API)**, click-to-WhatsApp chats carry an ad referral ID. Your WhatsApp provider can send events like `LeadSubmitted` / `Purchase` back to Meta through **Conversions API for Business Messaging**. Then you can optimize WhatsApp campaigns for **qualified conversations or purchases**, not just "conversations started". Ask your WhatsApp API provider for "CTWA conversion tracking / CAPI".

---

## 4. Account & campaign architecture

### 4.1 Recommended structure (lean & professional)

```
CAMPAIGN 1: SB | LEADS | PROSPECTING          (60–70% of budget)
  Advantage campaign budget (CBO) ON
  ├─ Ad set A: BROAD (Advantage+ audience, geo + age only, with suggestions)
  ├─ Ad set B: INTEREST STACK (construction / fenestration / architecture / business owners)
  └─ Ad set C: LOOKALIKE 1–3% (best customers / qualified leads)
      Each ad set: same 4–6 best ads

CAMPAIGN 2: SB | LEADS/MESSAGES | RETARGETING (15–20% of budget)
  ├─ Ad set: Video viewers 50%+ (90 days) + IG/FB engagers (180 days)
  │          + lead form openers who did not submit + website visitors (30 days)
  │          EXCLUDE: leads already submitted (30 days), existing customers
  └─ Ads: proof-heavy: case studies, factory tour, testimonials, offer

CAMPAIGN 3: SB | TESTING | CREATIVE           (10–20% of budget)
  Ad set budgets (ABO), one ad set per new concept
  └─ Winners graduate to Campaign 1 (copy the post ID, keep social proof)

CAMPAIGN 4 (optional): SB | REACH/THRUPLAY | TOFU-VIDEO  (cheap reach)
  └─ Builds video-viewer pools in target cities for Campaign 2
```

### 4.2 Why this structure
- **Consolidation** gives each ad set enough conversions to exit learning (~50 optimization events/week per ad set).
- **Testing separated** from scaling, so a bad test doesn't hurt winning ads.
- **Retargeting separate**: warm audiences convert cheaper; they need different messages.

### 4.3 Key settings

| Setting | Recommended | Reason |
|---|---|---|
| Objective | **Leads** (Instant Form) for B2B quality; **Engagement → Messages (WhatsApp)** for dealer volume | Meta optimizes for the objective |
| Placements | Advantage+ placements **with Audience Network excluded**, or manual: FB/IG Feed, Reels, Stories, (optional) Explore, Marketplace | Audience Network = accidental clicks, junk leads |
| Attribution | 7-day click, 1-day view (default) for optimization; also look at **1-day click** in reporting | Shows real impact |
| Advantage+ creative enhancements | **Review each.** Keep: brightness/contrast, text improvements (test). Turn **off**: AI image generation/expansion/backgrounds that change product appearance | Product must look exactly real for B2B trust |
| Multi-advertiser ads | Off (optional) | Avoids your ad shown next to competitors |
| Language | Leave open, unless running regional-language creative | Many Indian users have English set |
| Dynamic creative / Flexible format | Use in **testing** campaign to test 3 texts × 2 headlines | Finds winning combinations faster |

---

## 5. Budget math & bidding

### 5.1 Minimum budget formula

To exit learning, an ad set needs ~**50 optimization events per week**.

```
Minimum daily budget per ad set ≈ (Target cost per lead × 50) ÷ 7
```

Example: target CPL ₹250 → (250 × 50) ÷ 7 ≈ **₹1,800/day per ad set**.

If you can't afford that: **use fewer ad sets** (put everything in 1–2), or optimize for a cheaper upper-funnel event at first. It's fine to stay in "Learning limited" with a small budget, but don't split it further.

### 5.2 Suggested monthly budgets (estimates; adjust to your numbers)

| Stage | Monthly spend | Structure |
|---|---|---|
| **Start / test** | ₹25,000–40,000 | 1 prospecting campaign (1–2 ad sets) + small retargeting |
| **Grow** | ₹60,000–1,50,000 | Full structure from 4.1 + 3–5 new creatives/week |
| **Scale** | ₹2,00,000+ | Add new states, conversion-leads optimization, Advantage+ leads campaigns (if available), more creative volume |

### 5.3 Bidding

| Strategy | When to use |
|---|---|
| **Highest volume (lowest cost)** | Start here. Let Meta learn. |
| **Cost per result goal (cost cap)** | Once you know your real CPL. Set it ~10–20% above your average to control cost while scaling. |
| **Bid cap** | Advanced only; strict control, can stop delivery. |

### 5.4 Budget change rules
- Change budgets by **≤20% at a time**, max once every **2–3 days**, to avoid resetting learning.
- For big jumps, **duplicate** the winning ad set/campaign with the higher budget instead of editing.
- Never pause a winning ad set for days and restart; performance often drops.

---

## 6. Audience strategy

### 6.1 Prospecting audiences (cold)

| Audience | How to build | Notes |
|---|---|---|
| **Broad / Advantage+ audience** | Geo + age 24–60 only, add "audience suggestions" (interests below) | Often the best performer once creative is strongly B2B. Let creative do the filtering. |
| **Interest stack** | Interests (OR): *Construction, Building materials, Civil engineering, Real estate development, Architecture, Interior design, Aluminium, Window, Glass, Fenestration, Hardware*; AND narrow by behaviour: *Small business owners* / *Facebook Page admins* (if available) | Test with/without the AND-narrowing |
| **Lookalike: best customers** | Upload top 50–200 customers (phone/email). Use a **value-based** list (add a "value" column = yearly purchase ₹). Create 1%, 1–3%, 3–5% India | Best way to find more big buyers |
| **Lookalike: qualified leads** | Monthly upload of A/B leads + Won | Gets better every month |
| **Lookalike: engaged video viewers 95%** | From your best B2B videos | Good when customer list is small |
| **Geo-pin audiences** | Drop pins with 10–25 km radius on industrial areas, aluminium/uPVC fabrication clusters, building-material markets, fast-growing real estate zones | Reaches fabricators/contractors physically there |

**Exclusions (always):**
- Existing customers (customer list), unless running an upsell campaign.
- Leads submitted in last 30 days (so you don't pay twice).
- Your own employees (upload their numbers).

### 6.2 Retargeting audiences (warm)

| Audience | Window |
|---|---|
| Video viewers 50% / 75% / 95% | 30 / 90 / 180 days |
| Instagram account engagers | 90 / 365 days |
| Facebook Page engagers | 90 / 365 days |
| **Instant form: opened but not submitted** | 30 / 90 days (very valuable: interested but hesitant) |
| Messaged your Page / WhatsApp | 90 days |
| Website: catalog/contact page visitors | 30 / 90 days |
| Website: top 25% time spent | 30 days |
| CRM: "Quote sent but not won" (customer list) | Upload weekly |

### 6.3 Geographic strategy for big buyers
- **Phase 1:** your home state + where you already deliver well (fast service = your advantage).
- **Phase 2:** 3–5 cities with heavy real-estate construction (check new project launches, RERA registrations in that city).
- **Phase 3:** states where you can appoint **distributors** (a distributor campaign, Section 9).
- Split ad sets by geo **only** when the message/offer differs (e.g., regional language), otherwise keep together.

### 6.4 Audience size guidance
- Prospecting: **≥ 10 lakh** people for broad; ≥ 2 lakh for interest/LAL.
- Retargeting: can be small (thousands), but needs ≥ ~1,000 to deliver well.

---

## 7. Lead form engineering

The Instant Form is your **quality filter**. Build it like this.

### 7.1 Form settings
- **Form type: Higher intent** (adds a review screen before submit → fewer accidental leads). Use phone verification if offered in your account.
- **Intro / context card:**
  - Headline: `Bulk & Project Supply: Window & Door Hardware`
  - Paragraph (or bullets):
    - `For fabricators, builders, contractors & dealers`
    - `[X]+ SKUs in stock · Dispatch in [X] hrs · GST invoice`
    - `Minimum project order: ₹[X]`  ← **this line filters small buyers**
  - Image: warehouse/dispatch photo.

### 7.2 Questions (in this order)

1. **Full name** (prefilled)
2. **Phone number** (prefilled)
3. **Company / firm name** (short answer, custom, adds healthy friction)
4. **City** (prefilled or short answer)
5. **You are a:** (multiple choice)
   - Aluminium / uPVC window fabricator
   - Builder / Developer
   - Contractor
   - Architect / Interior designer
   - Dealer / Distributor
   - Homeowner / Individual
6. **Monthly / project hardware requirement:**
   - Below ₹50,000
   - ₹50,000 – ₹2 lakh
   - ₹2 lakh – ₹10 lakh
   - Above ₹10 lakh
7. **What do you need now?**
   - Price list for bulk order
   - Quote for a specific project (BOQ)
   - Sample kit
   - Dealership / distributorship
8. **When do you need supply?** Immediately / within 1 month / 1–3 months / just exploring
9. **GST number** (short answer, optional)

**Conditional logic (if available in your form editor):** if "Homeowner" → skip to end with a message "Thank you! Our dealer near you will contact you." (they still become C leads).

### 7.3 Completion screen
- Headline: `Thank you, our project team will call you within 10 minutes (10am–7pm).`
- Button: **WhatsApp us now** (link: `https://wa.me/91XXXXXXXXXX?text=Hi%20SB%20Enterprise%2C%20I%20just%20submitted%20the%20form`) or **Download catalog**.

### 7.4 Lead delivery (never download manually once a day)
- Connect forms to a **CRM or Google Sheet in real time** (Meta native CRM integrations, Zapier, Make, Pabbly Connect, LeadsBridge).
- Trigger **instant WhatsApp/SMS** to the lead ("Thanks [Name], [Sales person] will call you in 10 minutes. Here's our catalog: [link]").
- Trigger **instant alert** to sales person's phone (WhatsApp group or CRM app notification).

### 7.5 Form A/B tests to run
- Higher intent vs More volume.
- With vs without "Minimum project order ₹X".
- With vs without GST question.
Track **cost per qualified lead**, not cost per lead.

---

## 8. Click-to-WhatsApp system

Best for **dealers, fabricators and repeat buyers** who prefer chatting.

### 8.1 Setup
- Objective: **Engagement** (or Leads/Sales with "Messaging apps" conversion location) → **WhatsApp**.
- Pre-filled message with Ref code (Section 3.3).
- **Ice-breakers / quick reply buttons** (if using templates):
  - `Bulk price list`
  - `Project quote (BOQ)`
  - `Become a dealer`
  - `Request sample kit`

### 8.2 Qualification flow (WhatsApp API bot or manual script)

```
Bot: Welcome to SB Enterprise 👋 Window & door hardware for fabricators,
     builders & dealers. Please choose:
     1️⃣ Bulk price list  2️⃣ Project quote  3️⃣ Dealership  4️⃣ Sample kit

Bot: Great! Which best describes you?
     Fabricator / Builder / Contractor / Architect / Dealer / Individual

Bot: Approx monthly requirement?
     <₹50k / ₹50k–2L / ₹2L–10L / ₹10L+

Bot: City?

→ If ₹2L+ or Builder/Dealer: "Thank you! [Name], our senior manager,
  will call you within 10 minutes." + instant alert to owner.
→ Else: send catalog PDF + price list + "Reply CALL for a callback."
```

### 8.3 WhatsApp tricks
- **Labels/tags**: `A-lead`, `B-lead`, `C-lead`, `Sample sent`, `Quote sent`, `Won`, plus the ad Ref.
- **Broadcast (with opt-in)** every 7–10 days to warm leads: new product, dispatch photos, project stories. Don't spam.
- **Catalog in WhatsApp Business** with codes and photos (no public price for project items; "Price on request" for bulk).
- **Reply time** is shown to users. Keep it fast.

---

## 9. Offer engineering

Big buyers don't respond to "10% off". They respond to **reduced risk and saved effort**.

| Offer | Target | Why it works |
|---|---|---|
| **"Send your BOQ / window schedule → detailed quote in 24 hours"** | Builders, contractors | Saves their procurement time; you get exact project size |
| **Free sample kit for verified fabricators/builders** (gated: GST + requirement ≥ ₹X) | Fabricators, architects | Physical product = trust. Gating keeps cost in control |
| **Trial order pricing** on first order ≥ ₹[X] | Fabricators | Removes risk of switching suppliers |
| **Dedicated account manager + priority dispatch** | Large fabricators, builders | Big buyers fear delays more than price |
| **Credit terms after [X] orders** (only if you can) | Repeat buyers | Major decision factor in B2B India |
| **Dealer / distributor program**: territory, margin, marketing support | Dealers in other cities | Scales your reach without your own sales team |
| **Spec support for architects**: spec sheets, CAD/BIM-friendly drawings, samples | Architects/designers | Gets you **specified** into projects → bulk orders later |
| **Private label / custom finish** (if you can) | OEMs, window system brands | Huge repeat volumes |
| **Factory/warehouse visit invitation** | Builders' procurement | Seeing scale = trust |

**Rule:** every ad has **one** clear offer + **one** clear action.

---

## 10. Creative system

### 10.1 Angles (the "why buy" message)

Test angles, not just designs. Each angle → 2–3 creatives.

| Code | Angle | Core message | Best for |
|---|---|---|---|
| A1 | **Pain: callbacks** | "Every failed roller = a site revisit and an angry customer." | Fabricators |
| A2 | **Proof: testing** | "50,000 open-close cycles. Still smooth." (only real test numbers) | Fabricators, architects |
| A3 | **Scale: stock** | "[X] SKUs, [X] lakh units in stock. No waiting." | Builders, big fabricators |
| A4 | **Speed: dispatch** | "Order by 2 pm, dispatch same day." (if true) | Contractors |
| A5 | **Economics** | "Hardware is 3% of window cost but 80% of complaints." | Fabricators, builders |
| A6 | **Authority: projects** | "Supplied to [X] projects / [X] flats across [state]." | Builders |
| A7 | **Founder trust** | Owner on camera: years in business, promise, phone number | All, especially big accounts |
| A8 | **Comparison** | Cheap vs SB side-by-side test | Fabricators |
| A9 | **Partner / dealer** | "Become SB distributor in your city: [X]% margins, territory protection" | Dealers |
| A10 | **Offer** | "Send BOQ → quote in 24 hrs" / "Free sample kit for verified fabricators" | All B2B |

### 10.2 Formats that work for B2B hardware

1. **Vertical video 9:16, 15–40 sec** (Reels/Stories): demos, tests, warehouse, dispatch.
2. **Founder/sales-head talking head** with B-roll cutaways.
3. **Customer testimonial** (a fabricator or builder on site, phone-shot, honest). The strongest format.
4. **Carousel**: one product family per card → last card "Get bulk price list".
5. **Static "spec card"**: product macro photo + 3–4 hard specs (material, finish, load, cycles) + "Bulk/project orders".
6. **Before/after site photos**: old failed hardware vs new installed SB hardware.
7. **Collection/Instant Experience** (optional): mini catalog inside Facebook.

### 10.3 Production rules (professional)
- **Hook in first 1–2 seconds**: movement, sound, bold claim, or a surprising visual (weight crushing a roller, 1,000 boxes on a truck).
- **On-screen captions always.** Burned-in subtitles in English/Hinglish.
- **Show the product in the hand / on the window**, not floating on white.
- **Real people, real locations** (factory, warehouse, site). Over-polished = looks like a retail brand ad.
- **Logo** small in a corner throughout, not as an intro.
- **Safe zones for 9:16**: keep text out of top ~14% and bottom ~20% (UI covers it).
- **Provide 3 aspect ratios**: 9:16 (Reels/Stories), 4:5 (Feed), 1:1 (backup). Use asset customization per placement.
- **Length:** 15–30 sec for cold; 45–90 sec okay for retargeting (case study, factory tour).
- **Sound:** trending/neutral music low + voiceover. Many watch muted, so text must carry the message alone.
- **AI product images:** use your product-scene-prompt skill to place real product photos into premium window scenes. Keep the product 100% accurate.

### 10.4 Hook bank (first line on screen / first words spoken)

| ID | Hook |
|---|---|
| H01 | "Fabricators, stop losing money on site revisits." |
| H02 | "This roller carried [X] kg for [X] cycles. Watch." |
| H03 | "Why do sliding windows fail in 6 months? It's not the profile." |
| H04 | "₹10 saved on a roller = ₹1,000 lost on a complaint." |
| H05 | "This is what [X] lakh units of stock looks like." |
| H06 | "Builders: one call, full hardware for your entire project." |
| H07 | "Today's dispatch: [X] boxes to [City]." |
| H08 | "Cheap vs ours: same price per window, different life." |
| H09 | "I've been supplying window hardware for [X] years. Here's my promise." |
| H10 | "Looking for a hardware distributor in your city? We're appointing." |
| H11 | "Send us your BOQ. Quote in 24 hours." |
| H12 | "Architects: get our spec sheet and free sample kit." |

### 10.5 Creative testing method

**Setup (Testing campaign, ABO):**
- 1 ad set per **concept/angle**, same audience (broad), budget ~₹500–1,000/day each.
- Inside: 3 creatives (different hooks/visuals) + 2 primary texts + 2 headlines (flexible/dynamic format). This is the "3-2-2" method.
- Run **5–7 days** or until each creative spent ≈ **3× your target CPL**.

**Kill / keep rules:**

| Signal after ~3× target CPL spend | Action |
|---|---|
| 0 leads | Kill |
| CPL > 2× target | Kill |
| CPL near target, but leads mostly C quality | Kill or rework message to be more B2B |
| CPL ≤ target AND ≥30% A/B leads | **Winner** → move to Prospecting campaign (use same post ID to keep likes/comments) |
| Hook rate (3-sec views ÷ impressions) < 20% | Hook problem → new first 2 sec |
| Hook rate good, but low hold/CTR | Body/offer problem → change middle/CTA |

**Iteration:** for every winner, make **3 variations** (new hook, new first visual, new person) → keeps fatigue away.

### 10.6 Creative fatigue signals
- Frequency > **3–4** in 7 days (prospecting).
- CTR falls **30%+** from its first-week average.
- CPL rises 30%+ for 3+ days with same budget.
→ Refresh with new hooks/visuals; keep the winning **angle**.

### 10.7 Creative production cadence
- **Weekly:** 3–5 new ads (1 shoot day / month can give 20+ clips).
- **Monthly shoot list:** 2 tests, 2 dispatch, 1 warehouse, 1 founder, 1–2 testimonials, 2 installation, 1 project walkthrough.

---

## 11. Ad copy bank

> Replace **[X]** with real numbers only. Keep claims true and provable.

### Copy 1: Fabricators (Pain + Proof), English
**Primary text:**
> Fabricators: one failed roller costs you a site revisit, a ₹1,000+ loss and an unhappy customer.
>
> SB Enterprise heavy-duty hardware is tested for [X] cycles and [X] kg load.
> ✅ [X]+ SKUs ready in stock
> ✅ Dispatch within [X] hours
> ✅ GST invoice · project pricing
>
> **For bulk & project orders only.** Tap *Get Quote* for the bulk price list.

**Headline:** Heavy-Duty Window Hardware: Bulk Price List
**Description:** Tested · In Stock · Fast Dispatch
**CTA button:** Get Quote

### Copy 2: Builders (Scale + Offer)
> Builders & developers: get complete window & door hardware for your project from one supplier.
>
> 📋 Send your BOQ/window schedule → detailed quote in 24 hours
> 🏗️ Supplied to [X]+ projects across [State]
> 🚚 Scheduled phase-wise delivery to site
> 👤 Dedicated project manager
>
> Tap *Get Quote* to share your project details.

**Headline:** Project Supply: Quote in 24 Hours
**CTA:** Get Quote

### Copy 3: Hinglish (Fabricators)
> Fabricator bhai, sasta roller = baar baar complaint, baar baar site visit. ❌
>
> SB Enterprise ka heavy-duty hardware: [X] cycles tested, [X] kg load. ✅
> 📦 [X]+ products stock mein ready
> 🚚 [X] ghante mein dispatch
> 🧾 GST bill, bulk rate
>
> Sirf bulk / project order ke liye. Price list ke liye *Get Quote* dabaiye.

**Headline:** Bulk Rate Price List: Window Hardware
**CTA:** Get Quote / Send WhatsApp Message

### Copy 4: Dealers / Distributors
> Hardware dealers: add a fast-moving window & door hardware range to your shop.
>
> 💰 Strong dealer margins
> 🗺️ Territory protection for distributors
> 📦 Ready stock + fast replenishment
> 📣 Marketing support: catalogs, display, digital ads in your area
>
> We're appointing distributors in [City/State]. Tap *Apply Now*.

**Headline:** Become SB Enterprise Distributor
**CTA:** Apply Now

### Copy 5: Architects / Designers
> Architects & interior designers: specify hardware that matches your design and lasts.
>
> 🎨 Finishes: [list your finishes]
> 📐 Spec sheets & technical drawings
> 📦 Free sample kit for practicing architects
>
> Tap *Learn More* to request the spec pack.

**Headline:** Free Spec Pack + Sample Kit
**CTA:** Learn More

### Copy 6: Retargeting (Founder trust)
> You checked out SB Enterprise. Here's why [X]+ fabricators and builders trust us:
>
> "[Short real customer quote]" – [Name], [Company], [City]
>
> [X] years · [X] SKUs · [X] projects supplied
> Talk to us directly on WhatsApp. No middlemen.

**CTA:** Send WhatsApp Message

### Copy 7: Retargeting (Form opened, not submitted)
> Still comparing hardware suppliers? Send us your requirement. We'll send a quote + free sample (for verified fabricators/builders) within 24 hours. No obligation.

**CTA:** Get Quote

---

## 12. Video scripts

### Script V1: "Strength test" (Fabricators), 20 sec
| Time | Visual | On-screen text / VO |
|---|---|---|
| 0–2s | Heavy weight placed on roller; close-up | **"Can your roller take [X] kg?"** |
| 2–8s | Machine/hand cycling the sliding sash fast; counter visible | "[X] cycles. Still smooth." |
| 8–13s | Side-by-side: cheap roller wobbling vs SB smooth | "Cheap rollers = callbacks." |
| 13–17s | Warehouse racks, boxes | "[X]+ SKUs in stock · Dispatch in [X] hrs" |
| 17–20s | Logo + phone, "For bulk/project orders" | "Tap Get Quote for bulk price list" |

### Script V2: "Warehouse scale" (Builders), 25 sec
| Time | Visual | Text / VO |
|---|---|---|
| 0–2s | Fast walk into warehouse, wide shot | **"This is what [X] lakh units of stock looks like."** |
| 2–10s | Racks, labelled bins, staff packing | "Every fitting your project needs, under one roof." |
| 10–16s | Truck loading, invoice/challan stamped | "Phase-wise delivery to your site." |
| 16–22s | Finished building with windows | "Supplied to [X]+ projects across [State]." |
| 22–25s | CTA card | "Send your BOQ → quote in 24 hours." |

### Script V3: "Founder promise", 40 sec
- **0–3s:** Owner in warehouse: "I'm [Name], founder of SB Enterprise. For [X] years, we've supplied window hardware to fabricators and builders."
- **3–15s:** "The biggest problem I hear: hardware fails, the fabricator gets blamed. So we test every batch for [X]." (B-roll testing)
- **15–28s:** "We keep [X]+ products in stock so your project never waits." (B-roll racks, dispatch)
- **28–40s:** "If you're a fabricator, builder or dealer, send me your requirement. My team will call you within 10 minutes." (CTA card)

### Script V4: "Customer testimonial", 30 sec
- Fabricator on their shop floor or site: name, firm, city.
- Questions to ask on camera: *What problem did you have before? Why did you switch? What changed (complaints, speed, profit)? Would you recommend us?*
- End with SB CTA card. Get written permission to use their name/face.

### Script V5: "Dispatch of the day" (series, weekly), 10–15 sec
- "Today's dispatch: [X] boxes to [City] for [type of project]." Truck loading time-lapse. Builds proof of scale continuously; cheap to make every week.

### Shot list for one monthly shoot day
- [ ] 10 product macro shots (each family, each finish)
- [ ] 3 strength/durability tests
- [ ] 1 cheap-vs-SB comparison
- [ ] Warehouse walk (wide + details)
- [ ] Packing & dispatch, truck loading time-lapse
- [ ] Installation on a real window (fabricator)
- [ ] Founder: 4–5 talking segments
- [ ] 1–2 customer testimonials
- [ ] Finished project exterior/interior
- [ ] Team photos (sales, warehouse)

---

## 13. Full-funnel & retargeting

### 13.1 Funnel map

```
TOFU (cold, cheap reach)        MOFU (warm, build trust)         BOFU (hot, ask for action)
─────────────────────────       ──────────────────────────       ──────────────────────────
Test/strength videos            Case studies, testimonials       Lead form: Get Quote / BOQ
Warehouse/dispatch reels   →    Factory tour, founder video  →   WhatsApp: price list
Educational: "why rollers       Spec sheets, comparisons         Sample kit offer
fail" content                                                    Dealer application
Optimize: ThruPlay / Reach      Optimize: Leads / Engagement     Optimize: Leads / Conv. leads
```

### 13.2 Retargeting sequence (by days since first engagement)

| Days | Message | Format |
|---|---|---|
| 0–3 | Offer: "Get bulk price list / BOQ quote" | Lead form ad |
| 4–10 | Proof: testimonial or project case study | Video |
| 11–20 | Founder trust + direct WhatsApp | Video / CTWA |
| 21–45 | Sample kit offer / factory visit invitation | Static + lead form |
| 45–90 | New products, dispatch reels (stay top-of-mind) | Reels |

Build with audience windows (e.g., video viewers 0–7 days, minus 0–3; etc.) or keep it simple: one retargeting ad set with 4–6 ads of different stages and let Meta rotate.

### 13.3 Frequency control
- Retargeting frequency up to **6–10/week** is okay for small warm B2B audiences, but refresh creatives every 2–3 weeks.

---

## 14. Account-Based Marketing

For **named big targets**, e.g., the top 50 builders, top 100 fabricators, top 30 window system companies in your region.

1. **Build a target list** (spreadsheet): company, decision maker, phone, email, city, project pipeline. Sources: RERA project registrations, builder association member lists, IndiaMART, Justdial, LinkedIn, exhibitor lists, your sales team.
2. **Upload as a Custom Audience** (phones + emails of owners, purchase heads, project managers). Even a partial match helps; small audiences may deliver slowly, so combine with lookalikes.
3. **Run a dedicated "ABM" campaign** with high frequency: case studies, founder video, project capability, "visit our warehouse".
4. **Coordinate with outbound:** the sales person calls/WhatsApps the same accounts that week ("You may have seen our videos...").
5. **Same list on LinkedIn** (Matched Audiences) for procurement heads.
6. **Track per account:** touched / meeting / sample / quote / won.

This "surround sound" (ads + calls + WhatsApp + visit) is how small suppliers win big accounts.

---

## 15. Speed-to-lead & sales process

### 15.1 SLAs (write these on the wall)

| Lead type | First contact | Owner |
|---|---|---|
| A lead (Builder/Dealer or ₹2L+/month) | **≤ 5 minutes** (call) | Senior sales / owner |
| B lead (₹50k–2L) | ≤ 30 minutes | Sales executive |
| C lead (small/homeowner) | Same day (WhatsApp catalog + dealer referral) | Junior / automation |
| After-hours leads | Auto WhatsApp instantly, call first thing next morning (before 10 am) | Automation + sales |

### 15.2 First call script (2–4 minutes)

1. **Open:** "Hello [Name], this is [You] from SB Enterprise. You requested our bulk price list a few minutes ago, is this a good time for 2 minutes?"
2. **Qualify (BANT-lite):**
   - "What do you mainly make / build?"
   - "Roughly how many windows/doors per month or in this project?"
   - "Which hardware are you using now? What problems do you face?"
   - "Who decides on hardware purchases?"
   - "When is your next requirement?"
3. **Position:** match 1–2 strengths to their pain (stock, testing, dispatch, credit).
4. **Next step (always one):** sample kit / BOQ quote / visit / trial order.
5. **Send immediately on WhatsApp:** company profile, catalog, relevant case study.

### 15.3 Follow-up cadence (don't stop at one call)

| Day | Action |
|---|---|
| 0 | Call + WhatsApp catalog/profile |
| 1 | WhatsApp: relevant test video / case study |
| 3 | Call: confirm sample kit / BOQ |
| 7 | WhatsApp: testimonial + "any questions?" |
| 14 | Call: quote follow-up / visit proposal |
| 30 | WhatsApp: new product / dispatch reel |
| Monthly | Stay in touch until they buy or say no |

### 15.4 Converting big accounts
- **Sample kit → site/factory visit → trial order → flawless delivery → regular orders → credit terms → annual rate contract.**
- After the first order: **call to check satisfaction**, fix any issue fast, ask for **testimonial + referral**.
- Offer **annual rate contracts** for builders and large fabricators (price stability is valuable to them).

---

## 16. Lead scoring

Score every lead in the CRM/Sheet (0–100):

| Factor | Points |
|---|---|
| Business type: Builder/Developer, Distributor, Window system company | 30 |
| Business type: Fabricator, Contractor | 20 |
| Business type: Architect/Designer | 15 (influencer, not buyer) |
| Business type: Homeowner | 0 |
| Requirement ₹10L+ | 30 |
| Requirement ₹2–10L | 20 |
| Requirement ₹50k–2L | 10 |
| Timeline: immediately / within 1 month | 15 |
| GST number given | 10 |
| Company name looks real / verifiable | 5 |
| Answered first call | 10 |

**A ≥ 60 · B 35–59 · C < 35.** Upload A + Won leads monthly as a Lookalike source.

---

## 17. Measurement

### 17.1 KPI stack

| Level | Metric | What it tells you |
|---|---|---|
| Creative | **Hook rate** = 3-sec video plays ÷ impressions | Does the first 2 sec stop scrolling? (aim 25%+) |
| Creative | **Hold rate** = ThruPlays ÷ 3-sec plays | Is the story interesting? |
| Creative | **CTR (link)** | Does the offer interest them? (≥1% decent) |
| Delivery | **CPM** | Cost to reach; rising CPM = fatigue or competition |
| Delivery | **Frequency** | Fatigue watch |
| Funnel | **Form open → submit rate** | Is the form too hard / too easy? |
| Funnel | **CPL** (cost per lead) | Basic efficiency |
| ⭐ Quality | **CPQL** (cost per qualified A+B lead) | Your main weekly KPI |
| ⭐ Quality | **% A+B leads** | Lead quality (aim 25–40%+) |
| Sales | **Lead → sample/quote rate**, **quote → win rate** | Sales team effectiveness |
| ⭐ Business | **CAC** = total ad spend ÷ new customers | Real cost of a customer |
| ⭐ Business | **ROAS / revenue per ₹1 spent** (first 90 days & 12 months) | Real return |

### 17.2 Unit economics: how much can you pay per customer?

```
Customer annual value (LTV-1yr)   = average monthly order × 12
Gross margin %                    = your margin
Gross profit per customer (1yr)   = LTV-1yr × margin
Max affordable CAC                = Gross profit per customer × 30–50%
Max affordable CPQL               = Max CAC × (qualified lead → customer rate)
```

**Example (illustration only):**
- Fabricator orders ₹1,00,000/month → ₹12,00,000/yr
- Margin 20% → ₹2,40,000 gross profit/yr
- Willing to spend 30% on acquisition → **Max CAC ≈ ₹72,000**
- If 1 in 8 qualified leads becomes a customer → **Max CPQL ≈ ₹9,000**

So even a ₹500 lead, or a ₹2,000 qualified lead, is **very profitable** if your team converts. **Most businesses under-spend on B2B leads because they look at CPL, not CAC.**

### 17.3 Ads Manager custom column set (save as "SB B2B")
Campaign name · Delivery · Budget · Amount spent · Impressions · Reach · Frequency · CPM · 3-sec video plays · ThruPlays · Hook rate (custom metric) · CTR (link) · CPC (link) · Leads · Cost per lead · Messaging conversations started · Cost per conversation · Conversion leads / Qualified (if CRM connected) · Cost per qualified lead.

**Custom metric:** Hook rate = `3-second video plays ÷ Impressions`.
**Breakdowns to check monthly:** Age, Placement, Region, Time of day (by Delivery → Time).

### 17.4 Weekly report template (fill every Monday)

| Week | Spend | Leads | CPL | A+B leads | CPQL | % A+B | Samples | Quotes | Wins | Revenue (new) | Best ad | Worst ad | Action |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| W1 | | | | | | | | | | | | | |

---

## 18. Optimization rules

### 18.1 Daily (10 minutes)
- [ ] Ads delivering? Any rejected ads / payment failures?
- [ ] All new leads contacted within SLA? (This is the most important daily check.)
- [ ] Any ad spending 3× target CPL with 0 leads → pause.

### 18.2 Weekly (Monday, 45 minutes)
- [ ] Fill weekly report (17.4) with lead quality from CRM.
- [ ] Rank ads by **CPQL** (not CPL).
- [ ] Kill bottom 20–30% of ads; promote winners from testing.
- [ ] Launch 3–5 new creatives in testing.
- [ ] Check frequency & CTR trends for fatigue.
- [ ] Sales review: why did lost leads not convert? Feed insights into new ads.

### 18.3 Monthly
- [ ] Upload new customer list & qualified-leads list → refresh Lookalikes.
- [ ] Breakdown analysis: age, region, placement. Exclude persistent losers only if data is significant.
- [ ] Review CAC & revenue vs spend → decide budget for next month.
- [ ] Plan next month's shoot (Section 12 shot list).
- [ ] Check Event Match Quality & CRM sync health.

### 18.4 Automated rules (Ads Manager → Rules)
| Rule | Condition | Action |
|---|---|---|
| Stop loser | Ad: spent > 3× target CPL AND leads = 0 (lifetime) | Turn off + notify |
| Stop expensive | Ad: CPL > 2× target over last 7 days AND spent > 3× target | Turn off + notify |
| Fatigue alert | Ad set: frequency > 4 (last 7 days, prospecting) | Notify |
| Budget protection | Campaign: daily spend > 1.5× planned | Notify |

### 18.5 Troubleshooting table

| Problem | Likely cause | Fix |
|---|---|---|
| Many leads, mostly junk/homeowners | Creative too consumer-like; "More volume" form; Audience Network on | B2B creative (warehouse/dispatch/BOQ), Higher intent form, "minimum order" line, exclude AN, conversion-leads optimization |
| Very few leads, high CPL | Too narrow audience, weak hook, form too long | Go broad, new hooks, remove 1–2 questions |
| Good leads but no sales | Slow follow-up, weak sales process, price mismatch | SLA, call script, sample kits, review pricing |
| Phone numbers not reachable | Fake/accidental leads | Higher intent + phone verification, completion message, call within 5 min |
| Performance dropped suddenly | Creative fatigue, budget jump, edits reset learning, competitor spend | New creatives, smaller budget steps, check auction (CPM) |
| "Learning limited" | Not enough events/week | Consolidate ad sets, increase budget, or optimize higher-funnel event |
| Ads rejected | Policy (claims, text, before/after) | See Section 20, edit claim, request review |

---

## 19. Scaling playbook

Only scale when **CPQL and CAC are profitable for 2+ weeks**.

1. **Vertical scaling:** +20% budget every 2–3 days on winning campaign while CPQL stays within target.
2. **Duplicate & jump:** duplicate the winning ad set at 2–3× budget; keep the original running. Kill whichever underperforms after 7 days.
3. **Horizontal scaling:**
   - New geographies (state by state, with matching delivery capability).
   - New personas (dealers, architects) with dedicated angles and forms.
   - New lookalike sources (Won customers, A leads, 95% video viewers).
4. **Creative scaling:** more variations of winning angles; new people on camera; regional languages (Hindi, Gujarati, Marathi, Tamil, etc.).
5. **Algorithmic scaling:** once CRM feedback is flowing, switch prospecting to **Conversion leads** optimization; test Meta's **Advantage+ leads / automated campaign** options if available in your account, with your best creatives.
6. **Cost control while scaling:** set a **cost per result goal** a little above your stable CPQL-equivalent CPL.
7. **Operational scaling:** before doubling ad spend, make sure the **sales team can handle 2× leads** within SLA. More leads + slow follow-up = wasted money.

---

## 20. Account safety & policy

- **Warm up new ad accounts:** start with modest budgets for the first 1–2 weeks; avoid huge sudden spends.
- **Don't change payment methods often;** keep a backup card on file.
- **Verified business + 2FA for all admins.**
- **Claims:** only use claims you can prove (test numbers, project counts). Avoid "No.1 in India", "100% unbreakable".
- **Avoid personal-attribute wording** like "Are you broke?"; business-type wording ("Fabricators:", "Builders:") is fine.
- **No misleading before/after or fake "price slash" countdowns.**
- **Images:** don't use other brands' logos or copyrighted images.
- **Comments moderation:** reply to every comment within hours; hide spam; move price questions to WhatsApp ("Bulk price shared on WhatsApp, please message us").
- **Landing pages/forms:** include business name, address, privacy policy link (required in lead forms; a simple privacy page on your website or a free policy page works).

---

## 21. Other channels

Meta works best when combined with these.

### 21.1 Google Search Ads (captures ready buyers)
- **Keywords (phrase/exact):** "window hardware manufacturer", "aluminium window fittings wholesale", "upvc window hardware supplier", "sliding window roller manufacturer", "door hardware distributor [city]", "[product] bulk supplier".
- **Negative keywords:** "price for one", "single", "DIY", "repair", "home depot"-type retail terms, "job", "salary", "free", "second hand", "amazon", "flipkart".
- Send to a **landing page** with a bulk-enquiry form + WhatsApp button; track with conversion tags; import offline conversions (Won) back into Google.
- **Google Business Profile** with products, posts and reviews.

### 21.2 LinkedIn (targets job titles)
- Organic posts from the founder's profile: dispatch, projects, tests, industry insights (3 per week).
- Connect + message: purchase managers, project heads at builders, architects, window system companies.
- LinkedIn ads only when budget allows (expensive, but precise for procurement heads).

### 21.3 B2B marketplaces
- IndiaMART / TradeIndia premium listings with full catalog; respond to buy-leads quickly.

### 21.4 Offline
- Trade exhibitions for doors/windows/fenestration (e.g., ZAK Doors & Windows Expo), builder association events (e.g., CREDAI chapter events), architect association meets.
- **Bring the event to Meta:** retarget event-area audiences; upload collected visiting-card contacts as a Custom Audience after the event.

### 21.5 Remarketing your existing customers (often the cheapest growth)
- Upload existing customers → run "new range / upgrade / referral" ads.
- **Referral program:** "Refer a fabricator/builder → [reward] after their first order."

---

## 22. 90-day roadmap

### Days 1–14: Foundation (spend ₹0–5,000)
- [ ] Business Portfolio, verification, 2 admins + 2FA, backup ad account
- [ ] Page + Instagram trust layer (Section 2.2), 12 posts
- [ ] WhatsApp Business (or API provider) with catalog, auto-replies, labels
- [ ] Pixel + CAPI (if website), domain verification
- [ ] CRM/Google Sheet with stages + scoring (Sections 15–16), real-time lead sync
- [ ] Sales assets (Section 2.3) + sample kits
- [ ] Shoot day #1 → 15–20 clips; edit 8–10 ads

### Days 15–45: Launch & learn (₹30,000–50,000)
- [ ] Campaign 1 (Prospecting Leads, Higher intent form) with 2 ad sets (Broad + Interest), 4–6 ads
- [ ] Campaign 3 (Testing): 2 new concepts/week
- [ ] Campaign 2 (Retargeting) once video viewers/engagers > ~1,000
- [ ] Daily SLA checks, weekly reports, kill/scale rules
- [ ] Collect first 2–3 testimonials and 1 case study

### Days 46–90: Optimize & scale (₹60,000–1,50,000/month)
- [ ] Lookalikes from customers + A leads
- [ ] CRM → Meta stage sync; test Conversion leads optimization
- [ ] ABM campaign for top 50 named accounts + outbound calls
- [ ] Dealer/distributor campaign for 1–2 new states
- [ ] Google Search Ads on high-intent keywords
- [ ] Shoot day #2 and #3; 3–5 new creatives every week
- [ ] Scale winners +20% every 2–3 days while CPQL holds

### Targets to aim for by day 90 (set your own after first month)
- CPQL stable and within your affordable range (Section 17.2)
- 25–40%+ of leads are A/B
- 5–10 new B2B accounts in trial/regular ordering
- Clear list of top 3 angles and top 5 creatives

---

## 23. Templates & checklists

### 23.1 Pre-launch checklist
- [ ] Ad account currency INR, timezone Asia/Kolkata
- [ ] Payment + backup card added
- [ ] Audience Network excluded
- [ ] Form: Higher intent, qualifying questions, privacy policy link, completion screen with WhatsApp
- [ ] Leads syncing to CRM/Sheet in real time; sales alert working (test with a test lead via Meta's Lead Ads Testing Tool)
- [ ] Naming convention applied
- [ ] UTMs / WhatsApp Ref codes set
- [ ] Each ad: 9:16 + 4:5 versions, captions, hook in 2 sec, one CTA
- [ ] Advantage+ creative enhancements reviewed (product-altering AI off)
- [ ] Exclusions: existing customers, recent leads, employees
- [ ] Sales team briefed: SLA + call script + catalog/profile ready to send

### 23.2 CRM / Google Sheet columns
```
Lead ID | Date-time | Source (Form/WA/Google/Event) | Campaign | Ad / Ref code |
Name | Company | Phone | City | Business type | Monthly requirement |
Need (price list/BOQ/sample/dealer) | Timeline | GST | Score | Grade (A/B/C) |
Assigned to | First contact time | Response time (min) | Stage |
Sample sent date | Quote value ₹ | Quote date | Won/Lost | Lost reason |
First order ₹ | Monthly potential ₹ | Next follow-up date | Notes
```
Stages: `New → Contacted → Qualified → Sample sent → Quote sent → Negotiation → Won / Lost / Nurture`

### 23.3 WhatsApp message templates

**Instant reply to new lead:**
> Hi [Name] 👋 Thank you for contacting SB Enterprise. [Sales person] will call you within 10 minutes.
> Meanwhile, here's our company profile & catalog: [link]
> For faster help, reply with your requirement (product + quantity + city).

**After call (A lead):**
> Great speaking with you, [Name]. As discussed:
> ✅ Sample kit dispatching today to [City]
> ✅ Quote for [project] by [date]
> Here's a short video of our warehouse & testing: [link]
> – [Your name], SB Enterprise, [phone]

**Follow-up (no reply):**
> Hi [Name], just checking: did you get a chance to look at our catalog? If you share your BOQ or monthly requirement, we'll send a best project rate within 24 hrs.

**Dealer enquiry:**
> Thank you for your interest in SB Enterprise distributorship for [City]. Please share: shop/firm name, years in business, current brands you sell, monthly turnover range, and GST no. Our team will call you to discuss margins & territory.

### 23.4 Monthly creative brief template
```
Month:
Winning angles last month (by CPQL):
Losing angles:
Top objections heard by sales (use as ad topics):
New products / offers:
Shoot list (10–20 clips):
Hooks to test (5):
Personas to target (fabricator / builder / dealer / architect):
Languages:
```

### 23.5 Glossary (quick reference)
| Term | Meaning |
|---|---|
| CBO / Advantage campaign budget | Budget set at campaign level; Meta distributes across ad sets |
| ABO | Budget set per ad set (used for testing) |
| Learning phase | Meta's first ~50 optimization events per ad set; results unstable |
| CAPI | Conversions API: server-side events to Meta |
| Conversion leads | Optimization using your CRM's lead stages (quality) |
| Lookalike | Audience similar to a source list (e.g., best customers) |
| CPQL | Cost per qualified lead |
| CAC | Customer acquisition cost |
| Hook rate | % of impressions that watched 3 sec |
| Frequency | Average times one person saw your ad |
| CTWA | Click-to-WhatsApp ads |
| ABM | Account-based marketing: targeting named companies |
| TOFU/MOFU/BOFU | Top / middle / bottom of funnel |

---

### Final word: the 5 things that will give SB Enterprise the most growth
1. **B2B-only creative** (scale, tests, dispatch, projects, founder) + **"bulk/project orders only"** messaging.
2. **Higher-intent lead forms with qualifying questions** + **lead scoring**.
3. **5-minute follow-up** + sample kits + structured follow-up for 30 days.
4. **Feeding quality data back to Meta** (customer & qualified-lead lookalikes → CRM conversion leads).
5. **3–5 new creatives every week**, judged on **cost per qualified lead and CAC**, not likes or CPL.

*Prepared for SB Enterprise. Update this playbook every quarter with your real numbers and learnings.*
