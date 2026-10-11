SUNNY CREATIONS WEBSITE — SETUP GUIDE

FILES
- index.html: all page content and booking form
- style.css: responsive dark navy + gold design
- script.js: mobile menu and booking interactions

IMPORTANT: EMAIL BOOKING SETUP
This is a static website. It does not include online payments or order tracking, as requested.
The booking form uses FormSubmit as a simple email-form service.

1. Open index.html in a code editor.
2. Find this line:
   action="https://formsubmit.co/YOUR_EMAIL@example.com"
3. Replace YOUR_EMAIL@example.com with the email address where you want booking requests delivered.
   Example format: action="https://formsubmit.co/you@example.com"
4. Save and upload all three files to your web hosting.
5. Submit one test booking from the live website.
6. FormSubmit may send a verification email to your inbox the first time. Open it and verify the email address.
7. Test again and check inbox/spam.

The form will send the client name, email, service, budget, deadline, brand name, project details, reference link and consent field.
The client can provide a reference URL, but this version does not upload attachments.

IMAGE / PORTFOLIO NOTES
The large artwork and portfolio samples are made from HTML/CSS shapes, so they do not rely on missing image files. The portfolio samples are placeholders; replace them with your own work before publishing.

SECURITY / PRIVACY
- Do not put email passwords or secret API keys in HTML or JavaScript.
- Use HTTPS on your live website.
- Add your own Privacy Policy, Terms and Refund/Revision Policy before accepting real client bookings.
- Avoid collecting sensitive personal information.
- FormSubmit is a third-party service; review its current terms and privacy practices before use.
- This basic static version has no order tracking, customer accounts, admin dashboard, online payment, file uploads or spam-proof server-side validation.

LOCAL PREVIEW
Open index.html in a browser. Some email form functionality only works after replacing the email, deploying the website and completing FormSubmit's verification.
