# rtcamp

# WordPress Contact Form Testing Project

## Overview

This project provides a complete WordPress-style contact form implementation designed for QA testing practice. It includes HTML, CSS, and JavaScript files that simulate a typical WordPress contact form with validation and submission handling.

## Features

- WordPress-inspired UI design
- Form validation for required fields
- Email format validation
- Responsive design for different screen sizes
- Success/error message display
- Simulated form submission handling

## Files Structure

```
wordpress-contact-form-qa/
├── contact-form.html      # Main HTML file
├── styles.css            # CSS stylesheet
└── script.js             # Form validation and handling
```

## Setup Instructions

1. Clone or download the project files
2. Open `contact-form.html` in any modern web browser
3. No server required - works directly from file system

## Testing Scenarios

### Functional Testing
1. Test submission with all valid fields
2. Test submission with missing required fields
3. Test invalid email formats
4. Verify success message appears on valid submission
5. Verify error messages appear for invalid inputs

### UI Testing
1. Verify form layout and styling
2. Test responsive behavior on different screen sizes
3. Check focus states for form elements
4. Verify button hover effects

### Validation Testing
1. Name field - required
2. Email field - required and format validation
3. Message field - required
4. Subject field - optional

## Automated Testing

The project is ready for integration with automated testing tools like:
- Playwright (sample test provided in project documentation)
- Selenium
- Cypress

Sample Playwright test cases are available in the project documentation.

## Defect Reporting

When reporting defects, please include:
1. Browser and version
2. Steps to reproduce
3. Expected behavior
4. Actual behavior
5. Screenshots if applicable

## Contribution Guidelines

1. Fork the repository
2. Create a new branch for your changes
3. Submit a pull request with clear description of changes

## License

This project is open source and available under the MIT License.

## Contact

For questions or suggestions, please open an issue in the project repository.
