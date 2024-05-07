# MySocial

MySocial is a social media website built using Python and Django framework. It comes preloaded with sample data to showcase its features. Users can register, create profiles, connect with friends, post updates, and interact with other users.

## Installation

Before running MySocial, ensure you have Python and Django installed on your system. You can install Django using pip:

```
pip install django
```

Additionally, you may need to install other dependencies. These are typically included in the `requirements.txt` file. To install them, navigate to the project directory and run:

```
pip install -r requirements.txt
```

## Usage

To use MySocial on your local machine, follow these steps:

1. Clone the repository to your local machine:

```
git clone https://github.com/DivyaSirala/MySocial.git
```

2. Navigate to the project directory:

```
cd mysocial
```

3. Apply migrations to create the database schema:

```
python manage.py migrate
```

4. Load sample data (optional):

```
python manage.py loaddata sample_data.json
```

5. Run the development server:

```
python manage.py runserver
```

6. Open your web browser and go to [http://localhost:8000](http://localhost:8000) to access MySocial.

7. You can now register as a new user or use the preloaded accounts to explore the features of MySocial.

## Features

- User registration and authentication
- Profile creation and customization
- Friend connections
- Posting updates
- Like and comment on posts
- Search functionality

## Contributing

Contributions are welcome! If you'd like to contribute to MySocial, please fork the repository and submit a pull request with your changes.
