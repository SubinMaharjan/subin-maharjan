# EmailJS Setup Guide

This guide will help you set up EmailJS to receive contact form messages directly to your Gmail account.

## Step 1: Create EmailJS Account

1. Go to [EmailJS.com](https://www.emailjs.com/)
2. Sign up for a free account
3. Verify your email address

## Step 2: Add Email Service

1. In your EmailJS dashboard, go to **Email Services**
2. Click **Add New Service**
3. Choose **Gmail** as your email service
4. Connect your Gmail account
5. Note down your **Service ID** (you'll need this later)

## Step 3: Create Email Template

1. Go to **Email Templates** in your dashboard
2. Click **Create New Template**
3. Use this template content:

```
Subject: New Contact Form Message - {{subject}}

From: {{from_name}} ({{from_email}})

Message:
{{message}}

---
This message was sent from your portfolio website contact form.
```

4. Save the template and note down your **Template ID**

## Step 4: Get Your Public Key

1. Go to **Account** → **General**
2. Copy your **Public Key**

## Step 5: Update Your Website

Replace the following placeholders in your `script.js` file:

1. Replace `YOUR_PUBLIC_KEY` with your actual public key
2. Replace `YOUR_SERVICE_ID` with your Gmail service ID
3. Replace `YOUR_TEMPLATE_ID` with your template ID

## Step 6: Test the Form

1. Open your website
2. Fill out the contact form
3. Submit the form
4. Check your Gmail inbox for the message

## Example Configuration

After setup, your `script.js` should look like this:

```javascript
// Initialize EmailJS
(function() {
    emailjs.init("your_actual_public_key_here");
})();

// In the contact form handler:
emailjs.sendForm('service_1234567', 'template_abcdefg', this)
```

## Troubleshooting

### Common Issues:

1. **"EmailJS is not defined" error**
   - Make sure you've included the EmailJS script in your HTML
   - Check that the script loads before your custom JavaScript

2. **"Service not found" error**
   - Verify your Service ID is correct
   - Make sure your Gmail service is active

3. **"Template not found" error**
   - Verify your Template ID is correct
   - Make sure your template is published

4. **Emails not received**
   - Check your spam folder
   - Verify your Gmail account is connected properly
   - Check the EmailJS dashboard for error logs

### Testing Steps:

1. Open browser developer tools (F12)
2. Go to Console tab
3. Submit the contact form
4. Look for any error messages
5. Check the Network tab for failed requests

## Security Notes

- Your public key is safe to use in client-side code
- EmailJS handles the email sending securely
- No sensitive information is exposed in the browser
- Rate limiting is applied to prevent spam

## Free Plan Limits

- 200 emails per month
- 2 email services
- 2 email templates
- Perfect for personal portfolio websites

## Upgrade Options

If you need more emails:
- Pro Plan: $15/month for 1,000 emails
- Business Plan: $25/month for 10,000 emails

## Support

- EmailJS Documentation: https://www.emailjs.com/docs/
- EmailJS Support: support@emailjs.com
- Community Forum: https://github.com/emailjs/emailjs-js/issues
