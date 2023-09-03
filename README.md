# Chatify

## Overview

This is a real-time chat application built using Django that allows users to communicate with each other instantly. It provides a simple and intuitive user interface for sending text messages in real-time, making it ideal for both personal and group conversations.

## Getting Started Guide

### Dependencies

Install all the requirements in your machine `pip3 install -r requirements.txt`

### Postgres

Download postgres: https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
* After downloading it, enter it postgres console `psql postgres`
* Create Database `CREATE DATABASE chatify;`
* Create User `CREATE USER admin WITH PASSWORD 'admin';`
* Give the new user all privileges on new db `GRANT ALL PRIVILEGES ON DATABASE chatify TO admin;`

### Run Migrations 

`python3 manage.py migrate`

### Create SuperUser 

* `python manage.py createsuperuser`
* Email: `admin@admin.com`
* Username: `admin`
* Password: `admin`

### Run Server

`python3 manage.py runserver`

Good Luck