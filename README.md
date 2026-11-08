# RePhone - Second-Hand Smartphone Marketplace

A beginner-friendly 3-page website made with **HTML5 and CSS3 only** (no JavaScript).
It is a **frontend demo**: nothing is stored, sent or published.

## Folder structure
```
RePhone/
├── index.html   Home, with the About Us and Contact Us sections
├── phones.html  Explore Phones (sample listings)
├── sell.html    Sell Your Phone (demo form)
├── style.css    One stylesheet shared by all pages
├── images/      logo.png, hero-phone.jpg, phone1.jpg ... phone6.jpg
└── README.md
```

## How to run
Unzip the folder and double-click `index.html`. No installation or server is needed.

## How to edit
- **Add or change a phone:** copy one `<article class="card">...</article>` block in `phones.html`, then change the text and the image file name.
- **Change colours:** edit the variables inside `:root { ... }` at the top of `style.css`.
- **Use real photos:** put your own images in `images/` with the same file names, or update the `src` in the HTML.
- **Contact details:** the email addresses and phone numbers are samples. Search for `example` and `98765` and replace them.
- **Navigation and footer:** the same blocks are repeated on all 3 pages, so change them in each file.
- **Yellow sticker on the home page:** its text ("Pre-owned from") is sample text in `index.html`.

## Notes
- `sell.html` is a demo. After you click Submit, the page reloads and shows a thank-you box using the CSS `:target` selector. The form uses the GET method, so typed values appear in the address bar. Do not enter real personal details if you put the site online.
- The images are simple generated placeholders.
- Fonts load from Google Fonts when you are online. Offline, the browser uses system fonts.
