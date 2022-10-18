# SCA-30-days-of-code
Project 8 - Understanding models and their flexibility in data creation

Build an e-learning platform with your own content management system (CMS). The CMS will allow instructors to create courses and manage their content

<!-- to dump data from the database into the shell -->
- python manage.py dumpdata courses --indent=2

<!-- to dump data from the database into a file -->
- python manage.py dumpdata courses --indent=2 --output=courses/fixtures/
subjects.json

<!-- to dump data from a file into the database -->
- python manage.py loaddata subjects.json
