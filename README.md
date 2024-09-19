# Anti-Social Media Board


https://github.com/user-attachments/assets/ddd49b43-eb69-42e8-bce7-0f3afcf606ef
![Screenshot 2024-09-18 at 11 34 00 PM](https://github.com/user-attachments/assets/cc2d5a49-6f21-4e14-8275-ae90cb04ef3b)
![Screenshot 2024-09-18 at 11 34 12 PM](https://github.com/user-attachments/assets/5332035d-0bd9-4acd-b072-291fa504ddf6)


An intentionally ugly and chaotic message board application built with Flask, featuring real-time updates, image and video generation, and more!

## Features

- User registration and authentication
- Posting messages with tags
- Commenting on messages
- Adding reactions to messages
- Image generation using Stability AI API
- Video generation using Luma AI API
- Real-time updates using Socket.IO
- Tagging system with popular tags display
- User profiles
- Intentionally chaotic and "ugly" design

## Prerequisites

- Python 3.7+
- Flask
- Flask-SocketIO
- Flask-Login
- python-dotenv
- requests

## Installation

1. Clone the repository:
   ```
   git clone git remote add origin https://github.com/lalomorales22/my_ugly_message_board.git
   cd my_ugly_message_board
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the project root and add your API keys:
   ```
   STABILITY_API_KEY=your_stability_api_key
   LUMAAI_API_KEY=your_lumaai_api_key
   ```

## Running the Application

1. Start the Flask development server:
   ```
   python app.py
   ```

2. Open a web browser and navigate to `http://localhost:5000`

## Usage

- Register a new account or log in
- Post messages with optional tags, images, and videos
- Comment on messages and add reactions
- Explore user profiles and tagged messages

## Contributing

PLEASSE.. I KNOW THERE ARE PEOPLE WHO CAN MAKE SOMETHING WAY COOLER THAN THIS, WITH THIS. LETS SEE WHAT YOU GOT.
