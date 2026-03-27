# MakeoverBy Priya Shetty — Link in Bio Landing Page

A mobile-first, single-page HTML/CSS landing page for the Instagram account **@makeoverby_priya_shetty**.

## Tech Stack

| Layer         | Technology                            |
|---------------|---------------------------------------|
| Structure     | HTML5 (single file)                   |
| Styling       | CSS3 with CSS Variables               |
| Interactivity | Vanilla JavaScript (inline)           |
| Fonts         | Google Fonts — Playfair Display + Poppins |
| Icons         | Font Awesome 6 (CDN)                  |

## Before Going Live — Replace Placeholders

Open `index.html` and find-and-replace each placeholder with your real value:

| Placeholder               | Replace With                                                      |
|---------------------------|-------------------------------------------------------------------|
| `YOUR_GOOGLE_FORM_URL`    | Your Google Form booking link (e.g. `https://forms.gle/...`)     |
| `YOUR_PORTFOLIO_URL`      | Instagram Guides link or Google Drive gallery URL                 |
| `YOUR_PHONE_NUMBER`       | Country code + number, no spaces (e.g. `919876543210`)            |
| `YOUR_PROFILE_PHOTO_URL`  | Direct URL to profile photo (upload to GitHub repo)               |
| `YOUR_INSTAGRAM_URL`      | `https://www.instagram.com/makeoverby_priya_shetty`               |
| `YOUR_TESTIMONIAL_TEXT`   | A real client quote                                               |
| `YOUR_CLIENT_NAME`        | Client first name + area (e.g. `Divya, Indiranagar`)              |
| `YOUR_PAGE_TITLE`         | `MakeoverBy Priya Shetty | Makeup Artist Bengaluru`              |

## Deployment — GitHub Pages

1. Create a free account at [github.com](https://github.com) if you don't have one.
2. Click **+** → **New repository**. Name it `makeoverby-priya`. Set to **Public**.
3. Upload `index.html` to the repository (drag and drop or use `git push`).
4. Go to **Settings → Pages → Source**: select `main` branch → folder: `/ (root)` → **Save**.
5. Your page is live at: `https://yourusername.github.io/makeoverby-priya/`
6. Update your Instagram bio link with this URL.

### Custom Domain (Optional)

Buy a domain like `priyashetty.in` (~₹800/year) and point it to GitHub Pages via CNAME settings.

## Deployment — Netlify (Alternative)

1. Go to [netlify.com](https://www.netlify.com) → Sign up for free.
2. Drag and drop `index.html` onto the Netlify dashboard.
3. Netlify gives you a URL like `makeoverby-priya.netlify.app`.
4. Rename the URL for free in Netlify settings.

## Updating After First Deploy

- **GitHub Pages:** Edit `index.html` → commit & push → page updates in ~1 minute.
- **Netlify:** Drag and drop the updated `index.html` → live instantly.

## Go-Live Checklist

- [ ] All `YOUR_...` placeholders replaced with real values
- [ ] Opened page on mobile Chrome — all 3 buttons work
- [ ] "Book Your Appointment" opens the Google Form correctly
- [ ] "Chat on WhatsApp" opens WhatsApp with the correct number
- [ ] "View Portfolio" link opens correctly
- [ ] Profile photo loads correctly (not broken)
- [ ] Page looks correct on desktop (card layout centred)
- [ ] Page title shows "MakeoverBy Priya Shetty | ..." in browser tab
- [ ] HTTPS is enabled (padlock icon in browser)
- [ ] Instagram bio link updated to the live URL
- [ ] Tested by clicking the Instagram bio link from a real phone
- [ ] Google Form receives a test submission

## Future Enhancements (Phase 2)

- **Analytics:** Add Google Analytics 4 to track button clicks
- **UTM Parameters:** Append `?utm_source=instagram` to the Google Form URL
- **Gallery Section:** Embed a photo grid via Instagram Basic Display API
- **Booking Count:** JavaScript counter for social proof
- **Dark Mode:** CSS `prefers-color-scheme` + JS toggle
- **PWA:** Add `manifest.json` + service worker for "Add to Home Screen"

---

*Built by [Dhrithi Digital](https://www.dhritidigital.com) • March 2026*
