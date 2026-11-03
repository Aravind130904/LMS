# IRP LMS — Responsive front-end recreation

A responsive three-page recreation of the supplied IRP LMS reference screenshots using semantic HTML5 and CSS3.

## Project files
- `index.html` — Home page and five-step learning journey.
- `style-home.css` — Home page styles.
- `courses.html` — Courses page with nine embedded YouTube videos.
- `style-courses.css` — Courses page styles.
- `contact.html` — Contact details and responsive message form.
- `style-contact.css` — Contact page styles.
- `assets/home-hero.png` — Original generated hero illustration.

Each page has its own stylesheet. No JavaScript or build tools are required.

## Run locally
1. Extract the ZIP.
2. Open the folder in VS Code.
3. Open `index.html` in a browser, or use the Live Server extension.
4. Use the navigation to visit Courses and Contact Us.

## Contact form setup
The contact form uses native browser validation and FormSubmit to deliver messages without building a backend.
1. Deploy the website publicly.
2. Submit the contact form once using a real test message.
3. Check the inbox for `support@irplms.com` and confirm FormSubmit's activation email.
4. After confirmation, form submissions will be delivered to that address.

The first activation is required by FormSubmit. If you use another recipient email, change the form action in `contact.html` to `https://formsubmit.co/YOUR_EMAIL_ADDRESS`.

## Publish on GitHub Pages
1. Create a **public** GitHub repository.
2. Upload all HTML files, all three CSS files, `README.md`, and the `assets` folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to provide the public website URL.

## Responsive layout
The pages include desktop, tablet, and mobile breakpoints. The navigation collapses into a CSS-only mobile menu; cards and the contact form reflow to fit narrow screens without horizontal scrolling.

## Notes
- The course videos are YouTube embeds and require an internet connection.
- Hosted logo and banner image URLs supplied in the assignment are used on the relevant pages.
- The contact form uses FormSubmit, an external hosted form service. No custom backend or JavaScript is included.
