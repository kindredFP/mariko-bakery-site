# KO-BO BAKEHOUSE — mariko-bakery-site

Small-batch sourdough home bakery in Mississauga. Focaccia and baked goods, made to order with homemade sourdough and simple ingredients.

Live site: https://palattao.net/mariko-bakery-site/

## Files

```
mariko-bakery-site/
  index.html
  README.md
  images/
    hero-focaccia.jpg
    baker-dough.jpg
    focaccia.jpg
    sourdough.jpg
    sweet-bake.jpg
```

`index.html` is a single self-contained page. All styling and scripts are inline, no build step needed.

## Photos

Photos live in `images/` next to `index.html`. Use these exact filenames, all lowercase:

- `hero-focaccia.jpg` — hero, 4/5, about 1200px wide
- `baker-dough.jpg` — about section, 1/1, about 1000px wide
- `focaccia.jpg` — menu card, 4/3, about 800px wide
- `sourdough.jpg` — menu card, 4/3, about 800px wide
- `sweet-bake.jpg` — menu card, 4/3, about 800px wide

Keep each photo under about 300 KB if you can. JPG is fine.

If a photo is missing, the warm placeholder box shows instead of a blank or broken image. When the photo is added with the right name, it covers the placeholder automatically.

## Preview locally

Open `index.html` in a browser, or from the site folder run:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## Ordering rules

- Made to order only.
- Orders are prepared after payment is confirmed.
- Submit at least 3 days before the requested pickup date.
- Pickup near Winston Churchill and Battleford Road, Mississauga, Ontario.

The Order buttons open an email to mariko.andris@gmail.com with Bake, Quantity, Pickup date, Name, and Phone pre-filled.

## Contact

- Email: mariko.andris@gmail.com
- Instagram: @kobo.bakehouse

## Deploy

Upload `index.html` and the whole `images/` folder to the host, keeping the same structure. Use relative paths only, no absolute Mac paths.

## Still to confirm with Mariko

- Final menu items, flavours, sizes, and prices
- Real photos for all 5 slots
- Pickup days and hours, payment method, allergens
