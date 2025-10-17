# CAPTCHA Solver Web Application

This is a simple, single-file web application that demonstrates a client-side CAPTCHA verification system. It's built with HTML, Tailwind CSS for styling, and vanilla JavaScript for the logic, all contained within `index.html`.

## Features

*   **Responsive Design:** Optimized for various screen sizes using Tailwind CSS.
*   **Dark Theme:** A modern, eye-friendly dark background with light text.
*   **CAPTCHA Display:** Shows a static CAPTCHA image.
*   **User Input:** An input field for users to enter the CAPTCHA text.
*   **Verification Logic:** Client-side validation against a hardcoded CAPTCHA value.
*   **Clear Feedback:** Displays success or failure messages.
*   **Interactive Button:** A circular "Verify" button with hover effects.

## Project Structure

```
. (project root)
├── index.html
└── image.png
├── README.md
└── LICENSE
```

## Setup and Running

To run this application, you only need a web browser. Follow these steps:

1.  **Save the files:** Download `index.html`, `README.md`, and `LICENSE` into a directory. Ensure the `image.png` file (the CAPTCHA sample image) is also in the **same directory** as `index.html`.
2.  **Open `index.html`:** Double-click on `index.html` in your file explorer, or drag and drop it into any modern web browser (e.g., Chrome, Firefox, Edge, Safari).

The application will load, displaying the CAPTCHA image and an input field. Enter the CAPTCHA text and click the "Verify" button.

## How to Test

1.  **Correct CAPTCHA:** Look at the `image.png` file. The CAPTCHA text is `V4XBG`. Type `V4XBG` (case-insensitive) into the input field and click "Verify". You should see a success message.
2.  **Incorrect CAPTCHA:** Type any other text (e.g., `wrong`) into the input field and click "Verify". You should see a failure message.

## Technology Stack

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS (CDN):** Utility-first CSS framework for responsive and modern styling.
*   **Vanilla JavaScript:** Client-side logic for CAPTCHA verification.

## Customization

*   **CAPTCHA Value:** To change the correct CAPTCHA answer, modify the `correctCaptcha` variable in the JavaScript section of `index.html`.
*   **CAPTCHA Image:** Replace `image.png` with your desired CAPTCHA image. Ensure the filename remains `image.png` or update the `<img>` tag's `src` attribute accordingly.
*   **Styling:** All styling is managed by Tailwind CSS classes directly within the HTML. You can adjust colors, spacing, and layout by modifying these classes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.