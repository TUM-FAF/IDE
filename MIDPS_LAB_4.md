# Interactive Development Environments Laboratory Work #4

_Recomended tools are marked with **bold**_

_Use a different IDE for each laboratory work_

## Web development IDEs/text editors (one of):
  - **RubyMine**
  - **PyCharm**
  - **phpStorm/webStorm**
  - Sublime Text 3
  - Brackets
  - Komodo
  - Coda

### Prerequisites:
  - IDEs: (one of) Sublime Text 3, RubyMine, PyCharm, Komodo, Coda, phpStorm, webStorm, Brackets
  - Languages: Ruby, Python, JS
  - Technologies and Frameworks: Ruby on Rails, Django, Node.js && Express

### Mandatory Tasks:
  - Choose one of:
    - Express (JavaScript on Node.js)
    - Django (Python)
    - RoR (Ruby on Rails)
  - Install chosen framework on your computer (or a remote server)
  - Serve a static page with your name on it at address `/me.html` or `/me`
  - Serve a bootstrap form. It should have at least one field (ex. name). On submitting this form save data (in database or files or session or localStorage or whatever you want). Output a list of data from all previously submits.

### Tasks With Points:
  - Use framework command line to generate project files (2pt)
  - Save data submitted through form into database (1pt)
  - Create and use database seed (2pt)
  - Migrations (one of):
    - Use a relational database. Alter form fields and database structure (ex. add one more input field to form and add a column for it in your database). Create a migration for it. (2pt)
    - Use a non-relational database. Explain why you don't need migrations in this case. (1pt)
  - Use a different from default HTML templating engine (1pt)
  - Write at least 3 tests (any type of tests) (2pt)
  - Deploy your project (one of):
    - Deploy your project to [Heroku](https://www.heroku.com/) or [AppFog](https://www.appfog.com/)(1pt)
    - Create a GitHub hook that will trigger your custom server to download latest from master branch changes and apply them. You may need an additional repository for that. (3pt)
  - _Mention your own tasks that you did and claim points for them (max of 5 pt in total)_

### References:

Installation:
* [Express](http://expressjs.com/guide.html). Requires [Node.js](http://nodejs.org/download/)
* [Django](https://docs.djangoproject.com/en/dev/topics/install/). Requires [Python](https://www.python.org/download/)
* [RoR](http://rubyonrails.org/download/) or [Railsinstaller](http://railsinstaller.org/). Requires [Ruby](https://www.ruby-lang.org/en/installation/)

IDE:
* [PyCharm for Django](http://www.jetbrains.com/pycharm/quickstart/django_guide.html)

Command lines:
* [Rails command line](http://guides.rubyonrails.org/command_line.html)
* [Django command line](https://docs.djangoproject.com/en/dev/ref/django-admin/). Look for `manage.py startapp`
* [Express generator](https://github.com/petecoop/generator-express)

Testing:
* [Testing in Django](https://docs.djangoproject.com/en/dev/topics/testing/)
* [Testing in RoR](http://guides.rubyonrails.org/testing.html)
* [Testing in Express](http://www.scotchmedia.com/tutorials/express/authentication/2/02)
