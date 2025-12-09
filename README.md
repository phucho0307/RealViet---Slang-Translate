# RealViet---Slang-Translate
A website for international students to know and love the real culture of Vietnamese greeting

## Contact Form Setup

To receive messages from the contact page:

1. Sign up for a free EmailJS account at https://www.emailjs.com/
2. Add an Email Service (Gmail, Outlook, etc.)
3. Create an Email Template with these variables:
   - `{{from_name}}` - Instagram username
   - `{{message}}` - User's message
   - `{{reply_to}}` - Instagram username (optional)
4. Get your credentials from EmailJS dashboard:
   - Public Key (Account → API Keys)
   - Service ID (Email Services)
   - Template ID (Email Templates)
5. Replace the placeholders in `contact.html`:
   - `YOUR_PUBLIC_KEY` → Your Public Key
   - `YOUR_SERVICE_ID` → Your Service ID
   - `YOUR_TEMPLATE_ID` → Your Template ID

After setup, form submissions will be sent directly to your email!