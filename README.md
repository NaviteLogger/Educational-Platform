# Educational-Platform

A place where everyone can learn programming and topics related to IT.

## Table of Contents

- [Educational-Platform](#educational-platform)
  - [Table of Contents](#table-of-contents)
  - [About The Project](#about-the-project)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgements](#acknowledgements)

## About The Project

This project is a place where everyone can learn programming and topics related to IT. It is a platform where you can find courses, articles, and other resources to learn from. You can also create your own courses and share them with others.

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- [Python](https://www.python.org/downloads/)
- [Django](https://www.djangoproject.com/download/)
- [Django REST Framework](https://www.django-rest-framework.org/#installation)
- [MySQL](https://www.mysql.com/downloads/)

### Installation

1. Clone the repo

```sh
git clone https://github.com/NaviteLogger/Educational-Platform.git
```

2. Install Python packages

```sh
pip install -r requirements.txt
```

3. Create a database

```sh
mysql -u root -p
```

```sql
CREATE DATABASE educational_platform;
```

The rest of the database configuration is provided in the `init_db.py` file.

4. Create a `.env` file in the root directory and add the following variables

```env

```

5. Run the server

```sh
python manage.py runserver
```

### Usage

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the project

2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)

3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)

4. Push to the Branch (`git push origin feature/AmazingFeature`)

5. Open a Pull Request

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Contact

- [Email](mailto:kacprzakmarek92@gmail.com)

## Acknowledgements
