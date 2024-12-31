# Simple Rails 8 Email Testing Project

This project demonstrates how to set up and test emails in the development environment using Rails 8.

## About the Project

In Rails 8, you can easily test emails locally without actually sending them, which is great for development purposes. This project uses the `letter_opener` gem, which allows you to preview emails directly in your browser. 

By setting up the mailer configuration and using the `letter_opener` gem, you can quickly see how your emails will look and test email functionality without leaving your development environment.

## How It Works

1. **Mailer Configuration**: The Rails app is set up to use the `letter_opener` gem in the development environment, which opens the email in the browser when an email is sent.
2. **Email Preview**: Emails are not sent out but instead opened in a new tab in your browser, allowing you to view and test email content (such as HTML and plain text versions).
3. **Live Demo**: The process of setting this up and testing emails in Rails 8 is demonstrated in a live session.

## Watch the Live Demo

For a full walkthrough of the setup and demonstration, check out my [live session on YouTube](https://youtube.com/live/QnasM5mYSYg).

## Conclusion

This simple approach helps you easily test and refine your email templates in Rails 8, ensuring that everything looks good before sending real emails. Perfect for developers looking to streamline their email testing process in a local environment.
