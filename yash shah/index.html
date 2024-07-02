const puppeteer = require('puppeteer');

(async () => {
  const browser = await puppeteer.launch({ headless: false }); // Set headless to true if you don't need to see the browser
  const page = await browser.newPage();

  // Navigate to Twitter login page
  await page.goto('https://twitter.com/login');

  // Wait for the username field and enter the username
  await page.waitForSelector('input[name="session[username_or_email]"]');
  await page.type('input[name="session[username_or_email]"]', 'your_username');

  // Wait for the password field and enter the password
  await page.waitForSelector('input[name="session[password]"]');
  await page.type('input[name="session[password]"]', 'your_password');

  // Click the login button
  await page.click('div[data-testid="LoginForm_Login_Button"]');

  // Wait for navigation to the home page
  await page.waitForNavigation();

  console.log('Logged in successfully');

  // Close the browser
  await browser.close();
})();