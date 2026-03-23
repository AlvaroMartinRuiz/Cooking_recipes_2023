# Cooking Recipes Platform

A full-stack web application built with **Flask** and **SQLAlchemy** that allows users to discover, share, and interact with cooking recipes.

## Features

- **User Authentication**: Secure sign-up and login system using `Flask-Login`.
- **Recipe Management**: Create detailed recipes including:
  - Title, description, cooking time, and servings.
  - Granular ingredients (amount and unit type).
  - Step-by-step cooking instructions.
  - Photo attachments.
- **Social Interaction**:
  - Follow and unfollow other chefs/users.
  - Comment on recipes and reply to other comments.
  - Like or dislike specific recipes.
  - Bookmark favorite recipes to your personal profile.
- **Search**: Integrated search API to quickly find recipes by title.

## Tech Stack
- **Backend**: Python, Flask, Flask-SQLAlchemy, Flask-Login
- **Database**: Relational models for Users, Recipes, Ingredients, Steps, Comments, Photos, Bookmarks, and Ratings.
- **Frontend**: HTML/CSS templating via Jinja2.

## Structure
The core application logic is located in the `recipes/` module, which defines the database schema in `model.py`, handles user authentication in `auth.py`, and maps application routes in `main.py`.
