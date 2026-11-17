# Mongolian Food Composition Database - SPA (2.6-2.9 туршилт)

Хүнсний найрлагын мэдээллийн сангаар Single Page Application бүтээх төслийн 2-р бүлгийн 2.6-2.9 жишээний туршилт.

- 2.6 Services / data layer (`config.js`, `nutritionService.js`)
- 2.7 Хайлт, шүүлт (sidebar, food group, nutrition checkbox)
- 2.8 Дээжийн зураг (`images.json` build script, image modal)
- 2.9 Хэл солих (`nutritionsEnMn.json`, i18n)

## Ажиллуулах
```
npm install
npm run build:css
npm run generate:images
npm run convert:data
npm run serve      # http://localhost:8080
```
`src/data/nutritions.json` дахь 12 бичлэгийн 11 нь туршилтын (demo) өгөгдөл, `src/img/foods/` дахь зургууд нь SAMPLE зураг.
