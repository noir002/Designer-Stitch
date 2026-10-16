# Designer Stitch — Final Prototype

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` from this directory and open http://localhost:8000.

## Features
- Responsive editorial storefront with Home, T-shirts, Hoodies, Designs, Size Guide, and Customize pages.
- Interactive 3D/perspective hero slider. Use arrows or swipe/drag on touch or pointer devices.
- Existing generated campaign images plus enhanced/cropped versions of the supplied reference images (including the latest 14 uploads).
- Product cards route to category pages and can preselect garments in the configurator.
- Colour, fabric, GSM, fit, size, pattern, decoration, placement, artwork filename, quantity, and illustrative price estimate.
- Downloadable custom order brief.

## Notes
The generated imagery is newly created visual inspiration; the user-provided screenshots are cropped, contrast/sharpness/color enhanced, and included as additional references. Because source images were screenshots, crop/cleanup cannot recover pixels hidden by UI overlays or improve their resolution beyond the original. Replace with original high-resolution source artwork/product photos for production.
Prices and size chart are placeholders. No backend, live upload, order submission, payments, or stock management is connected.


## New image collection
The latest 14 uploaded screenshot references are included as cleaned JPG assets in `assets/`. Cropping removes outer edges and visible overlays where possible; image contrast, colour, and sharpness are enhanced. Since the originals are screenshots, this cannot restore details obscured by overlays or substitute for original high-resolution product photography.

## Responsive layout update
- Desktop retains the wide editorial layout and perspective 3D lookbook slider.
- Tablet navigation collapses into a touch-friendly menu before the links become cramped.
- Mobile uses a vertically art-directed hero, swipeable 3D slider, two-column product cards, compact fabric and palette cards, a stacked customizer, horizontally scrollable size chart, and a fixed five-item quick-navigation dock.
- Added reduced-motion support, focus-visible outlines, lazy loading for non-hero images, and high-priority loading for the hero gallery.
- The 14 recently supplied screenshot images have been enhanced, denoised, sharpened, and upscaled for clearer retina/mobile display while retaining the original artwork and garment details.


## Editorial dark-theme refresh
- Reworked the existing prototype into a high-contrast black/white streetwear editorial theme with restrained red accents, inspired by the supplied reference boards.
- Retained the existing multi-page prototype, product categories, 3D-style draggable/swipeable lookbook, garment customizer, fabric/GSM/colour options, size guide, and mobile navigation.
- Refined the supplied garment and campaign assets with high-quality upscaling, subtle tonal correction, and edge sharpening. Cropped obvious frame/overlay margins on selected fabric/detail images where safe.
- Responsive layouts are tuned for desktop, tablet, and mobile rather than simply shrinking the desktop view.
- This is still a frontend prototype; checkout and order submission are not connected to a backend.


## Premium light-theme refresh (October 2026)
- Switched the interface to a minimalist light palette with warm off-white surfaces, fine borders, restrained red accents and softer shadows.
- Rebuilt the lookbook slider styling as floating glassmorphic cards with deeper 3D perspective, polished shadows and smoother transitions while preserving swipe/drag and arrow controls.
- Added 18 user-supplied garment/artwork references as enhanced WebP assets. Each was upscaled with Lanczos resampling and gently sharpened/tonally balanced without changing the original design.
- Added a responsive studio archive gallery with an image lightbox, plus a dedicated homepage colour availability palette that feeds into the existing customizer.
- The existing separate Colour Lab page and garment customizer remain available. Images are local assets and the website does not require external image hosting.

## AI-generated HD visual refresh
- Replaced the earlier enhanced-but-still-soft source photos in the 18-image gallery with high-definition, AI-generated concept visuals inspired by the supplied streetwear artwork.
- Added a bold editorial spotlight panel and expanded the desktop gallery to a more premium four-column image layout, with responsive tablet/mobile breakpoints.
- These visuals are concept imagery generated from the inspiration boards, not exact reproductions of physical products; confirm final prints and garments against real production samples.
