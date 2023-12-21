# YouTube Downloader Django Site

Welcome to the YouTube Downloader Django Site! This application allows you to download videos from YouTube using a simple web interface built with Django.

## Features

- **YouTube Video Downloading**: Enter the URL of the YouTube video you want to download.
- **Video Resolution Options**: Choose from available resolutions for the downloaded video.
- **User-friendly Interface**: Intuitive web interface for easy navigation and interaction.

## Technologies Used

- **Django**: Python-based web framework for building the backend.
- **PyTube**: Python library for downloading YouTube videos.
- **Bootstrap**: Front-end framework for designing responsive web pages.

## Setup Instructions

1. Clone this repository: `git clone https://github.com/asilbek3450/YouTube_downloader.git`
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - For Windows: `venv\Scripts\activate`
   - For macOS and Linux: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Run database migrations: `python manage.py migrate`
6. Start the development server: `python manage.py runserver`
7. Access the application at `http://localhost:8000` in your web browser.

## Usage

1. Run the application as per the setup instructions.
2. Open your web browser and navigate to the provided URL (`http://localhost:8000`).
3. Paste the YouTube video URL in the provided field.
4. Choose the desired video format and resolution options.
5. Click the "Download" button to start the download process.

## Contributing

Contributions are welcome! If you have any ideas, enhancements, or bug fixes, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

# Hosting
This application is hosted on Heroku at https://a2304.pythonanywhere.com/