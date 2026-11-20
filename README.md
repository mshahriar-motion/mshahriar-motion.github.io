# Muhammad Shahriar — Portfolio Website

A static portfolio website built from the original Figma design. The design
itself is preserved exactly; this build adds YouTube links on the design's
own portfolio cards, working social buttons, Calendly booking, and motion
(floating rocks, twinkling stars, scroll reveals, parallax, hover effects).

**100% free hosting on GitHub Pages. No backend, no paid services.**

## What's inside

```
index.html          The whole site (design + links + animations)
assets/
  favicon.png       Site icon (logo from the design)
.nojekyll           Tells GitHub Pages not to run Jekyll
```

## Publish it free on GitHub Pages (about 5 minutes)

### 1. Create a GitHub account (free)
Go to https://github.com/signup if you don't have one.

### 2. Create a new repository
- Click **+** (top right) → **New repository**.
- Name it anything, e.g. `shahriar-portfolio`.
- Set it to **Public**.
- Click **Create repository**. Do not add a README from GitHub — you already have one here.

### 3. Upload these files
- On the new repository page, click **uploading an existing file**.
- Drag in `index.html`, the `assets` folder and `.nojekyll` (keep the same
  folder structure: the `assets` folder stays next to `index.html`).
- Click **Commit changes**.

### 4. Turn on GitHub Pages
- Go to **Settings** → **Pages** (left sidebar).
- Under **Build and deployment → Source**, choose **Deploy from a branch**.
- Branch: **main**, folder: **/(root)**. Click **Save**.

### 5. Open your site
After about a minute, the same Settings → Pages screen shows your link:

```
https://<your-username>.github.io/shahriar-portfolio/
```

That's your live portfolio. Share that link anywhere.

### Updating the site later
Edit `index.html`, then upload the changed file again to the same
repository — Pages redeploys automatically in about a minute. To change a
video, edit its `href` in the `hs-card` links of `index.html`.

## Links wired into the site

| Element | Destination |
|---|---|
| Portfolio cards (5, as designed) | 5 of your YouTube videos — see the note below |
| Book a Call / Start a Project | Calendly — https://calendly.com/shahriar-motion/30min |
| Watch Me | YouTube channel — https://www.youtube.com/@shahriar.motion |
| Facebook | https://www.facebook.com/profile.php?id=61587471650883 |
| Instagram | https://www.instagram.com/designer_shahriar/ |
| LinkedIn | https://www.linkedin.com/in/mshahriarmotion/ |
| Footer 4th icon (labelled LinkedIn in the design) | YouTube channel (see note below) |
| Phone number | `tel:+88017087793` (taps to call) |
| WhatsApp icon | https://wa.me/88017087793 (opens a chat) |
| Menu: Home / Services / Portfolio / About / Process | Scrolls to that section of the page |

**Note on the portfolio cards:** the design has 5 cards and you gave 7
videos, so 5 are linked — Podcast Trailer → https://youtu.be/uQ5JMs8uYBE,
Reels → https://youtu.be/NVHV6aM4kc4, UGC → https://youtu.be/PAaLvCDLS44,
Ads → https://youtu.be/59nOxzsfgxY, SaaS Explainer →
https://youtube.com/shorts/E4sVoj9PmL0. These 2 Shorts are not linked
anywhere yet: https://youtube.com/shorts/ruAXebVQ9cM (Quranly) and
https://youtube.com/shorts/s9hie1W8oYU (Animated Reels). Either one can be
swapped in for any card on request.

**Note on the 4th footer icon:** the design labels it "LinkedIn" a second
time. It is linked to your YouTube channel so no icon is dead; if you'd
rather it pointed somewhere else (X, Behance, etc.), say the word and it
takes one edit.

## Notes

- **Design preserved.** The SVG artwork is your Figma export, unchanged
  except for smaller embedded images (see below) and CSS classes used only
  for animation. Layout, colours, type and spacing are as designed.
- **Portfolio row.** The design's own 5 portfolio cards are kept exactly as
  drawn — same size, same labels, same timeline, same playhead. Each card's
  white body now shows its video: the real YouTube thumbnail with a red
  play button in the middle, like a video player. Click a card (or its play
  button) and the video opens in a new tab. No BEFORE/AFTER labels or extra
  text were added.
- **Images optimised for fast loading.** The huge 4096px team photo
  (6 MB, shown at 139px) was resized to 1024px; the About and team photos
  are kept at full resolution for a sharp, HD look. The site is now roughly
  2.6 MB instead of 13 MB.
- **No speech/captions gap:** none — this is a static site, no audio.
- **Mobile.** Everything scales with the design; the portfolio cards stay
  tappable on phones.
- **Motion.** Rocks float gently, stars twinkle on different timings,
  buttons fade in on scroll, rocks drift (parallax) as you scroll.
  All motion turns off automatically if a visitor prefers reduced motion.
  The portfolio section and the About section stay as designed — no
  entrance animation, no twinkle, no moving playhead. The only motion in
  the portfolio section is Zakaria-style: while you hover a card, a white
  "Watch Now!" pill follows your cursor (the cards themselves never move).
  A floating pill nav also appears once you scroll past the design's own
  menu. Photos are kept at full resolution, so everything stays sharp.
