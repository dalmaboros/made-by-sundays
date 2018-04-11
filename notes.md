# Notes

The custom CSS is separated into these blocks of code:

* `Test Index`
* `Home Index`
* `Mobile Index`
* `Project Pages`

## Style a new index page:
1. Copy and paste the `Test Index` block of code.
2. Replace `#collection-5ab318c1352f534840f96aa0` with the collection ID number of the new index page for each CSS rule.
    * Right click anywhere on the page in the web browser
    * View page source
    * Cmd+F search for "body id"
3. Replace any instance of `#test-01` and `#test-02` with different section ID names.
    * Go to "Pages" on your dashboard
    * Click the gear icon next to the page
    * Scroll down to "URL Slug" - This is the section ID name (without the preceding /)
4. If you have more sections, duplicate the `Test-01 Section` or `Test-02 Section` block of code (the CSS rules are identical)
5. Leave any selector that follows the collection ID or section ID unchanged.
6. Plug in CSS property values.

There are some CSS rules defined in the `Home Index` and `Mobile Index` blocks of code not defined in the `Test Index` block that you can copy as you need them.

You can also right click any element in the web browser and select "Inspect" to see the code for that element.

## Style a new project page:
1. Copy and paste the `Elisa` block of code.
2. Replace `#collection-59ebb25e0abd04fe1a0ca507` with the collection ID number of the new project page for each CSS rule.
    * Right click anywhere on the page in the web browser
    * View page source
    * Cmd+F search for "body id"
3. Leave any selector that follows the collection ID unchanged.
4. Plug in CSS property values.

There are no section IDs for project pages.

# CSS Properties and Values

## Color
All but one type of custom CSS rule control color:
- `background` (changes background color)
- `background-color` (also changes background color)
- `color` (changes font color)
- `fill` (changes color of social icon)

You can declare color a few different ways:
1. Hexadecimal code:
    * `background: #ff000;`
2. RGBA (red green blue alpha):
    * `background: rgba(255,0,0,1);` (the alpha value controls opacity and ranges from 0-1)
3. HSL (hue saturation lightness):
    * `background: (0, 100%, 50%);`
4. Color name:
    * `background: red;`

You can grab all those value types from the Photoshop color picker.
Here's a reference: <https://www.w3schools.com/cssref/css_colors_legal.asp>

## Border
This CSS rule controls a line that appears under certain links:
- `border-bottom`
  - `border-bottom: 2px solid red;` (makes a solid red line 2 pixels thick)
  - `border-bottom: none;` (no bottom border)

Reference: <https://www.w3schools.com/cssref/pr_border-bottom.asp>
