# Zoom-Like Video Call Application

This application is a Zoom-like video call platform developed using Django, JavaScript, and agora.io for real-time video communication. It allows multiple users to join the same meeting, similar to Zoom's functionality.

## Features

- **Real-time Video Calls:** Utilizes agora.io to facilitate seamless and high-quality video communication.
- **Multi-Participant Meetings:** Supports multiple participants joining a single meeting room.
- **User Authentication:** Utilizes Django's authentication system to manage user access and permissions.
- **Meeting Creation and Management:** Users can create, join, and manage meetings.
- **Responsive UI:** Provides a user-friendly interface across different devices.

## Installation

### Prerequisites

- Python (version >= 3.6)
- Node.js and npm

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/zoom-like-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd zoom-like-app
    ```

3. Install Python dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Install JavaScript dependencies:

    ```bash
    npm install
    ```

## Configuration

1. **Django Settings:**

    - Create a `.env` file in the root directory.
    - Define the following environment variables:

        ```dotenv
        DEBUG=TRUE  # Set to False in production
        SECRET_KEY=YourSecretKeyHere
        AGORA_API_KEY=YourAgoraAPIKey
        # Other configuration variables...
        ```

2. **Agora.io Configuration:**

    - Sign up for an account on [agora.io](https://www.agora.io).
    - Obtain the API Key and update the `AGORA_API_KEY` in the `.env` file.

## Usage

1. Start the Django server:

    ```bash
    python manage.py runserver
    ```

2. Run the frontend (assuming webpack or any bundler is set up):

    ```bash
    npm start
    ```

3. Access the application in your browser at `http://localhost:8000`.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes and commit them (`git commit -am 'Add feature/improvement'`).
4. Push the branch (`git push origin feature/improvement`).
5. Create a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to [agora.io](https://www.agora.io) for their real-time communication platform.
- Inspiration drawn from Zoom's user-friendly interface and multi-participant functionalities.
