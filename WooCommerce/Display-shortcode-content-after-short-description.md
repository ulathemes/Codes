```
add_filter('woocommerce_short_description', function ($description) {
	if (! is_product()) { return; }   
	return $description.do_shortcode('[mbv name="product-info"]');
});
```

Replace ```[mbv name="product-info"]``` With Your Shortcode
