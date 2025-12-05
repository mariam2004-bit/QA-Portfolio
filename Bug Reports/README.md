1.**Title:** Registration succeeds with invalid email

**Body:**
**Priority:** High
**Severity:** Medium
**Description:** Testing that registration should not succeed if a user enters an invalid email.

**Preconditions:**
- User is on the registration page of example.com
- Internet connection is stable
- Registration form is fully loaded
- User is not logged in

**Steps to Reproduce:**
1. Open the website example.com
2. Enter an invalid email, e.g.: kharab123@gmail.com
3. Fill the remaining fields with valid data
4. Click the "Register" button

**Expected Result:** The system should display the message "Invalid email format" and registration should not complete.

**Actual Result:** The system completes registration and the user is registered with an invalid email.

**Test Environment:**
- Laptop: Acer Travel Mate B-118-M
- Operating System: Microsoft Windows 10 Pro Education
- Browser: Version 140.0.3485.94 (Official build) (64-bit)
- Frequency: 100%

2.**Title:** "Description" field missing in address creation form

**Body:**
**Priority:** High
**Severity:** Major
**Description:** The address creation form does not include a "Description" field, preventing the user from entering additional information for the address.

**Preconditions:**
- User is logged in
- Shopping cart contains at least one item
- User is on the checkout page

**Steps to Reproduce:**
1. Open the website example.com
2. Choose an item
3. Start Checkout
4. Select "Address"
5. Select "Add new Address"

**Expected Result:** The form should include a "Description" text area field according to the design.

**Actual Result:** The "Description" field is missing in the address creation form, and the user cannot enter any additional information.

**Test Environment:**
- Device: Samsung Galaxy S23 FE
- Operating System: Android
- Browser: Google Chrome
- Reproducibility Rate: 100%
- Environment: Development

3.**Title:** Incorrect Label: “Play Later” Instead of “Buy in Installment”

**Body:**
**Priority:** High
**Severity:** Major
**Description:** The payment option is incorrectly labeled as “Play Later” instead of “Buy in Installment”.

**Preconditions:**
- User is logged in
- Shopping cart contains at least one item
- User is on the checkout page

**Steps to Reproduce:**
1. Open the website example.com
2. Choose an item
3. Start Checkout
4. Navigate to "Payment"

**Expected Result:** The payment option should be labeled as “Buy in Installment”.

**Actual Result:** The installment option is labeled as “Play Later”.

**Test Environment:**
- Device: Samsung Galaxy S23 FE
- Operating System: Android
- Browser: Google Chrome
- Reproducibility Rate: 100%
-  Environment: Development

4.**Title:** Clicking "Gift card" redirects to Home page

**Body:**
**Priority:** High
**Severity:** Major
**Description:** Clicking on the "Gift card" button incorrectly redirects the user to the Home page instead of the Gift Card page.

**Preconditions:**
- User is on the homepage of example.com
- User is logged in 

**Steps to Reproduce:**
1. Open the website example.com
2. Click on the "Gift card" button
3. Observe the page redirection

**Expected Result:** The user should be navigated to the Gift Card page.

**Actual Result:** The user is redirected to the Home page.

**Test Environment:**
- Device: Acer Travel Mate B-118-M
- Operating System: Microsoft Windows 10 Pro Education
- Browser: Microsoft Edge Version 142.0.3595.53 (Official build) (64-bit)
- Reproducibility Rate: 100%
-  Environment: Development

5.**Title:** Incorrect Label: “Promo Code & Gift Card” Instead of “Gift & Voucher”

**Body:**
**Priority:** High
**Severity:** Major
**Description:** The label is incorrectly displayed as “Promo Code & Gift Card” instead of the expected “Gift & Voucher”, which does not match the design and business terminology.

**Preconditions:**
- User is logged in
- Shopping cart contains at least one item
- User is on the checkout page

**Steps to Reproduce:**
1. Open the website example.com
2. Choose an item
3. Start Checkout

**Expected Result:** The label should be “Gift & Voucher” according to the design and business terminology.

**Actual Result:** The label is displayed as “Promo Code & Gift Card” instead of the expected term.

**Test Environment:**
- Device: Samsung Galaxy S23 FE
- Operating System: Android
- Browser: Google Chrome
- Reproducibility Rate: 100%
-  Environment: Development

6.**Title:** Incorrect Label: “Delivery Information” Instead of “Delivery Details”

**Body:**
**Priority:** High
**Severity:** Major
**Description:** The delivery section label is incorrectly displayed as “Delivery Information” instead of the expected “Delivery Details”.

**Preconditions:**
- User is logged in
- Shopping cart contains at least one item
- User is on the checkout page

**Steps to Reproduce:**
1. Open the website example.com
2. Select an item
3. Start Checkout

**Expected Result:** The section title should be “Delivery Details”.

**Actual Result:** The label is displayed as “Delivery Information”.

**Test Environment:**
- Device: Samsung Galaxy S23 FE
- Operating System: Android
- Browser: Google Chrome
- Reproducibility Rate: 100%
-  Environment: Development

7.**Title:** Missing “Try On” Option in “Delivery Information” Section

**Body:**
**Priority:** High
**Severity:** Major
**Description:** The “Try On” delivery option is missing in the Delivery Information section, preventing users from selecting this delivery method.

**Preconditions:**
- User is logged in
- Shopping cart contains at least one item
- User is on the checkout page

**Steps to Reproduce:**
1. Open the website example.com
2. Choose an item
3. Navigate to Kart
4. Start Checkout
5. Choose “Delivery Information”

**Expected Result:** The Delivery Information section should list all delivery methods, including: “Try On”.

**Actual Result:** The “Try On” delivery option is missing.

**Test Environment:**
- Device: Samsung Galaxy S23 FE
- Operating System: Android
- Browser: Google Chrome
- Reproducibility Rate: 100%
-  Environment: Development

8.**Title:** Search bar doesn’t return results for entered keywords in any language

**Body:**
**Priority:** Low
**Severity:** Major
**Description:** The search bar does not return any results regardless of the entered keyword or language.

**Preconditions:**
- User is on the website example.com
- User is logged in 

**Steps to Reproduce:**
1. Open the website example.com
2. Click on the search icon
3. Enter “dress” or “კაბა” in the search field
4. Observe the search results

**Expected Result:** Search results related to the entered keyword should be displayed.

**Actual Result:** No search results are displayed for any word in any language.

**Test Environment:**
- Devices: Windows 10 Pro Education (Laptop), Samsung Galaxy S23 FE, Acer Travel Mate B118-M
- Operating Systems: Android, Windows 10 Pro Education
- Browsers: Google Chrome, Microsoft Edge Version 142.0.3595.53 (Official build) (64-bit)
- Reproducibility Rate: 100%
- Environment: Production

9.**Title:** Language changes automatically after page refresh

**Body:**
**Priority:** High
**Severity:** Major
**Description:** The website does not retain the user-selected language after a page refresh, causing a mismatch with the chosen language.

**Preconditions:**
- User is on the website example.com
- User is logged in 

**Steps to Reproduce:**
1. Open the website example.com
2. Select a language different from the default (e.g., English)
3. Refresh the page

**Expected Result:** The website should retain the user-selected language after the page refresh.

**Actual Result:** The website reverts to a language that was not selected by the user.

**Test Environment:**
- Device: Acer Travel Mate B-118-M
- Operating System: Microsoft Windows 10 Pro Education
- Browser: Microsoft Edge Version 142.0.3595.53 (Official build) (64-bit)
- Reproducibility Rate: 100%
- Environment: Production

10.**Title:** Low contrast on “Cart” button text

**Body:**
**Priority:** High
**Severity:** Major
**Description:** The text on the “Cart” button has very low contrast, making it difficult to read for users with low vision.

**Preconditions:**
- User is on the website example.com
- User is logged in 

**Steps to Reproduce:**
1. Open the website example.com
2. Use Wave Accessibility Tool to inspect contrast
3. Locate the “Cart” button on the main page

**Expected Result:** Text on the button should have adequate contrast ratio (at least 4.5:1 for normal text) to ensure readability for all users.

**Actual Result:** Contrast ratio is very low (2.29:1), making text difficult to read, especially for users with low vision.

**Test Environment:**
- Device: Acer Travel Mate B-118-M
- Operating System: Microsoft Windows 10 Pro Education
- Browser: Microsoft Edge Version 142.0.3595.53 (Official build) (64-bit)
- Reproducibility Rate: 100%
- Environment: Production

11.**Title:** Call-to-action buttons are not visually highlighted enough

**Body:**
**Priority:** Medium
**Severity:** Medium
**Description:** The “Sign In” and “Register” buttons do not stand out visually. Their color and size do not attract user attention, making them easy to miss.

**Preconditions:**
- User is on the website example.com
- User is logged in 

**Steps to Reproduce:**
1. Open the website example.com
2. Observe the “Sign In” and “Register” buttons in the top-right corner

**Expected Result:** Call-to-action buttons should be visually distinctive and clearly highlighted.

**Actual Result:** Buttons are a different color but are not visually emphasized and blend into the navigation.

**Test Environment:**
- Device: Laptop, Acer Travel Mate B-118-M
- Operating System: Microsoft Windows 10 Pro Education
- Browser: Brave 1.81.135 (Official Build) (64-bit)
- Reproducibility Rate: 100%

12.**Title:** Price tags overlap with template images

**Body:**
**Priority:** Medium
**Severity:** Medium
**Description:** Price tags overlap with image content or text, making the design cluttered and hard to read.

**Preconditions:**
- User is on the website example.com
- User is logged in 

**Steps to Reproduce:**
1. Open the website example.com
2. Select "Templates" from the navigation bar
3. Check the price tags on template cards

**Expected Result:** Price tags should be clearly visible without covering image or text.

**Actual Result:** Tags overlap images and text in some cards.

**Test Environment:**
- Device: Laptop, Acer Travel Mate B-118-M
- Operating System: Microsoft Windows 10 Pro Education
- Browser: Brave 1.81.135 (Official Build) (64-bit)
- Reproducibility Rate: 100%

13.**Title:** Navigation bar elements are poorly organized

**Body:**
**Priority:** Medium
**Severity:** Medium
**Description:** Elements in the navigation bar are unevenly spaced and not visually balanced. Buttons have inconsistent sizes, making it unclear which is the primary action.

**Preconditions:**
- User is on the website example.com
- User is logged in

**Steps to Reproduce:**
1. Open the website example.com
2. Observe the navigation bar at the top of the page

**Expected Result:** Navigation bar elements should be evenly spaced and visually aligned.

**Actual Result:** Elements are misaligned and look unbalanced.

**Test Environment:**
- Device: Laptop, Acer Travel Mate B-118-M
- Operating System: Microsoft Windows 10 Pro Education
- Browser: Brave 1.81.135 (Official Build) (64-bit)
- Reproducibility Rate: 100%
