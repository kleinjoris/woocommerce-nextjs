## Setup

First clone/fork the repo and cd into it.

```bash
git clone https://github.com/imranhsayed/nextjs-woocommerce-restapi.git
cd nextjs-woocommerce-restapi
npm ci
npm run dev
```

## Add Headless features for WordPress

- Install and Activate following WordPress Plugins:

* [headless-cms](https://github.com/imranhsayed/headless-cms)
* [woocommerce](https://wordpress.org/plugins/woocommerce/)

## Configuration :wrench:

1. (Required) Create a `.env` file taking reference from `.env-example` and update your WordPressSite URL and Frontend next.js URL.
- `NEXT_PUBLIC_WORDPRESS_URL=https://example.com`
- `NEXT_PUBLIC_SITE_URL=http://localhost.com` ( This will be your frontend Next.js URL)

2. Add your `WC_CONSUMER_KEY` and `WC_CONSUMER_SECRET` to the `.env` by following [WooCommerce > Settings > Advanced > REST API](https://woocommerce.github.io/woocommerce-rest-api-docs/#authentication)

2. In your WordPress Dashboard, Go to Settings > General > Site Address (URL) ( Set this to Frontend URL e.g. http://localhost:3000 during development )
3. Create the Header and Footer Menus In WordPress Dashboard and set them to HCMS Header menu and HCMS Footer Menu respectively.

## Useful Links
- [Stripe](https://dashboard.stripe.com/)
- [Getting Stripe API Keys](https://codeytek.com/create-stripe-checkout-in-next-js-stripe-session-stripe-webhook/)

## Versioning :bookmark_tabs:

I use [Git](https://github.com/) for versioning.

## Author :bust_in_silhouette:

* **[Imran Sayed](https://twitter.com/imranhsayed)**

## License :page_with_curl:

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
