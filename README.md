# kite-packaging-scraper

# Instructions:
- Extract all the products from the website.
- Traverse all the categories and sub categories.
- Extract all product variants.
- Make sure there are no duplicate urls


Traverse Categories [23 in Count]:
Located: Left Navbar
Webpage Page Type: Static
xpath: //div[@class='list-group']

Traverse Sub Categories:
Located: Left Navbar
Web Page Type: Static
Xpath: //a[@class="list-group-item dropme-left "]

The sub category page could be product variant or might have more sub categories.
Traverse Sub Sub Categories:
Located: Main Body
Web Page Type: Static
Xpath: //div[@class="tile-container"]


Traverse Product Variants:
Located: Main Body
Web Page Type: JS / API
Fields:
Categories
Url
Root Gallery Images
Custom Bullet Description
Products filter
About Section

Variants has
Name
basket_desc
part_number
product_notes
Images / Videos Panel
box_type
Price Per Unit
Price Per Pack
Unit Per Pallets
Unit Per Pack
