# Django 5.x Compatibility

This fork provides django-tastypie v0.15.1 with Django 5.2 and Python 3.12 support.

## Why This Fork?

The original requirements constraint was `django-tastypie>=0.14.0,<0.15.0` which excluded v0.15.1.
Version 0.15.1 includes important Django 5.2 compatibility fixes that we need.

## Changes
- Version 0.15.1 includes Django 5.2 compatibility
- Supports Python 3.12
- Modern URL patterns with django.urls.conf
- Fixes URL-related issues with Django 5.x

## Usage
```
git+https://github.com/harvard-hbs/hbso-django-tastypie.git@django-5x-compatibility
```
