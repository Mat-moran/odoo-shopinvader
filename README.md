
<!-- /!\ Non OCA Context : Set here the badge of your runbot / runboat instance. -->
[![Pre-commit Status](https://github.com/shopinvader/odoo-shopinvader/actions/workflows/pre-commit.yml/badge.svg?branch=16.0)](https://github.com/shopinvader/odoo-shopinvader/actions/workflows/pre-commit.yml?query=branch%3A16.0)
[![Build Status](https://github.com/shopinvader/odoo-shopinvader/actions/workflows/test.yml/badge.svg?branch=16.0)](https://github.com/shopinvader/odoo-shopinvader/actions/workflows/test.yml?query=branch%3A16.0)
[![codecov](https://codecov.io/gh/shopinvader/odoo-shopinvader/branch/16.0/graph/badge.svg)](https://codecov.io/gh/shopinvader/odoo-shopinvader)
<!-- /!\ Non OCA Context : Set here the badge of your translation instance. -->

<!-- /!\ do not modify above this line -->

# Shopinvader

Odoo REST APIs for e-commerce.

<!-- /!\ do not modify below this line -->

<!-- prettier-ignore-start -->

[//]: # (addons)

Unported addons
---------------
addon | version | maintainers | summary
--- | --- | --- | ---
[base_url](base_url/) | 14.0.1.0.2 (unported) |  | keep history of url for products & categories
[partner_contact_company](partner_contact_company/) | 10.0.1.0.0 (unported) |  | Partner Company
[product_online_category](product_online_category/) | 10.0.1.0.0 (unported) |  | Product categories dedicated to online shop
[shopinvader](shopinvader/) | 14.0.5.24.2 (unported) |  | Shopinvader
[shopinvader_algolia](shopinvader_algolia/) | 14.0.2.0.0 (unported) |  | Shopinvader Algolia Connector
[shopinvader_assortment](shopinvader_assortment/) | 14.0.1.2.0 (unported) |  | Shopinvader Assortment
[shopinvader_auth_api_key](shopinvader_auth_api_key/) | 14.0.1.1.1 (unported) |  | Shopinvader API_KEY Authentication
[shopinvader_auth_jwt](shopinvader_auth_jwt/) | 14.0.1.2.0 (unported) |  | Find shopinvader backend and partner from JWT token
[shopinvader_backend_image_proxy](shopinvader_backend_image_proxy/) | 14.0.1.0.2 (unported) |  | Add possibility to replace the image URL by the proxy url set on the SE backend
[shopinvader_cart_expiry](shopinvader_cart_expiry/) | 14.0.1.0.0 (unported) |  | Shopinvader module to manage an expiry delay on cart
[shopinvader_category_image_for_product](shopinvader_category_image_for_product/) | 14.0.1.0.1 (unported) |  | Shopinvader Display category image for product
[shopinvader_contact_address_default](shopinvader_contact_address_default/) | 14.0.1.0.0 (unported) | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Integrates `partner_contact_address_default` with Shopinvader
[shopinvader_contact_company](shopinvader_contact_company/) | 10.0.1.0.0 (unported) |  | Make available the field company in the address form
[shopinvader_customer_activity](shopinvader_customer_activity/) | 14.0.1.0.1 (unported) | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Log the customer's shop activity
[shopinvader_customer_invoicing_mode](shopinvader_customer_invoicing_mode/) | 14.0.1.0.0 (unported) |  | Glue module to expose the invoicing_mode field to shopinvader
[shopinvader_customer_multi_user](shopinvader_customer_multi_user/) | 14.0.1.5.0 (unported) |  | Enable registration of multiple users per each company customer.
[shopinvader_customer_multi_user_company_group](shopinvader_customer_multi_user_company_group/) | 14.0.1.0.0 (unported) |  | Share shopinvader records within the Company Group
[shopinvader_customer_multi_user_validate](shopinvader_customer_multi_user_validate/) | 14.0.1.1.0 (unported) |  | Glue module for `shopinvader_customer_validate` and `shopinvader_customer_multi_user`.
[shopinvader_customer_multi_user_wishlist](shopinvader_customer_multi_user_wishlist/) | 14.0.1.1.0 (unported) |  | Integrate customer multi user and wishlist.
[shopinvader_customer_price](shopinvader_customer_price/) | 14.0.1.0.2 (unported) |  | Expose customer's specific prices.
[shopinvader_customer_price_wishlist](shopinvader_customer_price_wishlist/) | 14.0.1.1.0 (unported) |  | Expose customer's specific prices.
[shopinvader_customer_validate](shopinvader_customer_validate/) | 14.0.1.3.0 (unported) |  | Provide configuration and machinery to validate customers.
[shopinvader_delivery_carrier](shopinvader_delivery_carrier/) | 14.0.2.3.0 (unported) |  | Carrier integration for Shopinvader
[shopinvader_delivery_instruction](shopinvader_delivery_instruction/) | 14.0.1.0.2 (unported) |  | Shopinvader addons to let user define delivery instructions
[shopinvader_delivery_state](shopinvader_delivery_state/) | 14.0.1.0.0 (unported) |  | Shopinvader delivery state
[shopinvader_demo_app](shopinvader_demo_app/) | 12.0.2.0.4 (unported) |  | Shopinvader Demo App
[shopinvader_easy_binding](shopinvader_easy_binding/) | 14.0.1.0.1 (unported) | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Easily manage Shopinvader bindings for your company backend.
[shopinvader_elasticsearch](shopinvader_elasticsearch/) | 14.0.3.0.1 (unported) |  | Shopinvader Elasticsearch Connector
[shopinvader_guest_mode](shopinvader_guest_mode/) | 14.0.1.1.0 (unported) |  | Guest mode for Shopinvader
[shopinvader_image](shopinvader_image/) | 14.0.1.3.0 (unported) |  | Add the export of Image for Shopinvader
[shopinvader_import_image](shopinvader_import_image/) | 14.0.1.1.1 (unported) |  | Import product images
[shopinvader_invoice](shopinvader_invoice/) | 14.0.2.2.0 (unported) |  | Shopinvader Invoice module
[shopinvader_lead](shopinvader_lead/) | 14.0.1.1.0 (unported) |  | Shopinvader Lead Management
[shopinvader_locomotive](shopinvader_locomotive/) | 14.0.2.1.1 (unported) |  | Manage communications between Shopinvader and Locomotive CMS
[shopinvader_locomotive_algolia](shopinvader_locomotive_algolia/) | 14.0.1.0.0 (unported) |  | This addons is used to push the initial algolia configuration to locomotive
[shopinvader_locomotive_contact_company](shopinvader_locomotive_contact_company/) | 10.0.1.0.0 (unported) |  | Synchronize the contact_name with customer name
[shopinvader_locomotive_elasticsearch](shopinvader_locomotive_elasticsearch/) | 12.0.1.1.0 (unported) |  | This addons is used to push the initial elasticsearch configuration to locomotive
[shopinvader_locomotive_guest_mode](shopinvader_locomotive_guest_mode/) | 14.0.1.0.3 (unported) |  | Shopinvader guest mode for locomotive
[shopinvader_locomotive_reset_password](shopinvader_locomotive_reset_password/) | 14.0.1.3.0 (unported) |  | Give the possibility to send a email to reset thepassword from odoo
[shopinvader_locomotive_sale_profile](shopinvader_locomotive_sale_profile/) | 14.0.1.0.1 (unported) |  | Synchronize the sale profile info to customer record on Locomotive
[shopinvader_locomotive_wishlist](shopinvader_locomotive_wishlist/) | 14.0.1.0.2 (unported) |  | Synchronize wishlist details to Locomotive users record.
[shopinvader_membership](shopinvader_membership/) | 14.0.1.0.1 (unported) |  | Shopinvader Membership module
[shopinvader_multi_cart](shopinvader_multi_cart/) | 14.0.1.1.1 (unported) |  | Manage multiple carts in Shopinvader
[shopinvader_multi_category](shopinvader_multi_category/) | 14.0.1.0.0 (unported) |  | Shopinvader Many Categories
[shopinvader_notification_default](shopinvader_notification_default/) | 14.0.1.0.1 (unported) |  | Provide default notification templates for Shopinvader suite.
[shopinvader_partner_firstname](shopinvader_partner_firstname/) | 14.0.1.0.0 (unported) |  | Shopinvader Customer firstname/lastname
[shopinvader_partner_vat](shopinvader_partner_vat/) | 14.0.1.0.2 (unported) |  | Shopinvader Check VAT with invader environnement
[shopinvader_pending_cart_reminder](shopinvader_pending_cart_reminder/) | 14.0.1.0.0 (unported) |  | Shopinvader module to relaunch the customer when the cart/sale is not confirmed yet. Configure the delay and the email template on the backend.
[shopinvader_portal_mode](shopinvader_portal_mode/) | 14.0.1.1.0 (unported) |  | Shopinvader portal mode
[shopinvader_pos](shopinvader_pos/) | 14.0.2.2.0 (unported) |  | Shopinvader for PoS
[shopinvader_price_per_qty](shopinvader_price_per_qty/) | 14.0.1.0.1 (unported) |  | Shopinvader price per quantity
[shopinvader_product_attribute_set](shopinvader_product_attribute_set/) | 14.0.1.0.0 (unported) |  | Expose all PIM' Attribute sets with Shopinvader
[shopinvader_product_brand](shopinvader_product_brand/) | 14.0.1.3.1 (unported) |  | Shopinvader product Brand
[shopinvader_product_brand_image](shopinvader_product_brand_image/) | 14.0.1.1.0 (unported) |  | Shopinvader product Brand Image
[shopinvader_product_brand_tag](shopinvader_product_brand_tag/) | 14.0.1.0.0 (unported) |  | Index Product Brand Tags in Shopinvader
[shopinvader_product_manufactured_for](shopinvader_product_manufactured_for/) | 14.0.1.0.0 (unported) |  | Manage Product Made Specially For Some Customers
[shopinvader_product_media](shopinvader_product_media/) | 14.0.1.0.0 (unported) |  | Index storage media data into external search engine
[shopinvader_product_new](shopinvader_product_new/) | 14.0.1.0.1 (unported) |  | Shopinvader product new
[shopinvader_product_order](shopinvader_product_order/) | 14.0.1.1.0 (unported) |  | Manage product display order on Shopinvader
[shopinvader_product_price_tax](shopinvader_product_price_tax/) | 14.0.1.2.0 (unported) |  | Exposes product prices with and without taxes
[shopinvader_product_stock](shopinvader_product_stock/) | 14.0.1.0.3 (unported) |  | This module is used to choose a stock field during theexport (by backend)
[shopinvader_product_stock_assortment](shopinvader_product_stock_assortment/) | 14.0.1.0.2 (unported) |  | This module is used to let the Shopinvader product assortment use the stock context in Shopinvader product stock.
[shopinvader_product_stock_forecast](shopinvader_product_stock_forecast/) | 14.0.1.0.0 (unported) | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Export Stock Forecast data along with product stocks.
[shopinvader_product_stock_forecast_expiry](shopinvader_product_stock_forecast_expiry/) | 14.0.1.0.0 (unported) | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Integrates product lot expiration into the forecast
[shopinvader_product_stock_state](shopinvader_product_stock_state/) | 14.0.1.0.0 (unported) |  | This module is used to choose a stock state during theexport (by backend)
[shopinvader_product_template_multi_link](shopinvader_product_template_multi_link/) | 14.0.1.1.0 (unported) |  | Shopinvader Product Link
[shopinvader_product_template_multi_link_date_span](shopinvader_product_template_multi_link_date_span/) | 14.0.1.0.0 (unported) |  | Integrate `product_template_multi_link_date_span` in Shopinvader
[shopinvader_product_template_tags](shopinvader_product_template_tags/) | 14.0.1.0.0 (unported) |  | Index Product Template Tags in Shopinvader
[shopinvader_product_variant_multi_link](shopinvader_product_variant_multi_link/) | 14.0.1.0.0 (unported) |  | Integrate product_variant_multi_link with Shopinvader
[shopinvader_product_variant_selector](shopinvader_product_variant_selector/) | 14.0.1.0.0 (unported) |  | Ease creation of variants selector on shopinvader sites
[shopinvader_product_video_link](shopinvader_product_video_link/) | 14.0.1.0.2 (unported) |  | Add video on your Shopinvader website
[shopinvader_promotion_rule](shopinvader_promotion_rule/) | 10.0.1.0.0 (unported) |  | Module to manage Promotion Rule with shopinvader
[shopinvader_quotation](shopinvader_quotation/) | 14.0.2.3.1 (unported) |  | Shopinvader Quotation
[shopinvader_sale_amount_by_group](shopinvader_sale_amount_by_group/) | 14.0.1.0.0 (unported) |  | Expose the amount by tax to shopinvader
[shopinvader_sale_automatic_workflow](shopinvader_sale_automatic_workflow/) | 14.0.1.1.0 (unported) | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Use sale automatic workflows for Shopinvader orders
[shopinvader_sale_communication](shopinvader_sale_communication/) | 10.0.1.0.0 (unported) |  | This module adds information fields for customers and vendors.
[shopinvader_sale_coupon](shopinvader_sale_coupon/) | 14.0.1.2.0 (unported) |  | Manage Promotion and Coupon programs in Shopinvader
[shopinvader_sale_packaging](shopinvader_sale_packaging/) | 14.0.1.1.0 (unported) |  | Shopinvader Sale Packaging
[shopinvader_sale_packaging_wishlist](shopinvader_sale_packaging_wishlist/) | 14.0.1.0.0 (unported) |  | Add packaging information to wishlists
[shopinvader_sale_profile](shopinvader_sale_profile/) | 14.0.1.3.0 (unported) |  | ShopInvader - Sale profile
[shopinvader_sale_report](shopinvader_sale_report/) | 10.0.1.0.0 (unported) |  | Shopinvader addons to extend sale report with backend
[shopinvader_search_engine](shopinvader_search_engine/) | 14.0.1.4.1 (unported) |  | Shopinvader Catalog Search Engine Connector
[shopinvader_wishlist](shopinvader_wishlist/) | 14.0.1.1.0 (unported) |  | Handle shop wishlist

[//]: # (end addons)

<!-- prettier-ignore-end -->

## Licenses

This repository is licensed under [AGPL-3.0](LICENSE).

However, each module can have a totally different license, as long as they adhere to Shopinvader
policy. Consult each module's `__manifest__.py` file, which contains a `license` key
that explains its license.

----
<!-- /!\ Non OCA Context : Set here the full description of your organization. -->
