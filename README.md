# Conversion-Focused Shopify Product Card

A custom, high-converting product card template for Shopify themes built to maximize average order value and click-through rates directly from collection pages. 

## Key Upgrades over Standard Themes

→ **Inline Variant Swatches:** Shoppers can choose options directly on the collection page, skipping a step in the standard sales funnel.
→ **Immediate Micro-Proof:** Review counts and star ratings sit prominently below the product title to build instant authority.
→ **Clear Visual Hierarchy:** Isolates primary pricing from dynamic discount tags for fast visual scanning.
→ **Direct Add-to-Cart (ATC):** Converts interest into direct actions straight from the product grid.

---

## Installation Guide

Follow these steps to safely replace your theme's default product card with this conversion-focused setup.

### Step 1: Backup Your Current Theme
Before making any changes to your production code, it is best practice to duplicate your theme.
1. Log in to your **Shopify Admin Dashboard**.
2. Navigate to **Online Store** → **Themes**.
3. Click the **Three Dots (...)** next to your active theme and select **Duplicate**.

### Step 2: Open the Code Editor
1. On your active theme, click the **Three Dots (...)** and choose **Edit code**.

### Step 3: Locate and Backup the Existing Product Card File
1. In the left-hand sidebar, scroll down to the **Snippets** directory.
2. Search for your theme's default product card file (commonly named `card-product.liquid`, `product-card.liquid`, or `product-grid-item.liquid`).
3. Click on the file to open it.
4. Click the file options or rename the file by adding `-backup` to the end (e.g., rename `card-product.liquid` to `card-product-backup.liquid`). 
*Note: This ensures you can revert back instantly if needed.*

### Step 4: Create the New Product Card File
1. Inside the **Snippets** directory, click **Add a new snippet**.
2. Name it exactly the same as your original file name (e.g., `card-product` or `product-card`). Do not include the `.liquid` extension, Shopify adds it automatically.
3. Click **Done**.

### Step 5: Deploy the Code
1. Open the newly created blank file.
2. Copy the entire source code provided in this repository.
3. Paste the code directly into your new snippet file.
4. Click **Save** in the top right corner.

### Step 6: Verify and Test
1. Navigate back to your live site or preview mode.
2. Go to a collection page or the homepage product grid.
3. Verify that the inline swatches, rating layouts, and direct add-to-cart features render cleanly and function correctly across both desktop and mobile viewports.
