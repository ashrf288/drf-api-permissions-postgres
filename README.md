## Permissions & Postgresql

## Overview

Let’s move our site closer to production grade by adding Permissions and Postgresql Database.


Feature Tasks and Requirements

Features - General

You have been supplied with two demos, each presenting a key new feature.

blogapi-permissions demonstrates how to restrict access to portions of your APIs data.

blogapi-postgres demonstrates switching over to using postgres vs sqlite

Your job is to merge the functionality of both demos.

Customize your project to use different application features/models than Blog and Post
Features - Django REST Framework

Make your site a DRF powered API as you did in previous lab.

Adjust project’s permissions so that only authenticated user’s have access to API.

Add a custom permission so that only author of blog post can update or delete it.

Add ability to switch user’s directly from browsable API.