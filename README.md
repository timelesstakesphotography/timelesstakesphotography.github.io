# Timeless Takes website

A one-page static site: plain HTML and CSS, no build step, no monthly fees.

## Files
- `index.html` is the whole site.
- `styles.css` holds the design.
- `assets/` has the logo (ink and light versions, transparent background) and the favicon.
- `images/` is where your photos go (see below).

## 1. Add your photos
Drop JPEGs into `images/` with these exact names. Any slot without a photo shows a labelled placeholder, so you can add them one at a time.

| File | Shape | Where |
|---|---|---|
| `hero-1.jpg` | tall 2:3 | main hero image |
| `hero-2.jpg` | 4:5 | small hero image |
| `work-*.jpg` | tall 2:3 | Selected work, three across (order is set in `index.html`) |
| `about.jpg` | 4:5 | About section |
| `og-image.jpg` | 1200x630 | the picture shown when the link is shared |

Export from Lightroom at about 2000px on the long edge, quality 75 to 80, so each file stays under ~500 KB. Change the captions in `index.html` if the pictures differ.

## 2. Pic-Time link
Already set to https://timelesstakes.pic-time.com.

## 3. Enquiry form (free)
Connected to Web3Forms, delivering to timelesstakesphotography0@gmail.com. Once the site is live, update the form's website URL in the Web3Forms dashboard from localhost to the real address, then send one test enquiry.

The free plan covers 250 submissions a month. Each enquiry arrives as an email with the date, venue, wedding type, guest numbers and muhurtham time already filled in.

## 4. Put it online (free)
Any of these works and costs nothing:

- **Netlify Drop** (easiest, no account setup beyond sign-in): go to app.netlify.com/drop and drag the whole `website` folder in. You get an address like `timelesstakes.netlify.app`.
- **GitHub Pages**: create a public repository, upload these files, then Settings → Pages → deploy from the `main` branch. Address: `yourname.github.io/repo-name`.
- **Cloudflare Pages**: create a project, upload the folder, address like `timelesstakes.pages.dev`.

## The one thing that costs money
A custom domain such as `timelesstakes.co.uk` is optional and costs roughly £5 to £15 a year from Cloudflare, Porkbun or Namecheap. All three hosts above let you connect it later for free, with free HTTPS.

## Fonts
Bodoni Moda and Jost, both from Google Fonts under the SIL Open Font License, so commercial use is allowed.
