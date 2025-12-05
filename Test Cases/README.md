1.**Title:** Add product to cart with selected size

**Description:** Verify the ability to add a product to the cart with the selected size

**Pre-conditions:** 
- User is on the website
- Product page is open

**Post-conditions:** 
- The selected product appears in the cart with all details

**Single parameters:** 
- Size: M

**Steps:**
1. Open the website siteexample.com
2. Select the product size {Size}
3. Click "Add to cart"
4. Check the cart for the added product

**Severity:** Major
**Priority:** High
**Type:** Functional
**Behavior:** Positive

2.**Title:** Search product with correct keyword

**Description:** Verify that products corresponding to the entered keyword are displayed during search

**Pre-conditions:** 
- User is on the homepage

**Post-conditions:** 
- User remains on the search results page

**Single parameters:** 
- Keyword: dress, shoes

**Steps:**
1. Open the website example.com
2. Enter {Keyword} in the search field
3. Click the search button

**Severity:** Minor
**Priority:** Medium
**Type:** Functional
**Behavior:** Positive

3.**Title:** Empty search field

**Description:** Verify that leaving the search field empty does not cause a system error

**Pre-conditions:** 
- User is on the homepage

**Post-conditions:** 
- The results page does not contain any products

**Single parameters:** 
- Keyword: (empty)

**Steps:**
1. Open the website example.com
2. Leave the search field empty
3. Click the search button

**Severity:** Minor
**Priority:** Low
**Type:** Functional
**Behavior:** Negative

4.**Title:** Payment with invalid card

**Description:** Verify that the system correctly detects invalid card information and does not allow the user to complete the payment

**Pre-conditions:** 
- The cart contains at least one product
- User is on the checkout page

**Post-conditions:** 
- The product remains in the cart
- Payment is not completed

**Single parameters:** 
- Card Number: 1234 5678 1234 5678

**Steps:**
1. Open the website example.com
2. Select an item to purchase
3. Enter the card number
4. Fill in other required fields
5. Click "Pay"
6. Check the cart

**Severity:** Critical
**Priority:** High
**Type:** Functional
**Behavior:** Negative

5.**Title:** Change site language to English

**Description:** Verify that changing the website language from Georgian to English works correctly

**Pre-conditions:** 
- User is on the homepage

**Post-conditions:** 
- User remains on the same page, but all text is displayed in English

**Single parameters:** 
- Language: English, Georgian

**Steps:**
1. Open the website example.com
2. Select "English"
3. Verify that all product descriptions are displayed in English

**Severity:** Minor
**Priority:** Low
**Type:** Functional
**Behavior:** Positive

6.**Title:** Registration with invalid email

**Description:** Verify that the system correctly detects invalid email format and does not allow the user to complete registration

**Pre-conditions:** 
- User is on the registration page

**Post-conditions:** 
- User cannot register
- The form remains on the page

**Single parameters:** 
- Email: testexample.com, @example.com

**Steps:**
1. Open the website example.com
2. Open the registration form
3. Enter an invalid email
4. The text is entered in the field, but the format is incorrect
5. Click "Register"

**Severity:** Major
**Priority:** High
**Type:** Functional
**Behavior:** Negative

7.**Title:** Create New Admin with Valid Data

**Description:** Admin can successfully create a new administrator by providing valid and complete data in the Create New Admin form

**Pre-conditions:** 
- Super Admin is logged in
- "Create New Admin" form is open

**Post-conditions:** 
- New admin exists in the Admin List with correct First Name, Last Name, Email, Role, and Active status

**Steps:**
1. Open the site example.com
2. Navigate in the menu to locate “Admins”
3. Click "Create New Admin"
4. Enter admin information
5. Click "Create"

**Severity:** Major
**Priority:** High
**Type:** Functional
**Behavior:** Positive

8.**Title:** Create New Admin with Invalid Data

**Description:** Verifies that the system prevents creating a new admin when invalid or incomplete data is entered. Proper error messages should appear for required fields, email format, password length, and password mismatch

**Pre-conditions:** 
- Admin is logged in

**Post-conditions:** 
- No admin is created

**Steps:**
1. Open the site example.com
2. Navigate in the menu to locate “Admins”
3. Click “Create New Admin”
4. Enter invalid admin information
5. Click "Create"

**Severity:** Major
**Priority:** High
**Type:** Functional
**Behavior:** Negative

9.**Title:** Create New Admin with Partially Filled Form

**Description:** Verifies that submitting a partially completed form does not create a new admin. Missing required fields should trigger proper validation messages

**Pre-conditions:** 
- Admin is logged in

**Post-conditions:** 
- No admin is created

**Steps:**
1. Open the site example.com
2. Navigate in the menu to locate “Admins”
3. Click “Create New Admin”
4. Enter partial admin information
5. Click "Create"

**Severity:** Minor
**Priority:** Medium
**Type:** Functional
**Behavior:** Negative

10.**Title:** Edit an existing admin with invalid information and attempt to save

**Description:** Verifies that the system prevents saving edits if invalid data is entered, such as short password, mismatched Confirm Password, or cleared required fields. Ensures data integrity

**Pre-conditions:** 
- Admin is logged in

**Post-conditions:** 
- Admin record is not updated
- Proper error messages are displayed for invalid fields

**Steps:**
1. Open the website example.com
2. Navigate in the menu to locate “Admins”
3. Open Admin List → Select admin → Click "Edit"
4. Enter invalid data
5. Click "Save"

**Severity:** Major
**Priority:** High
**Type:** Functional
**Behavior:** Negative

11.**Title:** Verify admin appears in Admin List after creation with correct role and status

**Description:** Verifies that after creating a new admin with valid data, the admin appears in Admin List with the correct role and Active status

**Pre-conditions:** 
- Admin is logged in

**Post-conditions:** 
- New admin exists in Admin List

**Steps:**
1. Open the site example.com
2. Navigate to “Admins” in the menu
3. Verify that the newly created admin appears in the list with correct role and Active status

**Severity:** Major
**Priority:** High
**Type:** Functional
**Behavior:** Positive

12.**Title:** Create a new admin with empty required fields

**Description:** Verifies that the system prevents creating a new admin when required fields are left empty

**Pre-conditions:** 
- Admin is logged in

**Post-conditions:** 
- No admin is created

**Steps:**
1. Open the site example.com
2. Navigate to “Admins” in the menu
3. Click “Create New Admin”
4. Leave all required fields empty
5. Click "Create"

**Severity:** Major
**Priority:** High
**Type:** Functional
**Behavior:** positive

13.**Title:** Create a new admin with invalid email format

**Description:** Verifies that the system prevents creating a new admin with an invalid email format

**Pre-conditions:** 
- Admin is logged in

**Post-conditions:** 
- Admin record is not created
- Proper error message is displayed for invalid email

**Steps:**
1. Open the site example.com
2. Navigate to “Admins” in the menu
3. Click “Create New Admin”
4. Enter invalid email (e.g. "admin@domain.com) and fill other required fields
5. Click "Create"

**Severity:** Major
**Priority:** High
**Type:** Functional
**Behavior:** Negative

14.**Title:** Create a new admin and leave role unselected

**Description:** Verifies that the system prevents creating a new admin without selecting a role

**Pre-conditions:** 
- Admin is logged in

**Post-conditions:** 
- Admin record is not created
- Proper validation message is displayed for missing role

**Steps:**
1. Open the site example.com
2. Navigate to “Admins” in the menu
3. Click “Create New Admin”
4. Fill all fields except Role
5. Click "Create"

**Severity:** Major
**Priority:** High
**Type:** Functional
**Behavior:** Negative

15.**Title:** Verify system behavior when registering with an invalid email

**Scenario:** User tries to sign up with an invalid email address

**Description:**
Given the user is logged out and on the Sign Up page  
When the user enters an invalid email (e.g., mail@34mail.ru)  
And fills in other required fields  
And clicks the "Sign Up" button  
Then the system should display a validation message: "Please enter a valid email address"  
And the user should not be redirected to the Verify PIN Code page  
And no account should be created

**Status:** Failed

**Severity:** Major  
**Priority:** High

16.**Title:** Verify correct section loads when clicking “About” and “How it works?” in navigation menu

**Scenario:** User clicks “About” and “How it works?” buttons

**Description:**
Given the user is on the homepage and the navigation menu is visible  
When the user clicks the “About” button  
Then the second section should be displayed  

When the user clicks the “How it works?” button  
Then the third section should be displayed

**Status:** Failed

**Severity:** Medium  
**Priority:** Medium

17.**Title:** Verify image is created in 1:1 aspect ratio

**Scenario:** User creates an image in 1:1 aspect ratio

**Description:**
Given the user is on the image creation page and size options are visible  
When the user selects the 1:1 aspect ratio (square format)  
And generates the image  
Then the system should produce an image with equal width and height  
And the image should not appear stretched, cropped, or distorted

**Status:** Passed

**Severity:** Major  
**Priority:** High

18.**Title:** Verify image is created in 16:9 aspect ratio

**Scenario:** User creates an image in 16:9 aspect ratio

**Description:**
Given the user is on the image creation page with size options available  
When the user selects the 16:9 aspect ratio  
And generates the image  
Then the system should create an image where width and height match the 16:9 ratio  
And the image should appear without any stretching, cropping, or distortion

**Status:** Passed

**Severity:** Major  
**Priority:** High

19.**Title:** Verify image is created in 9:16 aspect ratio

**Scenario:** User creates an image in 9:16 aspect ratio

**Description:**
Given the user is on the image creation page and aspect ratio options are displayed  
When the user selects the 9:16 aspect ratio  
And generates the image  
Then the system should create an image where height is greater than width in a 9:16 ratio  
And the image should not be stretched, cropped, or distorted

**Status:** Passed

**Severity:** Major  
**Priority:** High

20.**Title:** Remove Background from Image

**Scenario:** Removing background from an image

**Description:**
Given an image is open in the editor  
When the user clicks “Remove Background”  
Then the system should remove the background  
And leave the main object visible and clean

**Status:** Passed

**Severity:** Major  
**Priority:** High

21.**Title:** Change background when user types a description

**Scenario:** Background change fails when using text description

**Description:**
Given an image is open in the editor  
When the user selects “Change Background”  
And types “make background home” in the description field  
Then the background should change to a home setting  
But the system changes the background to something else, not a home background

**Status:** Failed

**Severity:** Major  
**Priority:** High

22.**Title:** Verify user can view image in History

**Scenario:** User views image edit history

**Description:**
Given the user has made multiple edits to an image  
When the user opens the History panel  
Then all past edits should be displayed in chronological order  
And the user can see details of each edit without restoring

**Status:** Passed

**Severity:** Major  
**Priority:** High

23.**Title:** Verify AI Prediction detects AI-generated text

**Scenario:** Detect AI-generated text

**Description:**
Given the user has a text generated by AI  
When the user pastes it into the “Paste your text here” field  
And clicks to scan  
Then the system should identify the text as AI-generated  
And display a likelihood score or label

**Status:** Passed

**Severity:** Major  
**Priority:** High

24.**Title:** AI Prediction does not process text under 500 words

**Scenario:** Prevent AI Prediction on short text

**Description:**
Given the user has a text of fewer than 500 words  
When the user pastes it into the “Paste your text here” field  
And clicks to scan  
Then the system should not generate AI prediction  
And should display a message indicating the minimum word requirement

**Status:** Failed

**Severity:** Major  
**Priority:** High

25.**Title:** Verify AI Prediction scans uploaded files

**Scenario:** AI Prediction fails to scan uploaded file

**Description:**
Given the user has a valid text file  
When the user uploads the file in the File Upload section  
And clicks Scan  
Then the system should scan the file  
And display whether the text was written by AI or a human  
But currently the system does not scan the file and provides no result

**Status:** Failed

**Severity:** Major  
**Priority:** High

26.**Title:** AI Plagiarism Check Using Directly Copied Wikipedia Content

**Scenario:** Detect 100% plagiarism on fully copied Wikipedia text

**Description:**
Given the user opens the AI Plagiarism Scanner  
And user has copied an unmodified paragraph from the Wikipedia “Georgia” article  
When the user pastes the text into the plagiarism input field  
And clicks the “Scan” button  
Then the system should return a plagiarism score of 100%  
And the system should highlight exact matches

**Status:** Passed

**Severity:** Major  
**Priority:** High
