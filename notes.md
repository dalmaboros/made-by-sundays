# Instructions

## Color
All but one type of custom CSS rule control color:
- `background` (changes background color)
- `background-color` (also changes background color)
- `color` (changes font color)
- `fill` (changes color of social icon)

You can declare color a few different ways:
1. Hexadecimal code:
 - `background: #ff000;`
2. RGBA (red green blue alpha):
 - `background: rgba(255,0,0,1);` (the alpha value controls opacity and ranges from 0-1)
3. HSL (hue saturation lightness):
 - `background: (0, 100%, 50%);`
4. Color name:
 - `background: red;`

You can grab all those value types from the Photoshop color picker.
Here's a reference: <https://www.w3schools.com/cssref/css_colors_legal.asp>

## Border
This CSS rule controls a line that appears under certain links:
- `border-bottom`
  - `border-bottom: 2px solid red;` (makes a solid red line 2 pixels thick)
  - `border-bottom: none;` (no bottom border)

Reference: <https://www.w3schools.com/cssref/pr_border-bottom.asp>

## Collection ID
Each web page has a unique collection-id. To find the collection-id:
- View source code
- Find `id` attribute of the `<body>` tag

Reference for CSS selectors: <https://www.w3schools.com/cssref/css_selectors.asp>
