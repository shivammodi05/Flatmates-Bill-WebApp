# Flatmates' Bill

This web application helps to split a bill between two flatmates. It calculates the share of each flatmate based on the number of days they stayed in the house during the billing period.

## Features

- Calculate the share of each flatmate in the bill.
- Simple and intuitive web interface.

## Requirements

- Python
- Flask
- pip

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/shivammodi05/Flatmates-Bill-WebApp
    cd Flatmates-Bill-WebApp
    ```

2. Create a virtual environment:
    ```bash
    python -m venv .venv
    ```

3. Activate the virtual environment:
    - On Windows:
        ```bash
        .venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source .venv/bin/activate
        ```

4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask application:
    ```bash
    flask run
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/`.

3. Use the web interface to enter the bill details and calculate the share for each flatmate.

## Project Structure

- `flatmates_bill/flat.py`: Contains the `Bill` and `Flatmate` classes.
- `templates/index.html`: The main HTML template for the web interface.
- `static/main.css`: The CSS file for styling the web interface.
- `.gitignore`: Specifies files and directories to be ignored by git.

## License

This project is licensed under the MIT License.
