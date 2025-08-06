# Test Cases – Form Validation (Contact Form)

## TC_VAL_01 – Submit empty form
- **Preconditions:** User is on the contact form page.
- **Steps:**
  1. Click "Submit" without entering any data.
- **Expected Result:** Form shows required field validation errors.
- **Actual Result:** [To be filled]
- **Status:** [Pass/Fail]

## TC_VAL_02 – Invalid email format
- **Preconditions:** User is on the contact form page.
- **Steps:**
  1. Enter "test@invalid" in the Email field.
  2. Fill all other fields correctly.
  3. Click "Submit".
- **Expected Result:** Email validation error is displayed.
- **Actual Result:** [To be filled]
- **Status:** [Pass/Fail]

## TC_VAL_03 – Special characters in name field
- **Preconditions:** User is on the contact form page.
- **Steps:**
  1. Enter "@@@@" in the Name field.
  2. Fill all other fields correctly.
  3. Click "Submit".
- **Expected Result:** Validation error or message indicating invalid characters.
- **Actual Result:** [To be filled]
- **Status:** [Pass/Fail]

## TC_VAL_04 – Successful form submission
- **Preconditions:** User is on the contact form page.
- **Steps:**
  1. Enter valid name, email, and message.
  2. Click "Submit".
- **Expected Result:** Success message or redirect appears.
- **Actual Result:** [To be filled]
- **Status:** [Pass/Fail]
