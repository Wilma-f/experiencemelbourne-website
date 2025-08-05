# 1. Validation Testing

Testing to ensure that a web page's code meets specified requirements and industry standards. It helps to verify that the code is free from syntax errors, well-structured, and the web pages display correctly and function well across different browsers.

**Test Execution Schedule**  
Start Date: 1/09/2024  
End Date: 1/09/2024  

## Test Case 1: HTML Validation

**Objective**: Check that HTML files pass W3C validation.

**Description**: Verify that all HTML files (`index.html`, `photo.html`, `about.html`, `contact.html`) pass validation checks for unclosed tags, improper nesting, and attribute syntax errors.

**Steps to Execute**:
1. Go to the W3C Markup Validation Service: [https://validator.w3.org/](https://validator.w3.org/)
2. Upload the HTML files for validation.
3. Click **Check**.
4. Review the results.
5. Fix any errors and revalidate.

**Expected Result**: All HTML files meet W3C standards with no errors.  
**Test Data**: All HTML files: `index.html`, `photo.html`, `about.html`, `contact.html`

---

## Test Case 2: CSS Validation

**Objective**: Check that CSS files pass W3C validation for proper syntax, selectors, and duplicate code.

**Description**: Verify that all CSS files (`general.css`, `header.css`, `footer.css`, `index.css`, `photo.css`, `about.css`, `contact.css`) pass validation.

**Steps to Execute**:
1. Go to the W3C CSS Validator: [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)
2. Upload the CSS files for validation.
3. Click **Check**.
4. Review the results.
5. Fix any errors and recheck.

**Expected Result**: All CSS files meet W3C standards and have no errors.  
**Test Data**: All CSS files

---

# 2. Accessibility Testing

Testing to ensure the website is usable by people with disabilities (visual, physical, cognitive). Auditory testing excluded as there is no audio content.

**Test Execution Schedule**  
Start Date: 2/09/2024  
End Date: 2/09/2024  

## Test Case 3: Alt Text, Colour Contrast, Content Understandability, Navigation

**Description**: Use WAVE tool to check alt attributes, colour contrast, content clarity, and navigation.

**Steps to Execute**:
1. Go to [https://wave.webaim.org](https://wave.webaim.org)
2. Install the WAVE browser extension.
3. Open each webpage and activate the extension.
4. Review:
   - Alt text on images.
   - Text contrast.
   - Content structure.
   - Navigation simplicity.
5. Fix issues and recheck using WAVE.

**Expected Result**:  
- Descriptive alt text for images.  
