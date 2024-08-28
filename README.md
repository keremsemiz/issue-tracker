# Issue Tracking API

This is a FastAPI-based API for tracking issues, including creating developers, adding issues, and updating issue statuses.

## Features

- **Developer Management**: Add and list developers.
- **Issue Management**: Create and list issues, and update issue statuses.

## Installation

### Using Poetry

1. Clone the repository:
    ```bash
    git clone https://github.com/keremsemiz/issue-tracker.git
    cd issue-tracking-api
    ```

2. Install dependencies:
    ```bash
    poetry install
    ```

3. Run the application:
    ```bash
    poetry run uvicorn issue_tracking_api.main:app --reload
    ```

### Using Pip

1. Clone the repository:
    ```bash
    git clone https://github.com/keremsemiz/issue-tracker.git
    cd issue-tracking-api
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    uvicorn issue_tracking_api.main:app --reload
    ```

## Usage

After starting the application, you can interact with the API at `http://127.0.0.1:8000`.

### Endpoints

- **POST /developers/**: Add a new developer.
- **GET /developers/**: List all developers.
- **POST /issues/**: Add a new issue.
- **GET /issues/**: List all issues.
- **PUT /issues/{issue_id}/status/**: Update the status of an issue.

You can also explore the API documentation by visiting `http://127.0.0.1:8000/docs` in your browser.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
