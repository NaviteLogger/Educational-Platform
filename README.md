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
