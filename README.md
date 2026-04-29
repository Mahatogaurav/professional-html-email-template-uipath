# Professional HTML Email Template for UiPath

A reusable and professional HTML email template designed for UiPath automations.  
This template can be used in **Send Outlook Desktop Mail Message** or other email activities for automated report delivery.

## Features

- Professional corporate design
- Calibri font styling
- Dynamic date and time support
- Ready for UiPath integration
- Clean header, body, and footer layout
- HTML formatted email body

## Use Cases

- Daily reports
- MIS reports
- Dashboard notifications
- Automated client emails
- Internal business communications

## File Structure

Templates/
└── Professional_Email_Template.html

## UiPath Usage

Use the template inside:

- Send Outlook Desktop Mail Message
- Send SMTP Mail Message
- Send Exchange Mail Message

Set:

Body Format = HTML

## Dynamic Variables Example

```vb
Now.ToString("dd MMM yyyy")
Now.ToString("hh:00 tt")
