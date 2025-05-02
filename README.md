# Product Category Grid Block

A lightweight, responsive WordPress block that displays WooCommerce product categories in a flexible grid layout.

## Features

- Grid of WooCommerce product categories with thumbnails and titles
- Automatically uses a product image if the category lacks a thumbnail
- Customizable column count for desktop, tablet, and mobile views
- Supports `alignwide` and `alignfull` layout options in block themes
- No frontend JavaScript — lightweight and performance-friendly

## How to Use

1. Upload and activate the plugin on your WordPress site.
2. In the block editor, insert the **Product Category Grid** block.
3. Use the sidebar controls to:
   - Choose a parent category (or show top-level categories)
   - Show/hide empty categories
   - Set custom column layouts for different screen sizes
   - Adjust layout width (none, wide, full)

## Developer Notes

This block is rendered server-side using a `render_callback`.  
It uses CSS Grid with `--pcg-cols-*` custom properties for responsiveness.

## Credits

Created by [Ed Reibsamen](https://ghettolot.com) for the Ghetto Lot store.

---

MIT License
