# Hadir1.1 - Attendance System Using Face Recognition

Hadir is an automated attendance system designed for public organizations using **Face Recognition** technology. This system makes it easy for organizers and educational institutions to monitor attendance at events, workshops, and classes with a web-based platform for fast and accurate attendance registration.

## Key Features

- **Automated Face Detection and Recognition**: Detects and recognizes faces in real-time.
- **Web-based Platform**: No need for users to download an application; accessible 24/7 via a web browser.
- **Efficient Attendance Registration**: Extracts facial features to automatically mark present or absent attendees.
- **User-Friendly Interface**: Simple and intuitive UI for instructors and attendees.
- **Detailed Reporting**: Offers attendance summaries and statistics for event organizers.
- **Secure and Scalable**: Built with security measures such as SHA-256 encryption for user data and can handle large groups of attendees.

## Installation

To set up Hadir1.1 locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Dexter24601/Hadir1.1.git
2. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
3. Start the Django development server:
   ```bash
   python manage.py runserver
## Usage
1. Create an Account: Instructors or organizers can create a new account on the platform.
2. Create a Class/Event: Generate a QR code for attendees to scan and register by submitting their facial images.
3. Take Attendance: Upload a photo of the attendees in the session, and the system will automatically detect and register their attendance.
4. View Results: Instructors can view attendance data, including present and absent attendees, through the dashboard.

## Technologies Used
1. Python: Core language for back-end and face recognition processing.
2. Django: Web framework for building the platform.
3. OpenCV & YOLOv5: For face detection and recognition.
4. SQLite: Local database for storing user and attendance data.

