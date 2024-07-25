# Social Media Django Project
## Overview
![img.png](pic_readme%2Fimg.png)
![img_1.png](pic_readme%2Fimg_1.png)
![img_2.png](pic_readme%2Fimg_2.png)
![img_3.png](pic_readme%2Fimg_3.png)
![img_4.png](pic_readme%2Fimg_4.png)
![img_5.png](pic_readme%2Fimg_5.png)
This project is a social media web application built using Django. It provides core functionalities such as user profiles, post creation, liking posts, following/unfollowing users, and user recommendations.

## Features

- **User Authentication**: Sign up, sign in, and log out functionalities.
- **Profile Management**: Create and update user profiles with a profile picture and bio.
- **Post Creation**: Users can upload posts with images and captions.
- **Feed**: Display posts from users that the current user follows.
- **Like Posts**: Users can like or unlike posts.
- **Follow/Unfollow**: Follow or unfollow other users.
- **User Search**: Search for users by username.
- **User Suggestions**: Suggest users to follow who are not currently followed by the user and are not the current user.

## Project Structure

- **`social_media/`**: Application code
  - **`migrations/`**: Database migrations
  - **`models.py`**: Database models
  - **`views.py`**: View functions
  - **`urls.py`**: URL routing
- **`media/`**: Media files
  - **`post_images/`**: Uploaded post images
  - **`profile_images/`**: Profile pictures
- **`static/`**: Static files (CSS, JavaScript, etc.)
- **`templates/`**: HTML templates
- **`social_media/`**: Project settings
  - **`settings.py`**: Project configuration
  - **`urls.py`**: Project URL routing
- **`venv/`**: Virtual environment
- **`manage.py`**: Django management script
- **`db.sqlite3`**: SQLite database file
- 

## Installation

### 1. Clone the Repository:
   ```bash
   git clone git@github.com:wulitina/social_media.git
   cd social_media
```
or set up a new project by yourself

```bash
django-admin startproject social_media
cd social_media
django-admin startapp core
```

### 2. Set Up Virtual Environment:
```bash
python3 -m venv venv
source venv/bin/activate
pip install django
```
### 3. Apply Migrations:
```bash
python3 manage.py runserver
python3 -m django --version
python3 -m pip install Pillow
python3 manage.py makemigrations
```

### 4. Create Superuser (optional, for admin access):
```bash
python3 manage.py createsuperuser
(e.g.user： admin
Email address: admin@socialbook.com
password:admin)
```
### 5. Run the Development Server:
```bash
python3 manage.py runserver
```