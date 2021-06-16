# python-web-flask-mvc-pbkdf2-encrypted-argon2-encode

## Description
This is a simple login with
encryption and encoding. A custom error
page will be shown for unauthorized
access.

Passwords are pbkdf2 encrypted and encoded argon2.

## Tech stack
- python
  - flask
  - argon2_cffi
  - backports.pbkdf2

## Docker stack
- python:latest

## To run
`sudo ./install.sh -u`
- Available http://localhost
- Login with id: user and password: pass
- Login with id: admin and password: pass
- Login with id: super and password: pass

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
