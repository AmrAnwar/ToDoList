### About the site Project:

this is Simple Project Agile Mangment site. 

### Run:

```shell
$ git clone https://github.com/AmrAnwar/ToDoList # orusing zip without git
$ cd ToDoList # go inside the project directory
amranwar00 (master) ToDoList $ virtualenv env -p python2
amranwar00 (master) ToDoList $ . env/bin/activate
(env) amranwar00 (master) ToDoList $ sudo pip install -r requirements.txt
(env) amranwar00 (master) ToDoList $ python manage.py createsuperuser # to access Admin page
(env) amranwar00 (master) ToDoList $ python manage.py collectstatic # generate static files
(env) amranwar00 (master) ToDoList $ python manage.py runserver # run the server

Performing system checks...

System check identified no issues (0 silenced).
December 15, 2018 - 15:34:40
Django version 1.11.4, using settings 'todo.settings'
Starting development server at http://127.0.0.1:8000/
```

### What User Can Do: 
- create , update, delete Projects << Project has lists inside it
- create, update, delete Lists << list has Tasks inside it 
- create, update, delete Task inside each list, 
- tasks has status , points , sublists inside it .
- user can invite other users to his list using their email
- user can follow other users

