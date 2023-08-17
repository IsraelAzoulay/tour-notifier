# Tour Notifier
A simple program to scrape and monitor a webpage for new tour events and send email notifications when new events are found.
The script will continually check the specified webpage for new events every 2 seconds and send an email notification if a new event is found.

## Setup
1. Ensure you have Python installed.
2. Install required packages:
   pip install requests selectorlib python-dotenv
3. Set up your `.env` file with your Gmail credentials and the receiver's email:
  SENDER_EMAIL=your_email@gmail.com
  SENDER_PASSWORD=your_app_password
  RECEIVER_EMAIL=receiver_email@gmail.com

## Usage
Run the script:
python main.py
