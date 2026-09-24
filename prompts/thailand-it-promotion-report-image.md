# Thailand IT Promotion Report — Image Generation Prompt

## Trigger
Use this prompt ONLY when the user explicitly asks to generate images/pictures from the Thailand IT Promotion Report.

Do NOT automatically generate images during the normal daily report.
Do NOT merge this prompt with `prompts/thailand-it-promotion-report.md`. Keep the report-data prompt and image-generation prompt separate.

## Source of Truth
Use ONLY products and prices that already appear in the Thailand IT Promotion Report being converted to images.

- Do not discover, add, remove, substitute, or re-price products while creating the image.
- Product names/models and prices must match the report exactly.
- For each product, show ONLY the cheapest/best price already established in the report.
- Do not show store/seller names.
- Do not show cross-store price comparisons.
- Do not invent missing prices, specs, discounts, or products.

## Output Structure
Generate ONE separate image per report section/category:

1. 💻 Laptop — one image
2. 📱 Smartphone / Phone — one image
3. 📲 Tablet / iPad — one image
4. 🖥️ Monitor — one image
5. 🧩 Desktop / PC Components — one image

Each category image is a SINGLE collage/catalog-style image containing MULTIPLE product items from that category.

Example: the Laptop image is ONE image that contains many laptop promotion items from the report, not one image per laptop.

Include as many report items for that category as can remain clearly readable in the single category image. Do not create one image per product.

Never combine all categories into one image unless the user explicitly asks for that.

## Required Content on Every Image
- Report date clearly visible
- Category/section title clearly visible
- Relevant product image/visual for each listed item
- Exact product/model identity from the report
- Cheapest/best price from the report
- Clean, readable Thailand IT promotion-report visual style

## Prohibited Content
- No store names
- No seller logos unless explicitly requested
- No alternative store prices
- No products that were not in the report
- No changed model names/SKUs
- No changed prices
- No automatic image generation; generate only after an explicit user request

## Accuracy Priority
Text accuracy is more important than decoration. Before image generation, use the report as the authoritative source and preserve its product/model and price data exactly.
