# Zara Handmade — Afghan Heritage, Handcrafted

A responsive, single-page storefront concept for Zara Handmade. It showcases five categories inspired by Afghan craft traditions: Shawls, Hats, Scarves, Accessories, and Carpets.

## Run locally
1. Extract the ZIP folder.
2. Open `index.html` in a modern browser.
3. No build step or package installation is required.

The site uses HTML, CSS, and vanilla JavaScript. Product images and the favicon are stored locally in this project. Google Fonts are optional enhancements; if offline, the browser falls back to system fonts.

## Features
- Five category cards and a filterable product collection.
- Product detail dialog.
- Shopping bag with quantity controls, remove buttons, subtotal, and `localStorage` persistence.
- Dark/light theme preference saved in `localStorage`.
- Welcome dialog shown once per browser tab session.
- Responsive mobile navigation and accessible labels.
- Contact form field validation.

## Important demo limitations
This is a front-end portfolio/demo storefront. It does **not** process real payments or send contact-form messages. To accept real orders, connect a trusted payment provider and backend. To deliver contact messages, connect a backend or email form service. The product names and prices are sample content and should be reviewed before a real launch.

## Publish through GitHub and Netlify
1. Create a GitHub repository and upload the contents of this folder (upload `index.html`, `favicon.png`, `favicon.ico`, `assets/`, and `images/` at the repository root).
2. In Netlify, choose **Add new site → Import an existing project** and connect that repository.
3. Set the base directory to the repository root. Leave the build command blank and the publish directory as `.` (the root).
4. Deploy. Every image path is relative, so keep the folder structure intact.

You can also drag the extracted `Zara-Handmade` folder into Netlify's manual deploy area.

## Project structure
```text
Zara-Handmade/
├── index.html
├── README.md
├── favicon.png
├── favicon.ico
├── assets/
│   └── floral-ornament.svg
└── images/
    ├── accessories/
    ├── carpets/
    ├── hats/
    ├── scarves/
    └── shawls/
```

## Image and design notes
The textile and craft visuals in this project were generated specifically as illustrative product imagery for this website concept. They should not be represented as verified photographs of specific Afghan artisans or individual products.
