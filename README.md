
This project is a UI automation testing suite using Playwright to test the e-commerce website SauceDemo.

📁 Features Covered:
✅ Login with valid and locked-out users
✅ Add products to cart
✅ Remove items from cart
✅ Sort products by name and price
✅ Complete checkout using fake data
✅ Tests run on Chromium, Firefox, and WebKit

🚀 How to Run the Tests
Install dependencies:


npm install
Run all tests on all browsers:

npx playwright test
Run tests in headed mode:

npx playwright test --headed
View the test report:

npx playwright show-report
🧩 Project Structure
tests/: Contains all test files

pages/: Page Object Model (POM) files

utils/: Support functions like data generators

playwright.config.ts: Configuration settings

💡 Notes
Login session is managed using storageState.json

Random data is generated using faker in checkout tests

Sorting and cart logic are validated using Playwright assertions

