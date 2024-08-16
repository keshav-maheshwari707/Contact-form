# Contact Form

A responsive contact form built using HTML and CSS with email functionality powered by the Web3Forms API.

## Features

- Responsive Design: The form is fully responsive and works well on all devices, including mobile and desktop.
- Email Integration: Uses the Web3Forms API to send form submissions directly to owner's email.
- User-Friendly Interface: Simple and clean design to provide a smooth user experience.

## Technologies Used

- HTML: Markup for the form structure.
- CSS: Styling for the form, including responsiveness.
- Web3Forms API: Backend service for handling email submissions.

## How It Works

1. User Input: Users fill out the form with their name, email and message.
2. Form Submission: When the user submits the form, the data is sent to Web3Forms.
3. Email Notification: The form data is then sent directly to owner's email address.

## Setup

To use this form in your project:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/contact-form.git
   ```

2. Update the form's `action` attribute with your Web3Forms endpoint:

   ```html
   <form action="https://api.web3forms.com/your-web3forms-endpoint" method="POST">
   ```

3. Customize the form fields and styling as needed.

## Live Demo

Check out the live demo [https://keshav-maheshwari707.github.io/Contact-form/].
