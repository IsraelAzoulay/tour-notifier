## EventEagleEye

### Description:
A Python-based application designed to periodically scan a specific website for new tour event announcements. Upon detecting a new event that hasn't been previously recorded, the system sends an email notification and saves the event for future reference.

### Features:
- Automated web scraping of a target URL for event data.
- Detection of new tour events based on historical data.
- Email notifications upon detecting new events.
- Persistent storage of detected events.

### Technologies Used:
- **Python**
- **Requests**: For making HTTP requests.
- **Selectorlib**: For data extraction from web pages.
- **smtplib & ssl**: For sending email notifications.
- **os & python-dotenv**: For environment variable management.

### How to Use:
1. Ensure you have Python installed on your machine.
2. Clone the repository: git clone https://github.com/IsraelAzoulay/tour-notifier.git
3. Navigate to the project directory.
4. Install the required libraries using the command: pip install -r requirements.txt
5. Set up your `.env` file with your email credentials (SENDER_EMAIL, SENDER_PASSWORD, RECEIVER_EMAIL).
6. Run `main.py`: python main.py
7. The system will start monitoring the specified URL and notify you when new events are detected.

### Files in the Repository:
- **main.py**: The main script that monitors the webpage and manages notifications.
- **data.txt**: Contains a record of detected events.
- **extract.yaml**: Selector template for data extraction.
- **requirements.txt**: Contains the required Python libraries for the project.
- **.gitignore**: Specifies files and directories that are to be ignored by Git.

### Contribution:
Feel free to fork this repository, make changes, and submit pull requests. Any feedback or suggestions are welcome!
