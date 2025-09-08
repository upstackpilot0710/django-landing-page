# Django Landing Page

A simple Django coming soon landing page for organizations. Easy to deploy and customize.

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Features](#features)
* [Technologies](#technologies)
* [Setup](#setup)
* [Deployment](#deployment)
* [Status](#status)
* [Contributing](#contributing)
* [License](#license)


## General info
A simple Django coming soon landing page built with Python and Django. Perfect for announcing upcoming websites or products.

## Screenshots

![Coming Soon Page](https://user-images.githubusercontent.com/19711677/84585879-cbfbb280-add9-11ea-8263-f2da37cbb638.png)

## Features

* Responsive design
* Social media links
* Email subscription form (frontend only)
* Video background support
* Bootstrap 4 framework
* Font Awesome icons

## Technologies
* Python 3.8
* Django 2.2.28
* JavaScript
* HTML5
* CSS3
* Bootstrap 4
* Font Awesome
* jQuery
* Vide.js for video backgrounds

## Setup

To run this app locally, follow these steps:

#### Prerequisites
- Python 3.8 or higher
- Pipenv (recommended) or pip
- Git

#### Installation

```bash
# Clone this repository
git clone https://github.com/upstackpilot0710/django-landing-page.git

# Navigate to the project directory
cd django-landing-page

# Install dependencies using Pipenv
pipenv install

# Activate the virtual environment
pipenv shell

# Run migrations (if any models are added)
python manage.py migrate

# Start the development server
python manage.py runserver

# Open your browser and visit http://127.0.0.1:8000
```

## Deployment

This project includes a `Procfile` for easy deployment to platforms like Heroku.

### Heroku Deployment

1. Create a Heroku app
2. Connect your GitHub repository
3. Enable automatic deploys or deploy manually
4. Set environment variables if needed (DEBUG=False for production)

### Local Production Setup

For production deployment, make sure to:
- Set `DEBUG = False` in settings.py
- Configure `ALLOWED_HOSTS` appropriately
- Set up a proper web server (nginx + gunicorn recommended)
- Use environment variables for sensitive settings

## Status
Project is: _completed_ and ready for use.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
