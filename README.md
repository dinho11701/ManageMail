# Email Management Automation

This project provides an automated solution for managing emails using Python, specifically focusing on connecting to an email server via IMAP and processing emails to remove spam. It's designed with modularity in mind, allowing for easy expansion or modification of the email handling logic.

## Features

- **IMAP Connection**: Establishes a secure connection to an IMAP server to interact with the email account.
- **Spam Management**: Identifies and deletes emails that are marked as spam based on predefined criteria.
- **CI/CD Integration**: Utilizes Continuous Integration and Continuous Deployment to ensure the quality and reliability of the application.

## Getting Started

These instructions will guide you on how to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need Python 3.8 or higher, and pip installed on your system. Optionally, for contributing or deploying, familiarity with Git and GitHub Actions is advantageous.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/email-management-automation.git
   cd email-management-automation

2. Install required packages

   pip install imaplib email pytest

3. Configuration
Create a .env file in the root directory and add the following environment variables to configure your email server and authentication details:
