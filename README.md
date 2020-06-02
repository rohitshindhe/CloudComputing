# CloudComputing

import libraries as below:

from enum import unique
import requests
from django.template.defaultfilters import upper
from flask import Flask, render_template, request, redirect, url_for, flash
from flask_sqlalchemy import SQLAlchemy
from OpenSSL import SSL

(ssl_context='adhoc' -----> http to https)

This app.py will display the weather of the cities in the world, using REST API from open weather "https://openweathermap.org/api".
Then the code is deployed to cloud aws ec2 instance.
When browsing can use the aws instance URL with port number.
In front of URL and use delete function to delete data from DB

POSTMAN options used: POST, GET, PUSH & DELETE.

Database:

SQlite has been used as internal DB.
