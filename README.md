# minimal-flask-server

A small and minimalistic Flask framework with Gunicorn frontend.
Based on alpine 3.11 with the minimal components to run a basic Flask
application.

![](https://github.com/cgerull/minimal-flask-server/workflows/Docker%20Image%20CI%20latest/badge.svg?branch=development)

## Modules supplied

```bash
Flask==1.1.1
Flask-Bootstrap==3.3.7.1
gunicorn==20.0.4
Jinja2==2.10.3
PyYaml==5.3
visitor==0.1.3
Werkzeug==0.16.0
```
  
## Usage

Use this image as a base for your own Flask webapp. If you need addtional modules
please install them in user space for the user 'web' (UID 1000) in your own image.
