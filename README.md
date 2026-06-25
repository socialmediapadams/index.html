# Mediclaim Coverage Survey Form

A responsive HTML-based Mediclaim Coverage Survey Form for employee insurance enrollment. The form collects employee details, dependent information, and employee consent before submission to Google Apps Script.

## Features

* Responsive and mobile-friendly design
* Clean HR-themed user interface
* Employee Information section
* Dynamic Dependent Management
* Maximum 7 dependents allowed
* Relationship-based dependent details
* Date of Birth fields with proper date validation
* Gender options:

  * Male
  * Female
  * Not to say
* Mandatory Employee Declaration & Consent
* Google Apps Script integration for data submission
* Form validation and error handling
* Success and error notifications

## Form Sections

### Employee Information

* Full Name (as per Aadhaar)
* Employee Code
* Date of Birth
* Gender

### Dependents

Employees can add up to 7 dependents.

Supported relationships:

* Husband
* Wife
* Son
* Daughter
* Father
* Mother
* Father-in-law
* Mother-in-law

For each dependent:

* Full Name
* Date of Birth
* Gender

### Declaration & Consent

Employees must accept the declaration before submitting the form.

## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* Google Apps Script (Backend)

## Configuration

Open `index.html` and update the following variable with your deployed Google Apps Script Web App URL:

```javascript
var SCRIPT_URL = "YOUR_GOOGLE_APPS_SCRIPT_WEB_APP_URL";
```

## Deployment

### GitHub Pages

1. Upload `index.html` to your GitHub repository.

2. Commit and push the changes.

3. Go to:

   Settings → Pages

4. Select:

   * Branch: `main`
   * Folder: `/root`

5. Save changes.

Your form will be available at:

```text
https://your-username.github.io/repository-name/
```

## Validation Rules

* All employee fields are mandatory.
* Consent checkbox is mandatory.
* Maximum 7 dependents allowed.
* Date fields use standard HTML date validation.
* Form submission is blocked until validation passes.

## Project Structure

```text
project/
│
├── index.html
└── README.md
```

## License

Internal HR use for employee Mediclaim enrollment and survey collection.
