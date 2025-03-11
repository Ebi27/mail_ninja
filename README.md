# mail_ninja 🚀  
**Automate Your Email Management with Python**

I was tired of having 5000 unread emails with a bulk of them being promotional emails and decided to do something about it.
**Mail Ninja** is a collection of Python scripts designed to help me take control of my email by automating repetitive 
tasks like sorting, deleting, and unsubscribing from unwanted emails.

With **InboxNinja**, you can:
- **Delete emails** from specific folders (e.g., Social, Promotions).
- **Unsubscribe** from non-essential newsletters and marketing emails.
- **Keep your inbox clean** and focused on what matters.


## Features
- **Gmail API Integration**: Securely connects to your Gmail account to manage emails programmatically.
- **Folder-Specific Deletion**: Automatically deletes emails from folders like "Social" and "Promotions."
- **Unsubscribe Automation**: Identifies and processes unsubscribe links in emails.
- **Customizable**: Easily adapt the scripts to fit your specific needs.

---

## How It Works
1. **Authenticate**: Uses OAuth 2.0 to securely connect to your Gmail account.
2. **Delete Emails**: Clears out emails from specified folders (e.g., Social, Promotions).
3. **Unsubscribe**: Scans emails for unsubscribe links and helps you opt out of unwanted subscriptions.

---

## Getting Started

### Prerequisites
- Python 3.x installed.
- A Gmail account.
- Gmail API enabled in the [Google Cloud Console](https://console.cloud.google.com/).

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Ebi27/mail_ninja.git
   cd mail_ninja