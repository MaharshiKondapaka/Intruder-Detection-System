# Intruder-Detection-System

# Python Security System

A simple yet powerful security system built with Python, OpenCV, and React. It uses a pre-trained MobileNet SSD model for person detection, records video on motion, uploads it to Google Cloud Storage, and sends text notifications via Twilio. Features include arming/disarming the system, a web-based admin panel, and activity logs.

## Key Features
- **Person Detection**: Detects people using OpenCV and MobileNet SSD.
- **Video Recording**: Records video when motion is detected and saves it as MP4.
- **Cloud Storage**: Uploads videos to Google Cloud Storage with public URLs.
- **Text Notifications**: Sends SMS alerts via Twilio with video links.
- **Admin Panel**: React-based frontend to arm/disarm the system and view logs.
- **Activity Logs**: View recorded events by date range.

## Prerequisites
Before you begin, ensure you have:
- **Python 3.9+**
- **Node.js**
- **FFmpeg**
- Google Cloud credentials (`credentials.json`) for storage access
- Twilio account credentials (set in `.env`)

## Installation
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-name>
