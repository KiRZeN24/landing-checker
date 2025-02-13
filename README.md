# Landing Checker

This project aims to automate the testing of a landing page by verifying several key elements on the website. It focuses on checking that the banner, the privacy policy links, the proper display of courses, the functionality of the course links, and the ability to complete an enrollment form are all working correctly.

## Features

- **Banner verification**: Checks that the landing page banner is visible.
- **Link verification**: Verifies that the privacy policy links are available and working properly.
- **Course display**: Ensures that the courses are listed and visible on the page.
- **Course links**: Checks that the course links redirect correctly to the corresponding pages.
- **Enrollment form**: Automatically fills out and submits an enrollment form to verify its functionality.

## Requirements

To run this project, you will need to have the following programs and tools installed:

- Node.js
- pnpm (package manager)
- Playwright
- A browser (preferably Chrome or Firefox)

## Installation

1. Clone this repository:


   ```bash
   git clone https://github.com/KiRZeN24/landing-checker.git
   ```
2. Navigate to the project directory:

    ```bash
    cd landing-checker
    ```
3. Install the dependencies using pnpm:

    ```bash
    pnpm install
    ```

4. Install the necessary browsers for Playwright:

    ```bash
    pnpm exec playwright install
    ```

## Usage

To run the landing page checks, use the following command:

    
    pnpm start
    
This command will open a browser and perform the automatic checks for the following aspects:

    1. Banner verification.
    2. Checking the privacy policy links.
    3. Display of courses.
    4. Functionality of the course links.
    5. Filling out and submitting the enrollment form.

## Contributions

Contributions are welcome. If you have any improvements or fixes, please open a pull request or create an issue to discuss the changes.