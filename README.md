# django-tailwind-support
### A bare bones setup for using tailwind with django.

# Setup:
I removed all the dependencies to run node, to get them back. Navigate to the directory that has **tailwind_project\tailwind_app\static\js** and type this command in the command terminal:  `npm install`

Make sure to always use the style.min.css in your html pages for accessing tailwind css as it yields better performance.

Also whenever you are adding another app to the project, make sure to copy the static folder from **tailwind_app** and then add it to the new app to access tailwind css there.

# Information:
I refered the article done by medium to setup this project, corrected few bits of the code to make tailwind run for me. I uploaded this repo to make this part of the procedure a simple install.

Article refered : https://medium.com/@lendinez/how-to-use-tailwind-in-django-and-not-die-in-the-attempt-2853eb164aa7

---

