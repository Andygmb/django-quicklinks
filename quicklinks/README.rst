quicklinks
========================

Important notes for Django-quicklinks:

1. Install from github ( pip install git+git://github.com/emkorybski/django-quicklinks.git )

2 .Add quicklinks ('quicklinks') to INSTALLED_APPS and run 'python manage.py migrate quicklinks' if you have the south app installed.

3. Create 'quicklinks' folder in your 'media/' directory and copy contents od 'media_files' folder there. It is using LESS, too so point your LESS compiler to the newly created 'quicklinks' folder.

4. Install 'djangoadminsortable' app - ( pip install git+git://github.com/emkorybski/django-admin-sortable.git ). The app also needs a separate folder in 'media/' directory, copy files from 'static/adminsortable/' there. 


