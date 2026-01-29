<div align="center">
<h2>Svelte Commerce</h2>
</div>

<div align="center">

**The open-source frontend for any eCommerce. Built with a headless approach, using a modern JS stack. We have WIP for MedusaJS, Shopify. The API approach also allows you to merge Svelte Commerce with any third-party tool like payment gateways, POS or AI.**

</div>

<div align="center">
  <br>
    <img width="400" src=".github/svelte-commerce.gif" >
    <img width="400" src=".github/svelte-commerce-demo.gif" hspace="5">
</div>

<br>
<p align="center">
<img height="400" src=".github/home-page-mobile.jpg" hspace="10">
<img height="400" src=".github/catalog-listing-mobile.jpg" hspace="10">
<img height="400" src=".github/product-details-mobile.jpg" hspace="10">
</p>

<br/>
<h2 align="center"> Premium themes made using svelte-commerce </h2>
<p align="center">
<img height="200" src=".github/moisny.jpg" hspace="10">
<img height="200" src=".github/jws.jpg" hspace="10">
<br>
<br>
<img height="200" src=".github/varni.jpg" hspace="10">
<img height="200" src=".github/suffolk.jpg" hspace="10">
</p>

<br/>
<p align="center">
  <img src="https://img.shields.io/badge/Made_With-Svelte-red.svg?style=for-the-badge" alt="Made with Svelte"><br/><br/>
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-blueviolet?style=for-the-badge" alt="Maintained">
</p>

<br/>
<p align="center">
  <a href="https://discord.gg/GgdAeccwDR" target="_blank">
    <img src="https://img.shields.io/badge/Discord-Community-blueviolet?logo=discord&style=for-the-badge" alt="Discord Community" width="200" height="28"/>
  </a>
</p>

<p align="center">
Reach out to me with queries!
</p>
<br/>
<br/>

<div align="">

</div>
<br/>
<h2 class="text-center text-sm font-semibold text-gray-600">TRUSTED BY TEAMS AROUND THE WORLD</h2> 
<p>
<img hspace="10" alt="Varni Jewels" src="https://litekart.in/_app/immutable/assets/varni.DuN9QdLG.webp" class="h-fit w-28 px-2 dark:brightness-0 dark:invert" height="32" style="object-fit: contain;">
<img hspace="10" alt="LRNR" src=".github/lrnr.svg" class="h-8 px-2 dark:brightness-0 dark:invert" height="32" style="object-fit: contain;">
<img hspace="10" alt="Tesoro" src="https://litekart.in/_app/immutable/assets/tesoro.CSdX56Wq.png" class="h-8 px-2 dark:brightness-0 dark:invert" height="32" style="object-fit: contain;">
<img hspace="10" alt="Secretgreen" src="https://litekart.in/_app/immutable/assets/secretgreen.BzzbCiSU.jpg" class="h-8 px-2 dark:brightness-0 dark:invert"  height="32" style="object-fit: contain;">
</p>
<br/>

## What is it?

- Svelte Commerce is a PWA storefront for your existing eCommerce based on Sveltekit.
- It is possible to connect with any eCommerce backend that provides an API
- We are working on adaptors of Medusajs, Shopify

## Features

- 👨🏻‍💻 Its both SSR and SPA
- 🚀 Superfast
- 🔗 It is possible to connect with any eCommerce backend if the backend has Rest API
- 🔓 Svelte Commerce is free and open source. Download and modify it the way you want
- 🛒 Most of the essential features for ecommerce are already integrated
- 💰 No need to make a big leap or invest huge amount. Just take this opend source project and attach to existing backend.

## Get Started

```
git clone https://github.com/mvpcraft/SwiftMart.git
cd SwiftMart
npm i
npm run dev
```

Thats all !

Open http://localhost:3000 on chrome. Your app should be live with awesome svelte-commerce up and running

## Development
run `npm link` inside `litekart-utils` repo
run `npm link @misiki/litekart-utils` inside this repo
run `npm link` inside `litekart-connector` repo
run `npm link @misiki/litekart-connector` inside this repo

## Configuration

There are 3 places to configure

1. `src/lib/config/`
   All non secret and application wide configs are stored here. If required, change according to your requirement.

2. `.env`
   All secrets stored here

3. `src/lib/services/index.ts`
   This is used to define which service to use. Only 1 of the listed service can be active at a time. Valid values are
   - `export * from '@misiki/litekart-connector'`
   - `export * from '@misiki/medusa-connector'`

## Deployment

Click on the button to directly deploy to Netlify or Vercel. Zero configuration required.

The following envirnoment variable is mandatory

```
PUBLIC_LITEKART_DOMAIN=arialshop.com
PUBLIC_LITEKART_API_URL=https://api.litekart.in
```

You can replace the env variable with your store domain

### Docker

We also support docker images, use the following command to pull the latest docker image and deploy it:

## Features

Svelte ecommerce - Headless, Authentication, Cart & Checkout, TailwindCSS, Server Rendered, Proxy + API Integrated, Animations, Lazy Loading, Loading Indicators, Carousel, Instant Search, Faceted Filters, Open Source
