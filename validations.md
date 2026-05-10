
## 🧪 Testing & Validation

### ✋ Manual Testing

🔗 Navbar Links:

- All navigation links were manually tested to ensure they work correctly:
- Each link redirects to the correct page
- Active page is highlighted
- Links work on desktop and mobile
- No broken or empty links

🔘 Buttons:

- All buttons across the website were tested:
- Buttons respond on click
- Hover effects work
- Buttons redirect to the correct section/page
- No unresponsive or inactive buttons

☑️ Checklist Functionality

- The checklist on the Contact page was tested to ensure:
- Each checkbox can be selected
- The form only appears after all required boxes are checked
- No checkbox is blocked or unclickable
- The scroll-to-form behavior works correctly

![Manual-Checklist-Testing()](assets/images/validations/manual-testing-checklist.png)

📝 Form Validation

- The contact form was tested to ensure proper validation:
- All fields must be filled (no empty inputs allowed)
- Email field requires @ and .
- Error messages appear when fields are invalid
- Submit button only works when the form is valid
- Confirmation message appears after successful submission

![Manual-NameInput-Testing()](assets/images/validations/manual-testing-form-name.png)

![Manual-Subject-Input-Testing()](assets/images/validations/manual-testing-subject.png)

![Manual-Message-Input()](assets/images/validations/manual-testing-message.png)

📧 Email Format Validation

- The email input was tested with:
- Missing “@” → rejected
- Missing “.” → rejected
- Random text → rejected
- Correct format (example@mail.com) → accepted

![Manual-Checklist-Testing()](assets/images/validations/manual-testing-email.png)

📱 Responsive Testing

- Tested on multiple screen sizes:
- Mobile (375px)
- Tablet (768px)
- Desktop (1920px)
- Navbar, images, text, and layout adjust correctly.
- All HTML and CSS files were tested using official W3C validators.
- Full validation results and screenshots are documented in the validation.me file.
- Performance Testing:
- A Lighthouse audit was performed to review Performance, Accessibility, Best Practices, and SEO.
- All results and notes are included bellow:

### CSS
For validating my style sheet I used a validator from [W3C Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input).
The validation returned no errors, only a few warnings that can be ignored. Please see the results of the validation below. 

[css-file](assets/css/style.css)
![CSS-Validation](assets/images/validations/css.png)

### HTML
I also validated each of my HTML files using the [W3C Validation Service](https://validator.w3.org/#validate_by_input).
There are no erros or warnings on the HTML validations. Below are the validation results for my HTML pages.

#### Home page
[home-page-validation](index.html)
![HTML-Validation-Home()](assets/images/validations/html-home.png)

#### Destinations Page
[destinations-page-validation](destinations.html)
![HTML-Validation-Destinations()](assets/images/validations/html-destinations.png)

#### Culture page
[culture-page-validation](culture.html)
![HTML-Validation-Culture()](assets/images/validations/html-culture.png)

#### Contact Page
[contact-page-validation](index.html)
![HTML-Validation-Contact()](assets/images/validations/html-contact.png)

---
## 📌Lighthouse Testing

Lighthouse is a Chrome tool that analyzes my website’s performance, accessibility, best practices, and SEO, and provides scores and recommendations for improvement.

## ⚡Performance, Accessibility, Best Practices and SEO validations

#### Home - 🖥️Desktop

![Lighthouse Validation - Home Desktop](assets/images/lighthouse/desktop-lighthouse-home.png)

#### Home - 📱Mobile
![Lighthouse Validation - Home Mobile](assets/images/lighthouse/mobile-lighthouse-home.png)

#### Destinations - 🖥️Desktop
![Lighthouse Validation - Destinations Desktop](assets/images/lighthouse/desktop-lighthouse-destinations.png)

#### Destinations - 📱Mobile
![Lighthouse Validation - Destinations Mobile](assets/images/lighthouse/mobile-lighthouse-destinations.png)

#### Culture - 🖥️Desktop
![Lighthouse Validation - Culture Desktop](assets/images/lighthouse/desktop-lighthouse-culture.png)

#### Culture - 📱Mobile
![Lighthouse Validation - Culture Mobile](assets/images/lighthouse/mobile-lighthouse-culture.png)

#### Contact - 🖥️Desktop
![Lighthouse Validation - Contact Desktop](assets/images/lighthouse/desktop-lighthouse-contact.png)

#### Contact - 📱Mobile
![Lighthouse Validation - Contact Mobile](assets/images/lighthouse/mobile-lighthouse-contact.png)
