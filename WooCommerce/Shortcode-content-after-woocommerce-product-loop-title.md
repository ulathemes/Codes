### Display Shortcode's Content After WooCommerce Product Loop Title

```
// Display Shortcode's Content After WooCommerce Product Loop Title
add_action( 'woocommerce_after_shop_loop_item_title', 'my_shcontent', 5 );
function my_shcontent() {
  print do_shortcode ( '[rwmb_meta id="version" ]' );
}
```
