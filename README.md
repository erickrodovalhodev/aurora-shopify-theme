# Aurora

Shopify theme built in 2019-2020 on the Online Store 1.0 layout — `.liquid`
templates, no JSON, no sections everywhere.

Kept because it is the theme I actually shipped, and because 1.0 is still
running on stores that never migrated. The 2.0 rebuild lives in
[`aurora-os2`](https://github.com/erickrodovalhodev/aurora-os2).

## install

    shopify theme push --store sua-loja

## what it covers

- product card and collection grid
- AJAX cart drawer with item count from `/cart.js`
- search, breadcrumb, 404
- `settings_schema.json` for merchant-editable copy

## limits

1.0 era: no `sections/*.liquid` on every template, no metafields.
