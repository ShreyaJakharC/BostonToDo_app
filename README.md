# Boton To-Do List

## Overview

Travel List to Boston is a lightweight Flask web app that lets visitors build and manage a personalized itinerary of Boston attractions. Users can add new places they want to see, mark items complete (deleting them from the list), and rely on MongoDB for persistent storage.

## Features

- **Add Attractions:** Fill out a simple form to save a new place to your travel list
- **View List:** See all planned stops in a clean, responsive table
- **Delete Completed:** Remove items when you’ve visited, keeping your list up-to-date
- **Persistent Storage:** All entries live in a MongoDB collection, surviving server restarts
- **Intuitive UI:** Consistent design with Bootstrap and Jinja2 templates for seamless navigation

## Tech & Tools

- **Backend:** Python 3, Flask, PyMongo
- **Database:** MongoDB (`class-mongodb.cims.nyu.edu`)
- **Templating & Styling:** Jinja2, HTML5, CSS3, Bootstrap
- **Deployment:** NYU CIMS i6 web server (`i6.cims.nyu.edu`), CGI-based Flask hosting
- **Environment Management:** `.env` file for credentials, Python `venv` for dependencies
- **Version Control:** Git & GitHub

## Results & Key Takeaways

- **Full CRUD Workflow:** Implemented create, read, and delete operations with a user-friendly interface
- **Remote Deployment:** Successfully published to i6.cims.nyu.edu, bridging local development and shared hosting
- **Seamless UX:** Delivered a consistent look-and-feel across pages, reducing user friction


## Skills Gained

Flask Application Design, MongoDB Integration, Front-End Templating, and Deployment on Shared Hosting

## Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/flask-mongodb-travel-list.git
   cd flask-mongodb-travel-list
   ```
