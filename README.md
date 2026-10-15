# Pet Care Website

A simple 10-page website about pet care, built with plain HTML, CSS and JavaScript.
No frameworks and no installation needed.

## Pages

| File | Page |
|------|------|
| index.html | Home |
| about.html | About |
| dogs.html | Dog care |
| cats.html | Cat care |
| birds.html | Birds and small pets |
| nutrition.html | Pet food guide |
| grooming.html | Grooming tips |
| health.html | Health and FAQs |
| gallery.html | Photo gallery |
| contact.html | Contact form |

## Folder structure

```
site/
|-- index.html (and the 9 other pages)
|-- README.md
|-- css/
|   `-- style.css      all colors, layout and animations
|-- js/
|   `-- main.js        menu, FAQ, gallery popup, scroll effects
`-- images/
    |-- hero.jpg       your photo for the home page circle (add this)
    `-- hero.svg       temporary picture, shown if hero.jpg is missing
```

Keep this structure the same. If you move a folder, the pages will lose their style.

## How to run

1. Extract the zip file.
2. Open `index.html` in any browser (Chrome, Edge, Firefox).

## Features

- 10 pages with a shared menu and footer
- Mobile friendly menu (the button appears on small screens)
- Animations: floating hero image, scroll reveal, hover effects
- Clickable 3D-style buttons
- FAQ accordion, photo gallery popup, back-to-top button
- Contact form (shows a thank-you message, it does not send real email)

## How to change things

- **Colors:** open `css/style.css` and edit the values at the top, under `:root`.
- **Hero photo:** put a picture named `hero.jpg` inside the `images` folder.
- **Text:** open the page you want in a text editor and change the words between the tags.
- **Name:** search for "Pet Care" in all HTML files and replace it.
- **Contact details:** edit the email, phone and address in `contact.html`.

## Using your own images (recommended)

Some pages load photos from the internet (`loremflickr.com`). These are random and can fail to load.
For a reliable site:

1. Save your photos inside the `images` folder, for example `images/dog1.jpg`.
2. In the HTML file, change the image link:
   `src="https://loremflickr.com/700/500/dog?lock=0"`
   to
   `src="images/dog1.jpg"`

Use lowercase file names without spaces, for example `dog1.jpg`, not `Dog 1.JPG`.



## Credits

Fonts: Fredoka and Nunito (Google Fonts).
Placeholder photos: loremflickr.com.
MADE BY MUHAMMAD KHIZAR HAFEEZ
