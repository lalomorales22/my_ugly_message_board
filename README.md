# Anti-Social Media Board

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

5. Initialize the database:
   ```
   python
   >>> from app import init_db
   >>> init_db()
   >>> exit()
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

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)