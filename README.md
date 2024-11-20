# Recommendation System and Deployment

This project is a Recommendation system that suggests movies based on user preferences. It also includes a web interface for users to interact with the recommender system and view detailed information about movies and cast members.

## Features

- Movie recommendations based on user input
- Detailed information about recommended movies
- Cast information and biographies
- User reviews from IMDb

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/akshay132cloud/recommendation-system-movies-.git
    cd Netflix-Recommender-System-and-Deployment
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    venv\Scripts\activate  # On Windows
    # source venv/bin/activate  # On macOS/Linux
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask application:
    ```sh
    python main.py
    ```

2. Open your web browser and go to `http://127.0.0.1:8080`.

3. Enter your preferences and get movie recommendations.

## Project Structure

- `main.py`: The main Flask application file.
- `templates/`: Contains HTML templates for the web interface.
- `static/`: Contains static files like CSS and JavaScript.
- `requirements.txt`: Lists the Python dependencies.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.