Date: 03/09/2024

#1# Validation Testing: Testing to ensure that a web page's code meets specified requirements and industry standards. It helps to verify that the code is free from syntax errors, well-structured and the web pages display correctly and function well across different browsers.
Test Cases: 
#Test Case 1: HTML Validation- check that HTML files pass W3C validation. Check for unclosed tags, improper nesting of elements, and semantic correctness and attribute Syntax Errors.   
Description: Verify that all HTML files (index.html, photo.html, about.html, contact.html) pass validation checks.
Steps to Execute:
    Go to the W3C Markup Validation Service website. ( https://validator.w3.org/)
    Upload the html files for validation. (index.html, photo.html, about.html, contact.html)
    Click Check.
    Review the results.
    Fix any errors and recheck.
    Expected Results: All the HTML files meet W3C standards and no errors.
Test Data/Configurations: All HTML files (index.html, photo.html, about.html, contact.html)

#Test Case 2: CSS Validation- check that CSS files pass W3C validation. Check for proper syntax, selectors and duplicate CSS Code.
Description: Verify that all CSS files (general.css, header.css, footer.css, index.css, photo.css, about.css, contact.css) pass validation checks.
Steps to Execute:
    Go to the W3C CSS Validation Service website. (https://jigsaw.w3.org/css-validator/)
    Upload the CSS files for validation. (index.css, general.css, header.css, footer.css, photo.css, about.css, contact.css)
    Click Check.
    Review the results.
    Fix any errors and recheck.
    Expected Results: All the CSS files meet W3C standards and no errors.
Test Data/Configurations: All CSS files (general.css, header.css, footer.css, index.css, photo.css, about.css, contact.css)


#2 Accessibility Testing: Testing is conducted to ensure that the website is usable by people with disabilities, including those with visual, physical, auditory and cognitive impairments. Auditory impairment testing is excluded as there is no audio content. This testing includes checking for the proper use of alt attributes, keyboard navigation, and colour contrast. Also verify the website content to ensure it is clear, simple, and easy to navigate.
Test Cases:
    Alt Text Check: Verify that images on the website have descriptive alt attributes to aid users who rely on screen readers.
    Colour Contrast: Confirm that text has sufficient contrast against its background to be readable by users with visual impairments.
    Content understandability and navigation: Check the website content to ensure it is clear, simple, and easy to navigate.
    Keyboard Navigation: check that all interactive elements are accessible and navigable using a keyboard.
Test Case 3: Accessibility - Alt Text, Colour Contrast, Content understandability and navigation

Description: To check all HTML files on the website. Use web accessibility evaluation tool (WAVE) to check Alt Text, Colour Contrast, Content understandability and navigation to adhere to key web accessibility standards.

Steps to Execute:
    Go to the web accessibility evaluation tool - WAVE (wave.webaim.org)
    Install the browser extensions.
    Go to the web pages.
    Click the WAVE extension icon in your browser’s toolbar.
    Review the results-
    Ensure the images have an appropriate alt attribute.
    Check that the text colour has sufficient colour contrast against its background.
    Check for poorly structured content that might be difficult for users with cognitive impairments to understand.
    Ensure that the website’s navigation is straightforward, which supports users with cognitive disabilities in finding and using content effectively.
    Address the identified issues and use WAVE again to ensure that accessibility issues are resolved.
    Expected Results: All images should have descriptive alt text to convey the meaning. Text colour should have sufficient colour contrast against its background. The website content should be clear, simple, and easy to navigate.
Test Data/Configurations**:** On images, text and contents, on the website

1.3 Browser Testing:
Description: Browser testing checks that the website displays and functions correctly across various browsers and devices, including different screen sizes and resolutions.
Test Cases:
    Cross-Browser Compatibility: Test website functionality and layout across browsers such as Chrome, Edge and Firefox.
    Responsive Design: Verify that the website’s layout adjusts correctly across different screen sizes (mobile, tablet, desktop).







Test case 4: Keyboard Navigation

Description:

WebDev Tools: Verify focus indicators and tab order using DevTools.

WAVE Extension: Identify and address accessibility issues related to keyboard navigation.

Manual Testing: Test for the keyboard navigation and focus visibility.

Steps to execute:

For WebDev Tools:

To check focus indicators and tab order using Chrome DevTools:
Open Chrome DevTools: Right-click on the webpage and select "Inspect," or press Ctrl + Shift + I (Windows/Linux) or Cmd + Option + I (Mac).
Go to the Accessibility Tab: Click the "Accessibility" tab in DevTools.
Inspect Focus Indicators: Use the "Elements" panel to view focus states and accessibility properties.
Simulate Keyboard Navigation: Press the "Tab" key to navigate and ensure the focus order is logical and visible.
For WAVE Extension:

Open the webpage you want to test in the wave extension tool.
Run the Evaluation to see accessibility issues.
Check for keyboard-related issues using focus indicators and error reports.
Perform manual keyboard navigation
For Manual Testing: Use the Tab key to navigate through the website and ensure that all interactive elements (links, buttons, form fields) are reachable and in a logical order.

Expected Result: All interactive elements like links, buttons and forms should be navigated using the keyboard.

Test Data/Configurations**:** On button, links, and contact forms of the website.

Test Case 4: Browser Compatibility, Responsive Design.

Description: Test for Browser Compatibility to ensure the website functions correctly across different browsers and versions (Chrome, Firefox, Edge).

Test for Responsive Design to verify that the website adjusts seamlessly to various screen sizes and devices, ensuring an optimal user experience on desktops, tablets, and smartphones.

Steps to Execute:

Open your project folder in VS Code.
Start a local server using Live Server to open HTML files.
Install and Set Up BrowserStack Extension.
Launch your website locally through Live Server. Note the local URL (e.g., http://localhost:5500).
Start BrowserStack Extension:
Perform Manual Testing: Test navigation elements (hamburger menu, links, buttons). Test on the form by Submitting forms to ensure functionality.
Choose various devices and screen sizes from the BrowserStack extension to test responsiveness. Check how your site looks on various devices (mobile, tablet, desktop).
Test various screen resolutions.

Check for any issues Make necessary changes to the code and retest to verify fixes.
Repeat the testing process for other selected browsers (Chrome, Edge, Firefox)
Verify that the website layout and functionality are consistent across all browsers.
Expected Results: The website is compatible across different browsers and responsive on various devices and screen sizes.

Test Data/Configurations: On various browsers like Chrome, Edge and Firefox.

3. Test Execution Schedule:

Validation Testing:

- Start Date: 1/09/2024

- End Date: 1/09/2024

Accessibility Testing:

- Start Date: 2/09/2024

- End Date: 2/09/2024

Browser Testing:

- Start Date: 3/09/2024

- End Date: 3/09/2024

4. Test Execution:

4.1 Validation Te sting:

- Tools/Software Used: W3C HTML Validator, W3C CSS Validator

- Procedures: Run the HTML files and CSS files through the W3C HTML Validator and W3C CSS Validator. review and document results.

- Results:

Validation of HTML files: Using W3C HTML Validator HTML files are validated.
Validation of CSS files: Using W3C CSS Validator CSC files are validated
Errors found: In index.html

The end tag section was seen, but there were open elements. From line 105, column 5; to line 105, column 1
Unclosed element div. From line 48, column 9; to line 48, column 31
 Stray start tag footer**.** From line 108, column 1; to line 108, column 8
An img element must have an alt attribute, except under certain conditions
From line 116, column 13; to line 116, column 96

From line 117, column 13; to line 117, column 96

From line 118, column 13; to line 118, column 96

Resolved the Errors-

-By closing the </div > element and placing the closing </body> tag correctly.

-In the footer img element, the alt attribute is added and kept empty because there is a nearby text that explains the image.

-Added footer element alt attribute in index.html, photo.html, about.html and contact.html.

Errors: In Photo.html

-Element a not allowed as a child of element ul in this context. From line 66 to line 74.

Resolved the errors- deleted <ul> element

Errors: In about.html

-No <p> element in scope but </p> end tag is seen.

Resolved by adding <p> tag.

Errors: In contact.html

-In the form, <Textarea> element had autocomplete attribute which was not required. Resolved by removing it.

No errors were found in general.html, footer.css, photo.css

Error 1: header.css

Value Error: padding, is an incorrect operator: 0,20px

Resolved by removing comma.

Error 2: Index.css
Value Error: margin, is an incorrect operator: 0, auto on Line 68

Resolved by removing comma.

Error 3: about.css

Value Error: font-weight 400% is not a font-weight value: 400% on Line 13

Resolved by removing %

Error 4: contact.css

Value Error: border too many values or values not recognized on line 21.

Resolved by deleting the line 21

4.2 Accessibility Testing:

- Tools/Software Used: WAVE browser extension, Live server, DevTools,

- Procedures:

Use WAVE tools to test accessibility features.
Manually check keyboard navigation
DevTools: Use the Accessibility tab in DevTools to check focus indicators and tab order.
- Results:

Test conducted on the home page, photo page, about page and contact page.

Errors were found on the home page, photo page, about page and contact page.

1. empty form label – found on the header of home page.

2. Missing alternative text- missing alt text in the footer element.

3. Contrast Errors – Found very low contrast between link text and background colours on the following links

Link: Home

Link: Photos

Link: About

Link: Contact

Link: Denise Jans

Link: Unsplash

Resolved errors–

- The form label on the home page has an image element and not the text. So empty form label error is a false positive.

-Resolved the missing alternative text error by adding an alt attribute in the footer.

- Contrast Errors were resolved on all links by increasing the contrast against the background and surrounding text.

During the keyboard tab testing using Live server and Chrome DevTools, no errors were found.
