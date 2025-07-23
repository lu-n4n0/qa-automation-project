# Manual Test Cases

---

## TC001 – Valid reservation form submission

### Preconditions
- The user is on the homepage of https://automationintesting.online/

### Steps
1. Fill in the "Name" field with "Lucia"
2. Fill in the "Email" field with "lucia@example.com"
3. Fill in the "Phone" field with "987654321"
4. Select the arrival date (today)
5. Select the departure date (+2 days)
6. Enter "2" for the number of guests
7. Click the "Book" button

### Expected Result
- A confirmation message is displayed
- The form is cleared

### Status
To be tested

---

## TC002 – Email field validation (invalid email)

### Preconditions
- The user is on the homepage

### Steps
1. Fill all fields except the email (example: "lucia" or "lucia@")
2. Click on "Book"

### Expected Result
- An error message is displayed
- The form is not submitted

### Status
To be tested

---

## TC003 – Navigation to backoffice login page

### Preconditions
- The user is on the homepage

### Steps
1. Click on the "Backoffice" link
2. Verify that the login page appears

### Expected Result
- The login page appears with "Username" and "Password" fields

### Status
To be tested
