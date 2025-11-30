# CS340
# Grazioso Salvare Animal Shelter Database Interface

## Project Overview

This project delivers a reusable Python module that enables secure CRUD (Create, Read, Update, Delete) operations on the Grazioso Salvare animal shelter database. The module supports staff in managing animal records and identifying dogs suitable for search-and-rescue training.

---

## 🛠️ Technology Stack

- **Language**: Python 3
- **Database**: MongoDB
- **Driver**: PyMongo  
  PyMongo is the official MongoDB driver for Python. It was chosen for its reliability, full API support, and seamless integration with Python applications.

---

## 🐍 Module Usage

### File: `animal_crud.py`

This module defines a class `AnimalShelter` that encapsulates all CRUD functionality. It is designed for reuse in other Python scripts or notebooks.

### Class: `AnimalShelter`

#### Constructor
```python
AnimalShelter(username, password, db_name='aac', collection_name='animals')
Connects to MongoDB using the provided credentials.

Defaults to the aac database and animals collection.
Demonstrates the CRUD functions.
Imported aac_shelter_outcomes.csv into the aac database using MongoDB shell.
Verified creation and authentication of aacuser with readWrite access to the aac database.

