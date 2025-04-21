# Financial Data Transfer Landing Page

A modern, elegant landing page for securely transferring financial data through a webhook.

## Features

- Modern, finance-themed UI with dark blue color palette and light blue glowing accents
- Drag and drop file upload functionality
- Text message input for additional notes
- Secure data transfer via webhook
- Responsive design that works on all devices

## Usage

1. Drag and drop files into the designated area or click to select files
2. Add any additional notes or message in the text area
3. Click "Submit Securely" to send the data to the webhook

## Technical Details

The application sends data to the webhook URL using an HTTP GET request with the following parameters:
- `message`: The text entered in the message field
- `files`: The names of the uploaded files (one parameter per file)

## Setup

Simply host the HTML file on any web server or open it directly in a browser.

## License

MIT