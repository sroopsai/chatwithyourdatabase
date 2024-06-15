# Chat With Your Database

Chat With Your Database is a simple yet powerful chat application that allows you to interact with your MySQL database using natural language queries. Powered by Streamlit and LangChain, this application translates your natural language questions into SQL queries and returns the results from your database.

## Features

- Natural language interaction with your MySQL database
- Translates user queries into SQL
- Displays query results in a user-friendly chat interface
- Easy to configure and connect to any MySQL database

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.12 or higher
- MySQL database
- Poetry package manager (optional, for dependency management)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sroopsai/chatwithyourdatabase.git
    cd chatwithyourdatabase
    ```

2. **Install dependencies:**

    If you have Poetry installed:

    ```bash
    poetry install
    ```

    Alternatively, you can use pip:

    ```bash
    pip install -r requirements.txt
    ```

3. **Set up environment variables:**

    Create a `.env` file in the project root and add your database credentials:

    ```env
    MYSQL_USER=your_mysql_user
    MYSQL_PASSWORD=your_mysql_password
    MYSQL_HOST=your_mysql_host
    MYSQL_PORT=your_mysql_port
    MYSQL_DATABASE=your_mysql_database
    ```

## Usage

1. **Run the Streamlit app:**

    ```bash
    streamlit run src/app.py
    ```

2. **Connect to your database:**

    In the sidebar, enter your database connection details and click `Connect`.

3. **Start chatting:**

    Type your questions in the chat input box and receive SQL-generated responses based on your database schema.

## Configuration

The application uses the following main libraries:

- **Streamlit**: For creating the web interface
- **LangChain**: For natural language processing and handling chat prompts
- **SQLAlchemy**: For database interaction
- **mysql-connector-python**: For MySQL database connection

## Contributing

Contributions are always welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Create a pull request.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions or need further assistance, feel free to reach out to the project maintainer:

- **Roopsai**
- **Email**: roopsai@outlook.in

## Acknowledgments

- Special thanks to the developers of Streamlit, LangChain, and SQLAlchemy for their amazing tools and libraries.


