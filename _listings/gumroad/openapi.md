---
swagger: "2.0"
x-collection-name: Gumroad
x-complete: 1
info:
  title: Gumroad
  description: api-for-selling-of-digital-goods-and-media-
  termsOfService: https://gumroad.com/terms
  version: v1
host: api.gumroad.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/:product_id/variant_categories/:variant_category_id/variants:
    post:
      summary: Post Products Variant Categories Variant Category Variants
      description: Create a new variant of a product.
      operationId: postProductsProductVariantCategoriesVariantCategoryVariants
      x-api-path-slug: productsproduct-idvariant-categoriesvariant-category-idvariants-post
      parameters:
      - in: query
        name: max_purchase_count
      - in: query
        name: name
      - in: query
        name: price_difference_cents
      - in: query
        name: variant
      responses:
        200:
          description: OK
      tags:
      - Products
      - Variant
      - Categories
      - :variant
      - Category
      - Variants
  /products/:product_id/variant_categories/:variant_category_id/variants/:id:
    delete:
      summary: Delete Products Variant Categories Variant Category Variants
      description: Permanently delete a variant of a product.
      operationId: deleteProductsProductVariantCategoriesVariantCategoryVariants
      x-api-path-slug: productsproduct-idvariant-categoriesvariant-category-idvariantsid-delete
      responses:
        200:
          description: OK
      tags:
      - Products
      - Variant
      - Categories
      - :variant
      - Category
      - Variants
    get:
      summary: Get Products Variant Categories Variant Category Variants
      description: Retrieve the details of a variant of a product.
      operationId: getProductsProductVariantCategoriesVariantCategoryVariants
      x-api-path-slug: productsproduct-idvariant-categoriesvariant-category-idvariantsid-get
      responses:
        200:
          description: OK
      tags:
      - Products
      - Variant
      - Categories
      - :variant
      - Category
      - Variants
    put:
      summary: Put Products Variant Categories Variant Category Variants
      description: Edit a variant of an existing product.
      operationId: putProductsProductVariantCategoriesVariantCategoryVariants
      x-api-path-slug: productsproduct-idvariant-categoriesvariant-category-idvariantsid-put
      parameters:
      - in: query
        name: max_purchase_count
      - in: query
        name: name
      - in: query
        name: price_difference_cents
      - in: query
        name: variant
      responses:
        200:
          description: OK
      tags:
      - Products
      - Variant
      - Categories
      - :variant
      - Category
      - Variants
---