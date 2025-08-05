
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
- Adequate colour contrast.  
- Clear and navigable content.

**Test Data**: Images, text, navigation content across all pages.

## Test Case 4: Keyboard Navigation

**Tools Used**:  
- Chrome DevTools  
- WAVE extension  
- Manual testing  

**Steps to Execute**:

**Using Chrome DevTools**:
1. Open DevTools (`Ctrl+Shift+I` or `Cmd+Opt+I`).
2. Go to the **Accessibility** tab.
3. Inspect focus indicators.
4. Use `Tab` key to simulate keyboard navigation.

**Using WAVE Extension**:
1. Run WAVE evaluation.
2. Check for focus indicators and keyboard accessibility issues.

**Manual Testing**:
1. Use `Tab` to navigate.
2. Confirm all interactive elements (buttons, links, forms) are accessible and follow logical tab order.

**Expected Result**:  
All interactive elements are reachable and usable with keyboard navigation.  
**Test Data**: Buttons, links, form fields on the website.

---

# 3. Browser Testing

**Description**: Test that the website displays and functions correctly across different browsers and screen sizes.

**Test Execution Schedule**  
Start Date: 3/09/2024  
End Date: 3/09/2024  

## Test Case 5: Browser Compatibility & Responsive Design

**Description**:  
- Check functionality across Chrome, Edge, and Firefox.  
- Verify responsiveness on desktop, tablet, and mobile.

**Steps to Execute**:
1. Start local server (e.g. Live Server in VS Code).
2. Install & launch BrowserStack extension.
3. Test site using the local URL (e.g., `http://localhost:5500`).
4. Test responsiveness on different screen sizes.
5. Perform manual tests on:
   - Navigation menus
   - Forms (submit, input fields)
   - Layout consistency
6. Repeat for each browser.

**Expected Result**:  
Website functions and displays correctly on all tested browsers and screen sizes.  
**Test Data**: Chrome, Firefox, Edge; various screen resolutions.

---

# 4. Test Execution Summary

## 4.1 Validation Testing

**Tools Used**:  
- W3C HTML Validator  
- W3C CSS Validator  

**Results**:

### HTML Validation
**index.html**:
- Errors: Unclosed `<div>`, stray `<footer>`, missing `alt` attributes.  
- **Fixes**: Closed tags, added `alt=""` where necessary.

**photo.html**:
- Error: `<a>` not allowed inside `<ul>`.  
- **Fix**: Removed `<ul>`.

**about.html**:
- Error: Unmatched `</p>` tag.  
- **Fix**: Added matching `<p>`.

**contact.html**:
- Error: `autocomplete` attribute on `<textarea>`.  
- **Fix**: Removed attribute.

### CSS Validation

- `header.css`: `padding` had comma — **Fix**: Removed comma.  
- `index.css`: `margin` comma issue — **Fix**: Removed comma.  
- `about.css`: `font-weight: 400%` — **Fix**: Used valid value (e.g., 400).  
- `contact.css`: Invalid `border` property — **Fix**: Removed line.

---

## 4.2 Accessibility Testing

**Tools Used**:  
- WAVE extension  
- Chrome DevTools  
- Live Server  

**Results**:

- **Empty form label**: False positive (label contains image).  
- **Missing alt text**: Resolved by adding `alt` to footer images.  
- **Low contrast**: Fixed contrast issues on all affected links:
  - Home, Photos, About, Contact
  - Denise Jans, Unsplash

**Keyboard Navigation**:  
- Manually tested — no issues found.
- Tab navigation and focus order worked as expected.

---

# ![Sample Image](https://github.com/user-attachments/assets/eceb25d1-edda-44c2-8dc1-a69faf348702)

---

