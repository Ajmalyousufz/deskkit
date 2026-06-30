# DeskKit — 90-Day Build Plan

Niche: **desk & study setup gear for Indian students, developers and WFH workers**
(laptop stands → keyboards/mice → desk lighting → cable organization → webcams/audio → power banks)

Why this niche for you specifically:
- You ARE the audience. You don't need to fake expertise on a desk setup for coding/studying.
- It avoids face-on-camera content, which matches not wanting to do heavy personal-brand marketing.
- It uses your actual dev skill (this whole site is proof you can ship it yourself instead of paying for a "no-code" course).
- **Edge most competitors don't have:** almost all Amazon affiliate sites in this niche are English-only and brutally competitive. A Malayalam version of each review (e.g. "മികച്ച ലാപ്ടോപ്പ് സ്റ്റാന്റ്") targets searches with far less competition. Add Malayalam content once the English version is live — don't do both from day one.

---

## 0. Before writing anything

1. Log in to [affiliate.amazon.in](https://affiliate.amazon.in) (not .com).
2. Install the **SiteStripe** browser toolbar (shows up automatically once logged in to Amazon while browsing). It puts a "Get Link" button on every product page — this is the fast way to grab links, no manual searching in the dashboard.
3. Remember the rule: your account needs **3 qualifying sales within 180 days** of signup or it gets closed. Don't sit on this for months — get the first review live within week 1.

## 1. Deploy the site (free, ~20 minutes)

You already know git, so use **GitHub Pages** — free hosting, no server cost:

```bash
# inside the deskkit folder
git init
git add .
git commit -m "Initial DeskKit site"
gh repo create deskkit --public --source=. --push
# then in GitHub: Settings → Pages → Deploy from branch → main → / (root)
```

Your site will be live at `https://<your-username>.github.io/deskkit/`.
Later, once there's some traffic, a real domain (~₹600–800/year from a registrar) is a cheap upgrade — not needed on day one.

## 2. Replace the sample content

In `reviews/best-laptop-stands.html`:
- Pick 5 **real** laptop stands that actually rank on Amazon.in for "laptop stand" — check Amazon's own bestseller list in the category, don't guess.
- Replace every `[Replace with real product]` / `₹[xxx]` / `#REPLACE_WITH_AMAZON_AFFILIATE_LINK` with the real name, real price range, and the real SiteStripe link.
- Write the pros/cons from things you can actually verify (product description, real reviews, specs) — don't invent test results you didn't run.

In `about.html`: replace the bracketed placeholder lines with your own one-paragraph story and a real contact email.

## 3. Content calendar — one category at a time

Don't open all six categories at once — that's the same "jump to the next shiny thing" pattern. Finish category 1 fully (5 products + the page live) before starting category 2.

| Week | Task |
|---|---|
| 1 | Finish & publish "Best Laptop Stands" with real products and links |
| 2 | Write the Malayalam version of the same review |
| 3 | Publish "Best Budget Mechanical Keyboards for Coding" (English) |
| 4 | Malayalam version of keyboards review |
| 5 | "Best Monitor Light Bars for Night Coding" |
| 6 | Malayalam version |
| 7 | "Best Webcams Under ₹1500 for Online Classes" |
| 8 | Malayalam version |
| 9 | "Best Cable Organizers for a Clean Desk Setup" |
| 10 | Malayalam version |
| 11 | "Best Power Banks for a Full Day of WFH" |
| 12 | Malayalam version + go back and update week 1–2 post if prices/links changed |

That's it — 12 weeks, 6 categories, 12 pages. Don't add a 7th category until these are live and you've started step 4 below.

## 4. SEO basics (do this for every page, takes 5 minutes each)

- Unique `<title>` and `<meta description>` per page (already templated in the HTML — just edit the text).
- One clear `<h1>` per page matching the actual search phrase people type (e.g. "Best Laptop Stands for Students in India").
- Internal links between related reviews once you have more than one.
- Submit the site to **Google Search Console** (free) the day it's live — this is what gets you indexed, not waiting around.

## 5. Distribution that doesn't need "marketing personality"

These are text-based, low-exposure, and fit working quietly rather than performing:

- **Reddit**: r/developersindia, r/Kerala, r/india — answer real questions where a review genuinely helps (not spam, one honest mention with the link when relevant).
- **Quora**: answer "best laptop stand for students in India" style questions with a genuine answer + link.
- **Pinterest**: pin a simple graphic per review — visual, not verbal.
- **Telegram**: Kerala tech / engineering student groups, if you're already in any — share when genuinely relevant, not as a broadcast ad.
- **Organic search** is the real long-term channel. Everything above is just to get the first sales while Google indexes you.

## 6. Track it

- Amazon Associates dashboard → clicks, conversions, earnings (updates with a delay, don't check it 5 times a day).
- Google Search Console → which queries bring people to the site.
- Payment timing: earnings from a given month land roughly 60 days later. Don't read "no money yet" in week 3 as failure — that's expected.

## 7. Realistic milestones (read this when it feels slow)

- **Weeks 1–4**: Site live, 1–2 reviews up, zero or near-zero sales. Normal.
- **Month 2**: First few clicks turning into the 3 sales you need to keep the account active.
- **Month 3+**: If content is consistent, organic search traffic starts compounding. This is where most people who quit, quit — right before it starts working.

## 8. Money discipline while this builds

- Don't buy the ₹1,799 or ₹3,999 courses right now. You already have the actual skill (you're building this site yourself) that those courses sell to people who can't code.
- Park the bike purchase. Revisit it once you've seen 3 consecutive months of *growing* affiliate income — not before.
- If in 90 days you've shipped all 6 categories, distributed consistently, and still see nothing — that's useful data too, and worth a honest look at whether this niche or this channel is the bottleneck, before switching to a new one.
