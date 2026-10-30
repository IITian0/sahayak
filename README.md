# Sahayak

**A caregiving network for India's elderly.** Built by **Gaurav Kumar**, Team Aasra, MNIT Jaipur, for **SPHINX'26 · Minute To Pitch It**.

Most products centre the person being cared for. Sahayak centres the person *doing* the caring — because that is where the load actually falls.

## Live

| | |
|---|---|
| Website | https://iitian0.github.io/sahayak/ |
| App (PWA) | https://iitian0.github.io/sahayak/app.html |

Both install as a Progressive Web App: on Android/desktop Chrome tap **Install**, on iPhone use **Share → Add to Home Screen**. It runs full screen and works offline after the first load.

## What the prototype does

- Onboarding, then a five-tab app: **Today · Care plan · Circle · Respite · Family**
- Tick care steps — the progress ring updates
- Post in the caregiver circle — a reply comes back
- Pick a time slot and book a verified helper
- Send the day's note to a family member
- **English / हिंदी** toggle that actually switches the interface
- Profile with the elder's record and the current plan

Everything runs in the browser with no backend; state is held in memory. This is a front-end prototype for the pitch.

## Files

```
index.html              marketing site + install section
app.html                the working app prototype
manifest.webmanifest    PWA manifest
sw.js                   service worker (offline app shell)
icon-192.png            app icon
icon-512.png            app icon
```

## Run locally

Open `index.html` in any browser. No build step, no dependencies. The service worker needs `http://` or `https://` — for a local test, run `python3 -m http.server` in this folder.

## The numbers

| | |
|---|---|
| Indians aged 60 and above | 10.4 crore |
| Living with dementia | 88 lakh |
| Getting any diagnosis or care | 1 in 10 |
| Sahayak, per month | ₹199 |
| Urban home care today | ₹15,000–75,000 / month |

Sources: Government of India, 2024 · The Lancet, 2024 · Business Standard, 2024.

## The ask

Mentorship and one hospital pilot, to reach 100 families across two cities by March 2027.

---

*Sahayak — har caregiver ke paas ek aasra.*

---

© 2026 **Gaurav Kumar** · Team Aasra, MNIT Jaipur. All rights reserved. See [LICENSE](LICENSE).

The name, logo, design and code in this repository may not be copied, reused or resubmitted without written permission.
