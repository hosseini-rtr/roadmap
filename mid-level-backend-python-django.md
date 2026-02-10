# Mid-Level Backend Engineer - Python/Django

## Advanced Python
### Advanced OOP
- Multiple Inheritance
  - MRO (Method Resolution Order)
  - super() with multiple inheritance
- Abstract Classes
  - ABC module
  - abstractmethod
- Design Patterns
  - Singleton
  - Factory
  - Strategy
  - Observer
  - Decorator pattern

### Functional Programming
- Higher-order functions
- map, filter, reduce
- Closures
- Partial functions
- functools module

### Decorators
- Function decorators
- Class decorators
- @property
- @staticmethod, @classmethod
- Decorator factories
- functools.wraps

### Context Managers
- with statement
- `__enter__`, `__exit__`
- contextlib module
- Custom context managers

### Metaclasses
- type() usage
- `__new__` vs `__init__`
- Basic metaclass creation
- When to use metaclasses

### Generators & Iterators
- yield statement
- Generator expressions
- Iterator protocol
- itertools module
- Memory efficiency

## Django Advanced
### Advanced ORM
- Complex Queries
  - Q objects
  - F expressions
  - Aggregation (Count, Sum, Avg)
  - Annotation
- Query Optimization
  - select_related deep understanding
  - prefetch_related with Prefetch
  - only(), defer()
  - N+1 query problem
  - explain() for query analysis
- Raw SQL
  - raw() method
  - cursor.execute()
  - When to use raw SQL
- Database Functions
  - Concat, Coalesce
  - Extract, Trunc (dates)
  - Case, When

### Advanced Views
- Class-Based Views Mastery
  - Generic views customization
  - Mixins
  - CreateView, UpdateView, DeleteView
  - FormView
- Custom Mixins
  - LoginRequiredMixin
  - PermissionRequiredMixin
  - Custom authentication mixins
- Middleware
  - Writing custom middleware
  - Request/response processing
  - Middleware ordering

### Forms & Validation
- Advanced Forms
  - Form wizards
  - Formsets
  - Inline formsets
- Custom Validators
  - Field validators
  - Form-level validation
  - Model validation
- Clean methods
  - clean_<%% fieldname %%>
- clean()

### Django REST Framework (Advanced)
- Serializer Advanced
  - Nested serializers
  - SerializerMethodField
  - Custom fields
  - Validation
  - write(), create(), update()
- ViewSets & Mixins
  - Custom ViewSet mixins
  - Action decorators
  - Filtering, ordering, pagination
- Permissions
  - IsAuthenticated, IsAdminUser
  - Custom permissions
  - Object-level permissions
- Authentication
  - TokenAuthentication
  - SessionAuthentication
  - JWT (djangorestframework-simplejwt)
  - Custom authentication
- Versioning
  - URL versioning
  - Header versioning
  - Content negotiation

### Security
- OWASP Top 10
  - SQL Injection prevention
  - XSS protection
  - CSRF tokens
  - Clickjacking protection
- Django Security Features
  - SECURE_* settings
  - ALLOWED_HOSTS
  - Content Security Policy
- Password Management
  - Password hashers
  - Password validation
- Rate Limiting
  - django-ratelimit
  - Throttling in DRF

### Signals
- Built-in signals
  - pre_save, post_save
  - pre_delete, post_delete
  - m2m_changed
- Custom signals
- Signal handlers
- When to avoid signals

### Custom Management Commands
- Creating commands
- Command arguments
- Cron jobs integration

## Database & Performance
### PostgreSQL Advanced
- Indexes
  - B-tree, Hash
  - GiN, GiST
  - Partial indexes
  - Covering indexes
- JSON Fields
  - JSONField operations
  - Querying JSON data
- Full-Text Search
  - SearchVector, SearchQuery
  - SearchRank
  - Trigram similarity
- Constraints
  - Unique constraints
  - Check constraints
  - Exclusion constraints
- Views
  - Creating database views
  - Materialized views

### Query Optimization
- EXPLAIN ANALYZE
- Query planning
- Index usage analysis
- Slow query identification
- Django Debug Toolbar
- django-silk profiling

### Database Scaling
- Connection Pooling
  - pgbouncer
  - Database connection settings
- Read Replicas
  - Database routing
  - DATABASES configuration
  - Master-slave setup
- Partitioning (Introduction)
  - Range partitioning
  - List partitioning

### Transactions
- ACID properties
- Transaction isolation levels
- Django transactions
  - atomic()
  - select_for_update()
  - Transaction decorators
- Deadlock handling

### Caching
- Cache Strategies
  - Cache-aside
  - Write-through
  - Write-behind
- Django Cache Framework
  - Cache backends (Redis, Memcached)
  - Per-view caching
  - Template fragment caching
  - Low-level cache API
- Redis
  - Data structures (String, Hash, List, Set, Sorted Set)
  - Expiration
  - django-redis
  - Celery with Redis

## Concurrency & Async
### Threading
- threading module
- Thread synchronization
  - Lock, RLock
  - Semaphore
  - Event
- Thread safety
- GIL (Global Interpreter Lock)

### Multiprocessing
- multiprocessing module
- Process pools
- Queue, Pipe
- Shared memory
- When to use vs threading

### Async Python
- asyncio basics
  - async/await syntax
  - Event loop
  - Coroutines
  - Tasks
- aiohttp
- async/await in Django
  - ASGI
  - Async views (Django 3.1+)
  - Async ORM limitations

### Celery
- Task Queue Concept
- Setup & Configuration
  - Broker (Redis/RabbitMQ)
  - Result backend
- Tasks
  - @task decorator
  - Task execution
  - Task scheduling
  - Periodic tasks (Celery Beat)
- Error Handling
  - Retries
  - Error callbacks
- Monitoring
  - Flower
  - Task states

## API Design & Architecture
### RESTful Design
- Resource modeling
- URL structure best practices
- HATEOAS
- API versioning strategies
- Pagination
  - PageNumberPagination
  - LimitOffsetPagination
  - CursorPagination
- Filtering & Searching
  - django-filter
  - SearchFilter
  - OrderingFilter

### API Documentation
- OpenAPI/Swagger
  - drf-spectacular
  - drf-yasg
- API schema generation
- Documentation best practices

### GraphQL (Introduction)
- GraphQL vs REST
- Graphene-Django
- Queries, Mutations
- Schema definition

### Microservices Basics
- Monolith vs Microservices
- Service communication
  - REST APIs
  - Message queues
- Service boundaries
- API Gateway concept

## Testing
### Unit Testing Advanced
- Test organization
- Fixtures
- Mocking
  - unittest.mock
  - @patch decorator
  - MagicMock
- Factory Boy
  - Factories for models
  - Faker integration

### Integration Testing
- Testing with database
- TransactionTestCase
- Testing APIs
  - APIClient
  - Testing authentication
  - Testing permissions

### Test Coverage
- coverage.py
- Coverage reports
- Coverage thresholds
- Branch coverage

### TDD (Test-Driven Development)
- Red-Green-Refactor
- Writing tests first
- TDD benefits & challenges

### Performance Testing
- Load testing basics
  - Locust
  - Apache JMeter
- Profiling
  - cProfile
  - line_profiler

## DevOps & Deployment
### Docker
- Dockerfile
- docker-compose
- Containers vs VMs
- Image optimization
- Multi-stage builds
- Docker networking
- Volumes

### CI/CD
- GitHub Actions
- GitLab CI
- Jenkins (basics)
- Automated testing
- Deployment pipelines

### Web Servers
- Nginx
  - Reverse proxy
  - Static file serving
  - SSL/TLS configuration
- Gunicorn/uWSGI
  - Workers
  - Configuration
  - Performance tuning

### Cloud Platforms (Basics)
- AWS
  - EC2
  - RDS
  - S3
  - Elastic Beanstalk
- Heroku
- DigitalOcean

### Monitoring & Logging
- Logging
  - Python logging module
  - Log levels
  - Log formatting
  - Centralized logging (ELK stack basics)
- Monitoring
  - Sentry (error tracking)
  - New Relic / DataDog basics
  - Uptime monitoring

### Environment Management
- Environment separation
  - Development, Staging, Production
- Configuration management
  - Environment variables
  - Settings files structure
- Secrets management

## Message Queues
### RabbitMQ
- AMQP protocol
- Exchanges, Queues, Bindings
- Message routing
- Celery with RabbitMQ

### Redis as Message Broker
- Pub/Sub
- Streams
- Celery with Redis

## Soft Skills
### Code Review
- Giving constructive feedback
- Code review best practices
- Reviewing for security & performance

### Mentoring
- Helping junior developers
- Knowledge sharing
- Pair programming

### System Design (Intermediate)
- Breaking down requirements
- Component interaction
- Database schema design
- API design decisions

### Agile Methodologies
- Scrum/Kanban
- Sprint planning
- Retrospectives
- Story estimation
