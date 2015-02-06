0.1.3
  * Merged hjblok/shopify-mock oauth2 branch which makes the SHOPIFY_MOCK_SHOP_BASE_URL
    have optional basic auth params. Without this, testing against current shopify stores
    will fail because it will expect you to be hitting a url with basic auth in it.
