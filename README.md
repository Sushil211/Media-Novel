<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Sushil211/Media-Novel">
    <img src="static/images/MediaNovel_logos_white.png" alt="Logo" width="160" height="160">
  </a>

  <h3 align="center">Media Novel</h3>

  <p align="center">
    The Next Gen Digital Platform.
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Screenshot (171)](https://user-images.githubusercontent.com/54482089/140600537-b0e6eb15-b11d-4f91-8128-79e82137d0e1.png)

<br />

### Mobile View

<br />

![mobile_screenshot1](https://user-images.githubusercontent.com/54482089/140600210-c150a14b-b874-4161-be09-6107a4af07fa.jpeg)
![mobile_screenshot2](https://user-images.githubusercontent.com/54482089/140600212-cfa72b33-56e4-425a-a804-0ed3bc33fcea.jpeg)

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [django](https://www.djangoproject.com/)
* [Jinja template](https://jinja.palletsprojects.com/en/3.0.x/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

## Installation
1. Fork this repository to your github account
2. Clone the forked repository and proceed with steps mentioned below

### Install requirements
```
virtualenv env --python=python-3.9.6
.\env\Scripts\activate 
pip install -r requirements.txt
```
### Declare Env variables as env_example.py
1. SECRET_KEY can be found at medianovel/settings.py <br />
2. CLOUD_NAME, API_KEY and API_SECRET can be found at <a href="https://cloudinary.com/">cloudinary</a>

### DB Migrations
```
python manage.py makemigrations
python manage.py migrate
```
### Start Server
```
python manage.py runserver
```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

You can create new room

![Screenshot (174)](https://user-images.githubusercontent.com/54482089/140600547-e65497ac-b9f9-465b-9a09-3fb595bee591.png)

Check a user profile

![Screenshot (172)](https://user-images.githubusercontent.com/54482089/140600540-dcbe20b6-c297-4275-ac79-0f445282c5be.png)

Edit your profile

![Screenshot (176)](https://user-images.githubusercontent.com/54482089/140600559-f9dd327f-5cec-4378-9fb6-7e56fc949faf.png)

Browse all topics

![Screenshot (175)](https://user-images.githubusercontent.com/54482089/140600553-d868354f-d330-4ec9-aba6-452479e19e65.png)

Message in a room

![Screenshot (173)](https://user-images.githubusercontent.com/54482089/140600542-a16cc9b1-6007-4165-84dc-774dec254003.png)

Log in

![Screenshot (177)](https://user-images.githubusercontent.com/54482089/140600564-56cc1abd-013a-4472-8e2d-aff817eeee21.png)

Sign Up

![Screenshot (178)](https://user-images.githubusercontent.com/54482089/140600570-8591bddc-b3cd-4332-adf6-1e0d83fd429d.png)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

<a href="https://linkedin.com/in/sushil-sekhar-satapathy-78ab181a4" target="blank">
<img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="sushil-sekhar-satapathy-78ab181a4" height="30" width="40" />
</a>

<a href="https://twitter.com/ims_king" target="blank">
<img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg" alt="ims_king" height="30" width="40" />
</a>

**sushilsekhar300@gmail.com**

<br />

Live Project Link: https://media-novel.herokuapp.com/

<p align="right">(<a href="#top">back to top</a>)</p>
