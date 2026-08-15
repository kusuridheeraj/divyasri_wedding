# Divya Sri weds Mohan Goud — 23 August 2026

Luxury cream-and-gold temple wedding invitation. Cinematic temple-door loader, hand-illustrated section backgrounds, live countdown, WhatsApp RSVP, and sacred typography.

---

## 📂 Folder structure

Your repo looks like this:

```
divyasri_wedding/
├── index.html
├── README.md
├── background-music.mp3
├── images/
│   ├── door.png             ← the loader temple doors
│   ├── bg-hero.png          ← hero background (lamps + tilak)
│   ├── bg-invocation.png    ← Ganesha section background
│   ├── bg-invitation.png    ← invitation card background
│   ├── bg-muhurtham.png     ← muhurtham section background
│   └── bg-couple.png        ← bride & groom section background
```

**Keep the images folder exactly as named** — the HTML references these specific filenames.

---

## 🚀 Deploy on GitHub Pages (step by step)

1. Push your repository to GitHub (`https://github.com/kusuridheeraj/divyasri_wedding`).
2. Go to **Settings → Pages** in your repository.
3. Under **Branch**, select `main` and folder `/(root)`.
4. Click **Save**.
5. Wait ~1 minute, refresh — your live URL appears at the top:
   `https://kusuridheeraj.github.io/divyasri_wedding/`

Paste that URL into WhatsApp — the preview card uses the hero image and invitation details automatically.

---

## ✏️ Customizing details

Open `index.html` in any editor (VS Code, Notepad, or GitHub web editor).

### Couple photos (Optional)
Find the "Meet the Bride & Groom" section, look for `<!-- Replace with: ... -->` comments. Upload `divya.jpg` and `mohan.jpg` into your `images/` folder, then change:
```html
<div class="portrait-inner">D</div>
```
to:
```html
<div class="portrait-inner"><img src="images/divya.jpg" alt="Divya Sri"></div>
```
(Same for Mohan Goud, with `images/mohan.jpg`.)

### Wedding date for the live countdown
Near the bottom of the file in `<script>`, find:
```js
const WEDDING_DATE = new Date('2026-08-23T11:29:00+05:30').getTime();
```
This is set to **Sunday, 23 August 2026, 11:29 AM IST**.

### WhatsApp RSVP number
Currently configured for `+91 90142 67074` (`919014267074`). If you want to update it in the future, search for `919014267074` in `index.html`.

### Background music
The audio toggle plays background music on user interaction. To replace it:
1. Upload your preferred MP3 file to the repository.
2. Update the `<audio id="bgAudio">` source in `index.html`.

---

## 🎨 What's included

- **Temple-door loader** — sacred temple doors split and slide open on tap/click
- **Cream & gold temple aesthetic** — matching traditional auspicious colors
- **Sacred Telugu / Sanskrit invocations** — *Srirasthu ! | Shubamasthu !! | Avignamasthu !!!*
- **Sumuhurtham Card** — Sunday, 23ʳᵈ August 2026 at 11:29 AM, Mula Nakshatram, Thula Lagnam at Aditya Convention A/c, Mamnoor, Warangal
- **Live countdown** — auto-updates to 23 August 2026, 11:29 AM IST
- **WhatsApp + Call RSVP** — integrated with +91 90142 67074
- **Floating petals** — pink lotus, marigold, and jasmine mix
- **Single-page Print / PDF card** — clean printable invitation card
- **Open Graph preview** — customized WhatsApp share card preview

---

✦ With love · 23 August 2026 · #DIVYAWEDSMOHAN · #MOHANWEDSDIVYA ✦
