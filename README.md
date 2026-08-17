# Awesome Flask [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A micro web framework for Python and the extension ecosystem around it.

Tutorials, talks, and videos on this list are free. Paid courses are not accepted.

<p align="right">
  <a href="https://flask.palletsprojects.com/">
    <img src="flask-icon.svg" width="72" alt="Flask">
  </a>
</p>

## Contents

- [Official Resources](#official-resources)
- [Extensions](#extensions)
  - [Admin](#admin)
  - [APIs](#apis)
  - [Auth](#auth)
  - [Cache](#cache)
  - [Databases](#databases)
  - [Developer Tools](#developer-tools)
  - [Email](#email)
  - [Forms and Validation](#forms-and-validation)
  - [Full-text Search](#full-text-search)
  - [Security](#security)
  - [Task Queues](#task-queues)
  - [Utils](#utils)
- [Resources](#resources)
  - [Community](#community)
  - [Tutorials](#tutorials)
  - [Books](#books)
  - [Talks](#talks)
  - [Videos](#videos)
- [Projects](#projects)
  - [Boilerplates](#boilerplates)
  - [Open Source Projects](#open-source-projects)
- [Hosting](#hosting)

## Official Resources

- [Flask](https://flask.palletsprojects.com/) - Official documentation for current and past releases.
- [Flaskr Tutorial](https://flask.palletsprojects.com/tutorial/) - Official tutorial that builds a small blog.
- [Source Code](https://github.com/pallets/flask) - Flask itself, hosted by Pallets.
- [Pallets-Eco](https://github.com/pallets-eco) - Community extensions maintained next to the core projects.
- [Quart](https://github.com/pallets/quart) - Official ASGI counterpart of Flask, with a compatible API.

## Extensions

### Admin

- [Flask-Admin](https://github.com/pallets-eco/flask-admin) - Extensible admin interface for managing application data.

### APIs

- [APIFlask](https://github.com/apiflask/apiflask) - Flask web API framework with marshmallow validation and OpenAPI generation.
- [Connexion](https://github.com/spec-first/connexion) - Spec-first OpenAPI framework that can run on Flask.
- [Eve](https://github.com/pyeve/eve) - REST API framework powered by Flask and MongoDB.
- [Flasgger](https://github.com/flasgger/flasgger) - OpenAPI and Swagger UI for Flask views.
- [Flask-Rebar](https://github.com/plangrid/flask-rebar) - Flask, marshmallow, and OpenAPI combined for REST services.
- [Flask-RESTful](https://github.com/flask-restful/flask-restful) - Lightweight helpers for building REST APIs.
- [Flask-RESTX](https://github.com/python-restx/flask-restx) - Community fork of Flask-RESTPlus with Swagger documentation.
- [flask-smorest](https://github.com/marshmallow-code/flask-smorest) - Marshmallow-first REST framework with automatic OpenAPI.

### Auth

- [Authlib](https://github.com/authlib/authlib) - OAuth 1, OAuth 2, and OpenID Connect clients and servers.
- [Authomatic](https://github.com/authomatic/authomatic) - Framework-agnostic OAuth and OpenID client.
- [Flask-Dance](https://github.com/singingwolfboy/flask-dance) - OAuth consumer with built-in providers such as GitHub and Google.
- [Flask-HTTPAuth](https://github.com/miguelgrinberg/Flask-HTTPAuth) - Basic, digest, and token authentication for routes.
- [Flask-JWT-Extended](https://github.com/vimalloc/flask-jwt-extended) - JWT authentication with refresh tokens and fine-grained claims.
- [Flask-Login](https://github.com/maxcountryman/flask-login) - Session-based user login management.
- [Flask-Praetorian](https://github.com/dusktreader/flask-praetorian) - JWT authentication and role-based authorization for APIs.
- [Flask-Pundit](https://github.com/anurag90x/flask-pundit) - Policy-based authorization inspired by Rails Pundit.
- [Flask-Security](https://github.com/pallets-eco/flask-security) - Account management, authentication, and authorization. Continues Flask-Security-Too.
- [Flask-Session](https://github.com/pallets-eco/flask-session) - Server-side sessions for Flask.
- [Flask-User](https://github.com/lingthio/Flask-User) - Customizable user registration, login, and account management.

### Cache

- [Flask-Caching](https://github.com/pallets-eco/flask-caching) - Caching support with multiple backends.

### Databases

- [Flask-Alembic](https://github.com/pallets-eco/flask-alembic) - Alembic migrations wired to a Flask-SQLAlchemy database.
- [Flask-Migrate](https://github.com/miguelgrinberg/Flask-Migrate) - Database migrations for Flask-SQLAlchemy via Alembic.
- [Flask-MongoEngine](https://github.com/MongoEngine/flask-mongoengine) - MongoEngine integration with WTForms support.
- [Flask-PyMongo](https://github.com/mongodb-labs/flask-pymongo) - PyMongo integration for MongoDB.
- [Flask-SQLAlchemy](https://github.com/pallets-eco/flask-sqlalchemy) - SQLAlchemy integration for Flask.
- [Advanced Alchemy](https://github.com/litestar-org/advanced-alchemy) - SQLAlchemy companion with repositories, Alembic helpers, and a first-party Flask extension.

### Developer Tools

- [Elastic APM](https://github.com/elastic/apm-agent-python) - Application performance monitoring for Flask.
- [Flask-DebugToolbar](https://github.com/pallets-eco/flask-debugtoolbar) - In-browser debug toolbar, ported from Django.
- [Flask-MonitoringDashboard](https://github.com/flask-dashboard/Flask-MonitoringDashboard) - Automatic performance monitoring for Flask services.
- [Flask-Testing](https://github.com/jarus/flask-testing) - Unittest helpers for Flask applications.
- [Mixer](https://github.com/klen/mixer) - Object factory for SQLAlchemy and Django models.
- [nplusone](https://github.com/jmcarp/nplusone) - Detects N+1 queries when using Flask-SQLAlchemy.
- [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-python-contrib) - Tracing and metrics instrumentation, including Flask.
- [pytest-flask](https://github.com/pytest-dev/pytest-flask) - Pytest fixtures for Flask applications.
- [Sentry](https://github.com/getsentry/sentry-python) - Error tracking SDK with a Flask integration.

### Email

- [Flask-Mail](https://github.com/pallets-eco/flask-mail) - SMTP email sending for Flask.
- [Flask-Mailman](https://github.com/waynerv/flask-mailman) - Port of Django's mail system to Flask.

### Forms and Validation

- [Flask-Marshmallow](https://github.com/marshmallow-code/flask-marshmallow) - Marshmallow integration for serialization and validation.
- [Flask-Pydantic](https://github.com/pallets-eco/flask-pydantic) - Pydantic validation for Flask views.
- [Flask-WTF](https://github.com/pallets-eco/flask-wtf) - WTForms integration with CSRF, file upload, and reCAPTCHA.

### Full-text Search

- [flask-msearch](https://github.com/honmaple/flask-msearch) - Full-text search for Flask, with Whoosh support.
- [SQLAlchemy-Searchable](https://github.com/falcony-io/sqlalchemy-searchable) - Full-text search for SQLAlchemy models on PostgreSQL.

### Security

- [Flask-Bcrypt](https://github.com/maxcountryman/flask-bcrypt) - Bcrypt password hashing.
- [Flask-CORS](https://github.com/corydolphin/flask-cors) - Cross-Origin Resource Sharing (CORS) support.
- [Flask-Limiter](https://github.com/alisaifee/flask-limiter) - Rate limiting for Flask routes.
- [Flask-SeaSurf](https://github.com/maxcountryman/flask-seasurf) - CSRF protection for Flask.
- [Flask-Talisman](https://github.com/wntrblm/flask-talisman) - HTTPS enforcement and security headers.

### Task Queues

- [Celery](https://github.com/celery/celery) - Distributed task queue commonly used with Flask.
- [Dramatiq](https://github.com/Bogdanp/dramatiq) - Fast alternative to Celery, with [Flask-Dramatiq](https://flask-dramatiq.readthedocs.io/) available.
- [Flask-RQ](https://github.com/pallets-eco/flask-rq) - Redis Queue (RQ) integration for Flask and Quart.
- [Huey](https://github.com/coleifer/huey) - Small Redis-backed task queue.

### Utils

- [Flask-Assets](https://github.com/miracle2k/flask-assets) - Webassets integration for bundling and minifying static files.
- [Flask-Babel](https://github.com/python-babel/flask-babel) - Internationalization and localization via Babel.
- [Flask-GoogleMaps](https://github.com/flask-extensions/Flask-GoogleMaps) - Embed Google Maps in Flask templates.
- [flask-graphql](https://github.com/graphql-python/flask-graphql) - GraphQL support for Flask.
- [Flask-HTMLmin](https://github.com/hamidfzm/Flask-HTMLmin) - HTML minification for Flask responses.
- [flask-jsonrpc](https://github.com/cenobites/flask-jsonrpc) - JSON-RPC support for Flask.
- [Flask-Moment](https://github.com/miguelgrinberg/Flask-Moment) - Moment.js helpers for dates in Jinja templates.
- [Flask-Paginate](https://github.com/lixxu/flask-paginate) - Pagination helpers for Flask.
- [flask-s3](https://github.com/e-dard/flask-s3) - Serve Flask static assets from Amazon S3.
- [Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) - Socket.IO integration for Flask.
- [Frozen-Flask](https://github.com/Frozen-Flask/Frozen-Flask) - Freezes a Flask app into a static site.

## Resources

### Community

- [Discord](https://discord.gg/pallets) - Pallets community server. Use the Flask help channels.
- [Reddit](https://www.reddit.com/r/flask/) - Flask subreddit.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/flask) - Questions tagged `flask`.

### Tutorials

- [The Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world) - Long-form series covering a full Flask application.
- [Discover Flask](https://github.com/realpython/discover-flask) - Full-stack Flask series from Real Python.
- [Flaskr TDD](https://github.com/mjhea0/flaskr-tdd) - Introduction to Flask, test-driven development, and JavaScript.

### Books

- [Explore Flask](https://explore-flask.readthedocs.io/en/latest/) - Free book on Flask patterns and project structure.
- [Flask Web Development](https://www.oreilly.com/library/view/flask-web-development/9781491991725/) - O'Reilly book by Miguel Grinberg that builds a real application.

### Talks

- [Advanced Flask Patterns](https://speakerdeck.com/mitsuhiko/advanced-flask-patterns) - Patterns from Armin Ronacher.
- [Flasky Goodness](https://speakerdeck.com/kennethreitz/flasky-goodness) - Talk by Kenneth Reitz.
- [Domain Driven Design with Flask](https://speakerdeck.com/mikedebo/domain-driven-design-dot-dot-dot-with-flask) - Applying DDD ideas in Flask.

### Videos

- [PyVideo](https://pyvideo.org/search.html?q=flask) - Conference talks tagged Flask.
- [Python Flask Tutorial](https://www.youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH) - Full-featured web app series by Corey Schafer.

## Projects

### Boilerplates

- [cookiecutter-flask](https://github.com/cookiecutter-flask/cookiecutter-flask) - Cookiecutter template with Bootstrap, Webpack, and authentication.
- [fbone](https://github.com/imwilsonxu/fbone) - Classic Flask skeleton with a structured application layout.
- [Flask-AppBuilder](https://github.com/dpgaspar/Flask-AppBuilder) - Rapid app builder with security, auto CRUD, and charts.
- [Flask-Foundation](https://github.com/JackStouffer/Flask-Foundation) - Best-practice starter application.
- [uwsgi-nginx-flask-docker](https://github.com/tiangolo/uwsgi-nginx-flask-docker) - Docker image with uWSGI, Nginx, and Flask.

### Open Source Projects

- [Apache Airflow](https://github.com/apache/airflow) - Platform to author, schedule, and monitor workflows.
- [Apache Superset](https://github.com/apache/superset) - Data exploration and visualization platform.
- [FlaskBB](https://github.com/flaskbb/flaskbb) - Classic forum software built with Flask.
- [Indico](https://github.com/indico/indico) - Event management system developed at CERN.
- [PythonBuddy](https://github.com/ethanchewy/PythonBuddy) - Online Python editor with live syntax checking.
- [Redash](https://github.com/getredash/redash) - Query and visualize data from many sources.
- [SecureDrop](https://github.com/freedomofpress/securedrop) - Whistleblower submission system for newsrooms.
- [SimpleLogin](https://github.com/simple-login/app) - Email alias service that protects personal inboxes.
- [SkyLines](https://github.com/skylines-project/skylines) - Live tracking and flight database for gliding.
- [Timesketch](https://github.com/google/timesketch) - Collaborative forensic timeline analysis.

## Hosting

- [Flask Deployment Options](https://flask.palletsprojects.com/en/stable/deploying/) - Official notes on WSGI servers and platforms.
- [Fly.io](https://fly.io/docs/python/frameworks/flask/) - Deploy Flask close to users on Fly Machines.
- [Google Cloud Run](https://cloud.google.com/run/docs/quickstarts/build-and-deploy/deploy-python-service) - Container hosting that works well with Flask.
- [PythonAnywhere](https://help.pythonanywhere.com/pages/Flask/) - Hosted Python environment with first-class Flask support.
- [Render](https://render.com/docs/deploy-flask) - Web services and background workers for Flask.
- [Zappa](https://github.com/zappa/Zappa) - Deploy WSGI apps to AWS Lambda and API Gateway.

## Contributing

Suggestions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) first. Historical and unmaintained entries live in [archived.md](archived.md).
