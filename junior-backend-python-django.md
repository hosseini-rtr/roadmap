
## Python Fundamentals
### Core Syntax
- Variables & Data Types
  - int, float, str, bool
  - Type hints (PEP 484)
  - Dynamic typing vs static typing
- Control Structures
  - if/elif/else
  - for/while loops
  - break/continue/pass
- Functions
  - def, return, arguments
  - *args, **kwargs
  - Lambda functions
  - Decorators (basic understanding)

### Data Structures
- Lists
  - List comprehensions
  - Methods: append, extend, pop, sort
- Dictionaries
  - Dict comprehensions
  - Methods: get, keys, values, items
- Tuples & Sets
  - Immutability
  - Set operations
- Strings
  - Formatting (f-strings, format())
  - Methods: split, join, strip

### OOP Basics
- Classes & Objects
  - `__init__` constructor
  - Instance vs class variables
  - Methods
- Inheritance
  - Single inheritance
  - super()
- Encapsulation
  - Public vs private (underscore convention)

### Standard Library
- os & sys
- datetime
- json
- re (regular expressions basics)
- collections (defaultdict, Counter)

## Django Framework
### Project Setup
- Virtual Environments
  - venv, virtualenv
  - requirements.txt
- Django Installation
  - pip install django
  - django-admin startproject
  - python manage.py startapp

### Core Concepts
- MVT Architecture
  - Models
  - Views
  - Templates
- URL Routing
  - path(), include()
  - URL parameters
  - Named URLs
- Settings
  - DEBUG mode
  - INSTALLED_APPS
  - DATABASES
  - STATIC_FILES

### Models
- Field Types
  - CharField, TextField
  - IntegerField, BooleanField
  - DateField, DateTimeField
  - ForeignKey, ManyToMany
- Meta Options
  - ordering
  - verbose_name
- Model Methods
  - `__str__`
  - save(), delete()
- QuerySets Basics
  - filter(), get()
  - all(), exclude()
  - order_by()
  - create(), update()

### Views
- Function-Based Views
  - HttpRequest, HttpResponse
  - render(), redirect()
- Class-Based Views (Basics)
  - TemplateView
  - ListView, DetailView
- Forms
  - forms.Form
  - forms.ModelForm
  - Validation

### Templates
- Template Language
  - Variables: {{ variable }}
  - Tags: {% tag %}
  - Filters: {{ value|filter }}
- Template Inheritance
  - {% extends %}
  - {% block %}
  - {% include %}
- Static Files
  - {% load static %}
  - STATIC_URL, STATIC_ROOT

### Admin
- ModelAdmin
  - list_display
  - list_filter
  - search_fields
- Custom admin actions

## Database Basics
### SQL Fundamentals
- CRUD Operations
  - SELECT, INSERT, UPDATE, DELETE
- WHERE clauses
- JOINs (INNER, LEFT)
- Basic indexing concept

### Django ORM
- Migrations
  - makemigrations
  - migrate
  - Migration files
- Relationships
  - One-to-Many (ForeignKey)
  - Many-to-Many
  - One-to-One
- Basic Queries
  - select_related (basic)
  - prefetch_related (basic)

### PostgreSQL/MySQL Basics
- Installation & Setup
- Database creation
- User permissions
- psycopg2 / mysqlclient drivers

## REST APIs (Basic)
### Django REST Framework
- Installation & Setup
- Serializers
  - ModelSerializer
  - Field types
- ViewSets (Basic)
  - ModelViewSet
- Routers
  - DefaultRouter
- API Views
  - APIView
  - Generic Views

### HTTP & REST
- HTTP Methods
  - GET, POST, PUT, DELETE
- Status Codes
  - 200, 201, 400, 404, 500
- JSON Format
- Request/Response cycle

## Version Control
### Git Basics
- init, clone
- add, commit
- push, pull
- branch, checkout
- merge (basic)
- .gitignore

### GitHub/GitLab
- Repository basics
- Pull requests
- Code review basics

## Testing (Introduction)
### Unit Tests
- unittest module
- Django TestCase
- setUp, tearDown
- Assertions

### Test Coverage
- Basic concept
- coverage.py tool

### Debugging
- print() debugging
- pdb basics
- Django Debug Toolbar


## Basic Deployment
### Environment Variables
- python-decouple
- django-environ
- .env files

### Static Files
- collectstatic
- STATIC_ROOT vs STATIC_URL

### Basic Server Knowledge
- Development server
- WSGI concept (basic)
- gunicorn (basic usage)

## Soft Skills
### Code Quality
- PEP 8 Style Guide
- Readable code
- Comments & Documentation
- DRY principle

### Communication
- Asking questions
- Documentation reading
- Ticket/Issue understanding

### Time Management
- Task estimation basics
- Daily standups participation

