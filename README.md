# Commerce Enhanced Product

Provides enhanced product features for commerce_product.

## Features

- Add base fields to the `commerce_product` entity.
  - `image` Main picture of product.
  - `detail_images` Detail pictures of product.
  - `categories` Let the product entity can be classified with `taxonomy` module.
  - `brand` Let the product entity can belong to a brand taxonomy term.
  - `comments` Add comments functionality to the product.

- Add a taxonomy vocabulary that named `product_categories`.
- Add a taxonomy vocabulary that named `product_brands`.
- Add a views for getting product entities via HTTP GET interface.
- Add stock level field to product variation.
