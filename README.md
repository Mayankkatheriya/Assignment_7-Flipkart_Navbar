# Assignment_7-Flipkart_Navbar
## Hosted link: https://mayankkatheriya.github.io/Assignment_7-Flipkart_Navbar/
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/7b224933-3e1f-44be-88af-730e057685c5)
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/c07f55ab-1579-4edd-acac-d45ecc2c340a)

HTML part:\
"DOCTYPE html": This declaration specifies the document type as HTML.\
"html lang='en'": This indicates that the content is in the English language.\
"head": This section holds metadata and external resources for the webpage.\
"meta charset='UTF-8'": This sets the character encoding to UTF-8.\
"meta name='viewport' content='width=device-width, initial-scale=1.0'": This defines the viewport settings for responsive design.\
"title": This sets the title of the webpage, displayed in the browser tab.\
"link rel='stylesheet' href='styles.css'": This links an external CSS file for styling.\
"link rel='preconnect' href='https://fonts.googleapis.com'": This establishes a preconnect relationship with Google Fonts.\
"link rel='preconnect' href='https://fonts.gstatic.com' crossorigin": Another preconnect for Google Fonts with a crossorigin attribute.\
"link href='Google_Fonts_URL' rel='stylesheet'": This links to Google Fonts for the "Roboto" font in various weights.\
"link href='https://fonts.googleapis.com/icon?family=Material+Icons' rel='stylesheet'": This links to Google Fonts for "Material Icons" font.

CSS part:

* (Universal Selector):

Sets CSS properties for all elements on the page.\
Removes default margin and padding.\
Uses border-box sizing to include padding and borders within an element's total width and height.

html:

Sets the height of the HTML element to 1500px.

body:

Specifies the font family as "Roboto" or a sans-serif fallback.\
Sets the background color to black.\
Establishes the body element as a reference point for positioning elements.\
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/0e299cfb-3c29-4d0c-bd77-ff12a4d1f41b)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/9447344c-087a-4938-8907-a0b5a63798e5)
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/18ac927e-b635-41aa-ab12-fe7d3a6a5073)
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/23eeae4b-3beb-44ce-bd0c-18be97082884)

HTML part:\
Inside the "body" tag:

"header": This represents the header section of the webpage.\
"div class='navbar'": Inside the header, this div defines the navigation bar.\
"div class='logo'": Inside the navbar, this div holds the logo image.\
"img src='logo_URL' alt='logo'": An image is displayed with a URL and an alt attribute.\
"div class='search-bar'": Inside the navbar, this div contains the search bar.\
"input type='text' placeholder='Search for products, brands and more'": An input field for search is present, with a placeholder.\
"button": A button element is used for the search button.\
"i class='material-icons'": An icon from the Material Icons font is included.\
"div class='login'": Inside the navbar, this div represents the login option.\
"div class='seller'": Inside the navbar, this div signifies the "Become a Seller" option.\
"div class='more'": Inside the navbar, this div indicates the "More" option.\
"i class='material-icons'": An expand_more icon from Material Icons font.\
"div class='cart'": Inside the navbar, this div holds the cart icon and text.

CSS part: 

header:

Sets a white background color for the header.\
Spans the entire width of its container.

header .navbar:

Uses flexbox for layout with center alignment.\
Sets a background color using an RGB value.\
Spans the entire width of its container.\
Centers its content horizontally using justify-content.\
Aligns its content vertically using align-items.\
Adds padding on top and bottom (5px) and spans the entire width.

.logo:

Adds a right margin of 15px to create spacing.\
Sets the cursor to indicate interactivity.

.logo img:

Sets a fixed width (80px) and height (35px) for the logo image.

.search-bar:

Sets the width to 450px.\
Adds right margin for spacing.\
Positions the search bar relatively within its container.

.search-bar input:

Spans the entire width.\
Sets a fixed height of 35px.\
Defines font size, removes borders and outlines.\
Adds padding on top and bottom (5px) and left and right (10px).

.search-bar button:

Sets a fixed height (28px) and background color.\
Removes borders, sets margin-left, and uses an absolute position for precise placement.\
Defines cursor style.

.search-bar button i:

Sets font size and color for an icon inside the search button.

.login:

Sets background color and text color.\
Defines font size, font weight, padding, and cursor.\
Adds right margin for spacing.

.seller:

Sets text color, font size, font weight, and cursor.\
Adds right margin for spacing.

.cart, .more:

Uses flexbox for centering content vertically and horizontally.\
Defines cursor style.

.cart span, .more span:

Sets text color, font size, and font weight.

.cart i:

Sets color and font size for an icon within the cart element.

.more i:

Sets color and font size for an icon within the "more" element.\
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/e53eab13-8d4c-406d-a6f6-b9fadf71827e)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/ead4c1db-cd3e-4d4f-9997-0f0ea2250e0c)
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/4248a53e-8203-43a6-989e-d6f5950b91fc)

HTML part:\
Inside the "header" tag:

"div class='catagories'": Inside the header, this div represents the categories section.\
"div class='catagory'": Inside the categories div, this div signifies a single category.\
"div class='catgory-image'": Inside the category div, this div holds the category image.\
"img src='image_URL' alt='offers'": An image is displayed with a URL and an alt attribute.\
"div class='text'": Inside the category div, this div contains text content.\
"span": A span element carries text content.

CSS part:

.catagories:

Uses flexbox for layout with center alignment.\
Adds space between children using the gap property.\
Adds padding on top and bottom (15px) and spans the entire width.

.catagory:

Uses flexbox for layout with center alignment.\
Stacks its child elements vertically.\
Sets the cursor to indicate interactivity.

.catagory img:

Sets a fixed width (65px) and height (65px) for the category image.

.catagory .text:

Uses flexbox for layout with center alignment.

.catagory .text span:

Sets font size and font weight for the text within the category.

.catagory .text i:

Sets font size for an icon within the category text.\
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/cdc7982a-62af-4faf-8d45-439d10011512)

Now Copy and paste the catagory div as many times you want it will aranged in Systematic way\
![image](https://github.com/Mayankkatheriya/Assignment_7-Flipkart_Navbar/assets/128832286/17717e37-17e3-4873-801d-a4687802a558)
## Now Flipkart Navbar is ready
# Thankyou
