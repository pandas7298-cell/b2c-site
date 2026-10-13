# Tabajoy static prototype for Vercel

This directory contains a browse-only static prototype assembled from the 26 current Stitch screens. The original export remains unchanged.

## Deploy

1. Import the Git repository containing this project into Vercel.
2. Set **Root Directory** to `stitch_japanese_squishy_dtc_storefront/vercel-prototype` (or `vercel-prototype` if this directory itself is the repository root).
3. Select **Other** as the framework preset.
4. Leave **Build Command** and **Output Directory** empty; this is a static HTML site.
5. Deploy and open the root URL. `index.html` is the page directory.

If deploying from the command line with Vercel CLI, run it from this directory and use Vercel's static deployment flow.

## Home design

The desktop storefront root page and `/home/desktop/` share the DTC homepage layout. The design emphasizes the tactile product visuals, a scalable featured-products section, and a link to the full collection. Mobile styling remains a separate prototype view.

## Limitations

- This is a design prototype, not a production storefront.
- The desktop homepage uses consumer-store navigation, a featured-products section, and an all-products link to the collection page. Contact, account, search, story, gallery, and news pages are not implemented.
- No live cart, order submission, Medusa backend, or Stripe payment processing is included. Purchase and checkout-finalization controls stay disabled; the order-complete screen is a standalone prototype and is not reached by submitting an order.
- Contact is not created.
- The homepage demo video is served locally from `assets/product-demo.mp4` (about 40 MB); include this file when deploying. Playback uses native controls, muted autoplay, and looping.
- Prices, materials, shipping, and legal/operational details remain unconfirmed. Do not use this deployment to accept sales.
