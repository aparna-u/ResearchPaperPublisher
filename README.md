# TurnUp - Research Paper Publisher

A web app deployed over pythonanywhere allowing admins to upload research papers with custom categories. Users can easily filter, view, and download papers by category, enhancing accessibility and convenience.

## 🛠 Tech Stack

![html](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white) ![css](https://img.shields.io/badge/CSS-FF2D20?&style=for-the-badge&logo=css3&logoColor=white) ![js](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![python](https://img.shields.io/badge/Python-217346?style=for-the-badge&logo=python&logoColor=white) ![django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white) ![SQLITE](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
[![PythonAnywhere Badge](https://img.shields.io/badge/-PythonAnywhere-%231FADDA?style=for-the-badge&logo=python&logoColor=white)](#)


## Installation

- Clone the Repository to the desired location

```bash
  git clone https://github.com/Deepak91168/ResearchPaperPublisher
```

- Open Repository

```bash
 cd ResearchPaperPublisher
```

- Create a Virtual environment

```bash
 virtualenv venv
```

- Activate the virtual environment

```bash
 source venv/bin/activate
```

- Install the required Dependencies

```bash
 pip install -r requirement.txt
```

- Migrate all the database

```bash
 python manage.py migrate
```

- Run the Development server

```bash
 python manage.py runserver
```
- If running with DEBUG=FALSE, then

```bash
python manage.py collectstatic
```
## Screenshot

Working Project will look like this!

![App Screenshot](https://imgur.com/QbqMtgA.png)

## Contributing

Contributions are always welcome :)

Can work upon the [issues](https://github.com/Deepak91168/ResearchPaperPublisher/issues) mentioned and

1. Fork the Repository
2. Create your featureBranch.
3. Commit your changes (`git commit -m "Added amazingFeature"`)
4. Push to the branch (`git push origin feature/amazingFeature`)
5. Open up a Pull Request.

## References
````
# Django
  https://docs.djangoproject.com/en/4.1/

# Pythonanywhere
  https://help.pythonanywhere.com/pages/DeployExistingDjangoProject/
````
