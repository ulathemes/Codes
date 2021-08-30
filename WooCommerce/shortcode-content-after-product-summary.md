### Shortcode's Content After WooCommerce Product Summary

```
// Display Shortcode's Content After WooCommerce Product Summary
add_action( 'woocommerce_after_single_product_summary', 'my_content', 5 );
function my_content() {
  print do_shortcode ( '[mbv name="product-info"]' );
}

```
