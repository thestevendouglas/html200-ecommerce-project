# Description

This is an assignment to build a responsive ecommerce web page. Nav and product container div will use flexbox. Sidebar/aside is a module that changes layout and location based on window size. Submitting the mailing list signup form results in user feedback on the page. Clicking a product's “add to cart” or “remove from cart” button updates cart count at top.

Students may use the provided mockups to guide their design to whatever extent they like. Matching the mockups is not required.

## Provided Materials

  - basic HTML and CSS
  - JSON list of products in script.js file
  - reset.css
  - images for all products
  - suggested design mockups

## Assignments

Lesson 03:

  - Make design decisions about how you'd like your site to look. You can use the provided mockups to guide your design to whatever extent you'd like- feel free to implement them exactly or make up your own design completely.
  - Code basic CSS for page. `reset.css` file should remain as it is. `main.css` file can be added to, changed, or completely redone.
  - `nav ul` and `.item-container` elements should be styled as flexbox containers. Implement a responsive grid system of your own design, or use a library, or don't use a grid at all. Be sure all important size values are proportional (em, rem, %).
  - We'll continue working on the CSS for this project throughout the course, in particular making it more responsive. The styling does not have to be perfect after this assignment. It's fine to change or add to the HTML as necessary for your styling.

Lesson 05:

  - Write a JS form handler function to be triggered on form submit. It should print to the console a friendly message that includes the value of the form element with name "email". Something like "Thanks for signing up for our mailing list, bobross@example.com!"

Lesson 06:

  - Serve appropriately sized images. Use GIMP or another photo-editing program to resize all images to more reasonable, consistent dimensions. This includes product images, the logo, and any background or other images you've included.

Lesson 07:

  - Write Javascript function that toggles the inclusion of a product in the "cart".
  - Add/edit HTML as necessary to trigger the function on click of a button for each product.

Lesson 08:

  - Write CSS that uses media queries to change layouts/style based on device size. There shoud be at least one obvious layout change in addition to elements fluidly changing width.
  - Finish styling the page.

Lesson 09:

  - Write Javascript that causes the total number of items in the cart to display next to the cart icon when that total changes.
  - Write Javascript that displays the friendly message on form submit in the page, not in the console.
  - Update the HTML and CSS as necessary to accomodate these changes.
  - Update the Testing section of this README with your own information.

*Extra Challenge*: Incorporate unit tests with [Qunit](https://qunitjs.com/).

*Extra Challenge*: Code a popup that toggles between hidden and displayed when user clicks on cart icon. It should show information about items in the cart (maybe list of their names, but up to you).

*Extra Challenge*: Serve appropriately sized images for user's device. Create multiple sizes of each image, and serve the appropriate one using the `srcset` and `sizes` attributes on the `img` tags. This will require naming all of the images consistently, e.g. "ombre-infinity400.jpg", "ombre-infinity200.jpg". [More](https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/) about [srcset](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)

*Extra Challenge*: Use browser storage to save details about a user's cart so when they revisit the page, it's in the same state as when they left it. [More about browser storage](https://www.w3schools.com/html/html5_webstorage.asp)

*Extra Challenge*: Dynamically generate the HTML for product listings from the JSON objects in script.js.

## Requirements

  - Site layout looks good on all sizes of devices. At a minimum, elements are proportionally styled and aside element changes location and layout at different screen sizes. This should be tested using a variety of devices and at least one online browser compatiblity testing tool.
  - Nav and product container elements are styled using flexbox.
  - Appropriately sized images are served.
  - User can add and remove items from their cart, which changes cart count number at top of page.
  - This README is updated to include information about the testing steps taken to ensure site quality.
  - Site is live on GH Pages hosting.

## Grading
Each weekly assignment will be graded independently. There will not be a final grade for the entire project.

## Testing

The demographic of this user base is largely professional, urban, upper working class, who are both men and women. The primary purchasers of scarves are found to have higher than average incomes, live in larger cities and in are geographically located where the winters can be a bit more harsh. Ages of those who purchased or viewed these scarf products fell within the 25-55 age range, relied heavily upon newer smart phone, tablet and desktop computer devices and would browse products while on their lunch breaks or in the evenings after work. 

Our focused demographic uses the most current devices on the market, the most popular and highest selling being the latest apple iphone and ipad. Website responsiveness was tested on responsivedesignchecker.com and looked consistent and fluid on all currently top selling devices. 

Website tested across browsers and devices. Use tools from class.

How data was compiled/discovered/testing steps

Website emulator was used for Microsoft Edge using sonarwhal.com website. Initial analyzation returned 75 errors primarily in performance, security and interoperability. 

Website responsiveness was analyzed using responsivedesignchecker.com


[update this section with information about the testing steps you took to ensure site quality]