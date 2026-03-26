# Awesome Python with stars

An opinionated list of Python frameworks, libraries, tools, and resources.

# **Sponsors**

> The **#10 most-starred repo on GitHub**. Put your product in front of Python developers. [Become a sponsor](origin/SPONSORSHIP.md).

# Categories

**AI & ML**

* [AI and Agents](#ai-and-agents)
* [Deep Learning](#deep-learning)
* [Machine Learning](#machine-learning)
* [Natural Language Processing](#natural-language-processing)
* [Computer Vision](#computer-vision)
* [Recommender Systems](#recommender-systems)

**Web Development**

* [Web Frameworks](#web-frameworks)
* [Web APIs](#web-apis)
* [Web Servers](#web-servers)
* [WebSocket](#websocket)
* [Template Engines](#template-engines)
* [Web Asset Management](#web-asset-management)
* [Authentication](#authentication)
* [Admin Panels](#admin-panels)
* [CMS](#cms)
* [Static Site Generators](#static-site-generators)

**HTTP & Scraping**

* [HTTP Clients](#http-clients)
* [Web Scraping](#web-scraping)
* [Email](#email)

**Database & Storage**

* [ORM](#orm)
* [Database Drivers](#database-drivers)
* [Database](#database)
* [Caching](#caching)
* [Search](#search)
* [Serialization](#serialization)

**Data & Science**

* [Data Analysis](#data-analysis)
* [Data Validation](#data-validation)
* [Data Visualization](#data-visualization)
* [Geolocation](#geolocation)
* [Science](#science)
* [Quantum Computing](#quantum-computing)

**Developer Tools**

* [Algorithms and Design Patterns](#algorithms-and-design-patterns)
* [Interactive Interpreter](#interactive-interpreter)
* [Code Analysis](#code-analysis)
* [Testing](#testing)
* [Debugging Tools](#debugging-tools)
* [Build Tools](#build-tools)
* [Documentation](#documentation)

**DevOps**

* [DevOps Tools](#devops-tools)
* [Distributed Computing](#distributed-computing)
* [Task Queues](#task-queues)
* [Job Schedulers](#job-schedulers)
* [Logging](#logging)
* [Network Virtualization](#network-virtualization)

**CLI & GUI**

* [Command-line Interface Development](#command-line-interface-development)
* [Command-line Tools](#command-line-tools)
* [GUI Development](#gui-development)

**Text & Documents**

* [Text Processing](#text-processing)
* [HTML Manipulation](#html-manipulation)
* [File Format Processing](#file-format-processing)
* [File Manipulation](#file-manipulation)

**Media**

* [Image Processing](#image-processing)
* [Audio & Video Processing](#audio--video-processing)
* [Game Development](#game-development)

**Python Language**

* [Implementations](#implementations)
* [Built-in Classes Enhancement](#built-in-classes-enhancement)
* [Functional Programming](#functional-programming)
* [Asynchronous Programming](#asynchronous-programming)
* [Date and Time](#date-and-time)

**Python Toolchain**

* [Environment Management](#environment-management)
* [Package Management](#package-management)
* [Package Repositories](#package-repositories)
* [Distribution](#distribution)
* [Configuration Files](#configuration-files)

**Security**

* [Cryptography](#cryptography)
* [Penetration Testing](#penetration-testing)

**Miscellaneous**

* [Hardware](#hardware)
* [Microsoft Windows](#microsoft-windows)
* [Miscellaneous](#miscellaneous)

***

**AI & ML**

## AI and Agents

*Libraries for building AI applications, LLM integrations, and autonomous agents.*

* Pre-trained Models and Inference
  * [transformers](https://github.com/huggingface/transformers) ⭐ 158,422 | 🐛 2,286 | 🌐 Python | 📅 2026-03-25 - A framework that lets you easily use pre-trained transformer models for NLP, vision, and audio tasks.
  * [vllm](https://github.com/vllm-project/vllm) ⭐ 74,345 | 🐛 3,891 | 🌐 Python | 📅 2026-03-26 - A high-throughput and memory-efficient inference and serving engine for LLMs.
  * [diffusers](https://github.com/huggingface/diffusers) ⭐ 33,164 | 🐛 943 | 🌐 Python | 📅 2026-03-26 - A library that provides pre-trained diffusion models for generating and editing images, audio, and video.
* Orchestration
  * [langchain](https://github.com/langchain-ai/langchain) ⭐ 131,116 | 🐛 498 | 🌐 Python | 📅 2026-03-26 - Building applications with LLMs through composability.
  * [autogen](https://github.com/microsoft/autogen) ⭐ 56,218 | 🐛 703 | 🌐 Python | 📅 2026-03-26 - A programming framework for building agentic AI applications.
  * [crewai](https://github.com/crewAIInc/crewAI) ⭐ 47,232 | 🐛 449 | 🌐 Python | 📅 2026-03-26 - A framework for orchestrating role-playing autonomous AI agents for collaborative task solving.
  * [dspy](https://github.com/stanfordnlp/dspy) ⭐ 33,180 | 🐛 472 | 🌐 Python | 📅 2026-03-26 - A framework for programming, not prompting, language models.
  * [pydantic-ai](https://github.com/pydantic/pydantic-ai) ⭐ 15,785 | 🐛 613 | 🌐 Python | 📅 2026-03-26 - A Python agent framework for building generative AI applications with structured schemas.
* Data Layer
  * [mem0](https://github.com/mem0ai/mem0) ⭐ 51,075 | 🐛 533 | 🌐 Python | 📅 2026-03-25 - An intelligent memory layer for AI agents enabling personalized interactions.
  * [llama-index](https://github.com/run-llama/llama_index) ⭐ 47,991 | 🐛 255 | 🌐 Python | 📅 2026-03-25 - A data framework for your LLM application.
  * [instructor](https://github.com/567-labs/instructor) ⭐ 12,600 | 🐛 107 | 🌐 Python | 📅 2026-03-23 - A library for extracting structured data from LLMs, powered by Pydantic.
* Agent Skills
  * [trailofbits-skills](https://github.com/trailofbits/skills) ⭐ 3,921 | 🐛 22 | 🌐 Python | 📅 2026-03-25 - Python-friendly security skills for auditing, testing, and safer backend development.
  * [sentry-skills](https://github.com/getsentry/skills) ⭐ 467 | 🐛 16 | 🌐 Python | 📅 2026-03-25 - Python-focused engineering skills for code review, debugging, and backend workflows.
  * [django-ai-plugins](https://github.com/vintasoftware/django-ai-plugins) ⭐ 31 | 🐛 0 | 📅 2026-03-09 - Django backend agent skills for Django, DRF, Celery, and Django-specific code review.

## Deep Learning

*Frameworks for Neural Networks and Deep Learning. Also see [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning) ⭐ 27,763 | 🐛 58 | 📅 2025-05-26.*

* [tensorflow](https://github.com/tensorflow/tensorflow) ⭐ 194,345 | 🐛 3,988 | 🌐 C++ | 📅 2026-03-26 - The most popular Deep Learning framework created by Google.
* [pytorch](https://github.com/pytorch/pytorch) ⭐ 98,577 | 🐛 18,117 | 🌐 Python | 📅 2026-03-26 - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
* [keras](https://github.com/keras-team/keras) ⭐ 63,928 | 🐛 286 | 🌐 Python | 📅 2026-03-26 - A high-level deep learning library with support for JAX, TensorFlow, and PyTorch backends.
* [jax](https://github.com/jax-ml/jax) ⭐ 35,228 | 🐛 2,260 | 🌐 Python | 📅 2026-03-26 - a library for high-performance numerical computing with automatic differentiation and JIT compilation.
* [pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning) ⭐ 30,969 | 🐛 973 | 🌐 Python | 📅 2026-03-25 - Deep learning framework to train, deploy, and ship AI products Lightning fast.
* [stable-baselines3](https://github.com/DLR-RM/stable-baselines3) ⭐ 12,971 | 🐛 77 | 🌐 Python | 📅 2026-03-18 - PyTorch implementations of Stable Baselines (deep) reinforcement learning algorithms.

## Machine Learning

*Libraries for Machine Learning. Also see [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python) ⭐ 72,086 | 🐛 29 | 🌐 Python | 📅 2026-03-15.*

* [scikit-learn](https://github.com/scikit-learn/scikit-learn) ⭐ 65,527 | 🐛 2,146 | 🌐 Python | 📅 2026-03-25 - The most popular Python library for Machine Learning with extensive documentation and community support.
* [spark.ml](https://github.com/apache/spark) ⭐ 43,041 | 🐛 297 | 🌐 Scala | 📅 2026-03-26 - [Apache Spark](https://spark.apache.org/)'s scalable [Machine Learning library](https://spark.apache.org/docs/latest/ml-guide.html) for distributed computing.
* [mindsdb](https://github.com/mindsdb/mindsdb) ⭐ 38,837 | 🐛 133 | 🌐 Python | 📅 2026-03-26 - MindsDB is an open source AI layer for existing databases that allows you to effortlessly develop, train and deploy state-of-the-art machine learning models using standard queries.
* [xgboost](https://github.com/dmlc/xgboost) ⭐ 28,180 | 🐛 459 | 🌐 C++ | 📅 2026-03-25 - A scalable, portable, and distributed gradient boosting library.
* [lightgbm](https://github.com/lightgbm-org/LightGBM) ⭐ 18,195 | 🐛 500 | 🌐 C++ | 📅 2026-03-25 - A fast, distributed, high performance gradient boosting framework.
* [catboost](https://github.com/catboost/catboost) ⭐ 8,861 | 🐛 689 | 🌐 C++ | 📅 2026-03-25 - A fast, scalable, high performance gradient boosting on decision trees library.
* [h2o](https://github.com/h2oai/h2o-3) ⭐ 7,522 | 🐛 2,883 | 🌐 Jupyter Notebook | 📅 2026-03-26 - Open Source Fast Scalable Machine Learning Platform.
* [pgmpy](https://github.com/pgmpy/pgmpy) ⭐ 3,226 | 🐛 527 | 🌐 Python | 📅 2026-03-25 - A Python library for probabilistic graphical models and Bayesian networks.
* [feature\_engine](https://github.com/feature-engine/feature_engine) ⭐ 2,219 | 🐛 82 | 🌐 Python | 📅 2026-03-09 - sklearn compatible API with the widest toolset for feature engineering and selection.

## Natural Language Processing

*Libraries for working with human languages.*

* Chinese
  * [funnlp](https://github.com/fighting41love/funNLP) ⭐ 79,613 | 🐛 44 | 🌐 Python | 📅 2024-05-10 - A collection of tools and datasets for Chinese NLP.
  * [jieba](https://github.com/fxsjy/jieba) ⭐ 34,820 | 🐛 700 | 🌐 Python | 📅 2024-08-21 - The most popular Chinese text segmentation library.
* General
  * [spacy](https://github.com/explosion/spaCy) ⭐ 33,386 | 🐛 191 | 🌐 Python | 📅 2026-03-23 - A library for industrial-strength natural language processing in Python and Cython.
  * [gensim](https://github.com/piskvorky/gensim) ⭐ 16,380 | 🐛 435 | 🌐 Python | 📅 2025-11-01 - Topic Modeling for Humans.
  * [nltk](https://github.com/nltk/nltk) ⭐ 14,575 | 🐛 278 | 🌐 Python | 📅 2026-03-24 - A leading platform for building Python programs to work with human language data.
  * [stanza](https://github.com/stanfordnlp/stanza) ⭐ 7,753 | 🐛 90 | 🌐 Python | 📅 2026-03-25 - The Stanford NLP Group's official Python library, supporting 60+ languages.

## Computer Vision

*Libraries for Computer Vision.*

* [easyocr](https://github.com/JaidedAI/EasyOCR) ⭐ 29,156 | 🐛 526 | 🌐 Python | 📅 2025-12-05 - Ready-to-use OCR with 40+ languages supported.
* [kornia](https://github.com/kornia/kornia/) ⭐ 11,138 | 🐛 70 | 🌐 Python | 📅 2026-03-25 - Open Source Differentiable Computer Vision Library for PyTorch.
* [pytesseract](https://github.com/madmaze/pytesseract) ⭐ 6,324 | 🐛 20 | 🌐 Python | 📅 2026-03-16 - A wrapper for [Google Tesseract OCR](https://github.com/tesseract-ocr).
* [opencv](https://github.com/opencv/opencv-python) ⭐ 5,217 | 🐛 199 | 🌐 Python | 📅 2026-02-03 - Open Source Computer Vision Library.

## Recommender Systems

*Libraries for building recommender systems.*

* [annoy](https://github.com/spotify/annoy) ⭐ 14,187 | 🐛 76 | 🌐 C++ | 📅 2025-10-29 - Approximate Nearest Neighbors in C++/Python optimized for memory usage.
* [scikit-surprise](https://github.com/NicolasHug/Surprise) ⭐ 6,781 | 🐛 92 | 🌐 Python | 📅 2025-07-24 - A scikit for building and analyzing recommender systems.
* [implicit](https://github.com/benfred/implicit) ⭐ 3,779 | 🐛 106 | 🌐 Python | 📅 2024-07-11 - A fast Python implementation of collaborative filtering for implicit datasets.

**Web Development**

## Web Frameworks

*Traditional full stack web frameworks. Also see [Web APIs](#web-apis).*

* Synchronous
  * [django](https://github.com/django/django) ⭐ 87,122 | 🐛 424 | 🌐 Python | 📅 2026-03-25 - The most popular web framework in Python.
    * [awesome-django](https://github.com/shahraizali/awesome-django) ⭐ 1,900 | 🐛 7 | 📅 2026-03-22
  * [flask](https://github.com/pallets/flask) ⭐ 71,380 | 🐛 3 | 🌐 Python | 📅 2026-03-24 - A microframework for Python.
    * [awesome-flask](https://github.com/humiaozuzu/awesome-flask) ⭐ 12,701 | 🐛 69 | 📅 2024-08-18
  * [bottle](https://github.com/bottlepy/bottle) ⭐ 8,770 | 🐛 283 | 🌐 Python | 📅 2026-03-23 - A fast and simple micro-framework distributed as a single file with no dependencies.
  * [fasthtml](https://github.com/AnswerDotAI/fasthtml) ⭐ 6,896 | 🐛 56 | 🌐 Jupyter Notebook | 📅 2026-03-25 - The fastest way to create an HTML app.
    * [awesome-fasthtml](https://github.com/amosgyamfi/awesome-fasthtml) ⭐ 79 | 🐛 3 | 🌐 Python | 📅 2024-09-08
  * [pyramid](https://github.com/Pylons/pyramid) ⭐ 4,079 | 🐛 83 | 🌐 Python | 📅 2026-03-11 - A small, fast, down-to-earth, open source Python web framework.
    * [awesome-pyramid](https://github.com/uralbash/awesome-pyramid) ⭐ 570 | 🐛 0 | 📅 2021-07-08
  * [masonite](https://github.com/MasoniteFramework/masonite) ⭐ 2,364 | 🐛 24 | 🌐 Python | 📅 2025-03-25 - The modern and developer centric Python web framework.
* Asynchronous
  * [reflex](https://github.com/reflex-dev/reflex) ⭐ 28,263 | 🐛 292 | 🌐 Python | 📅 2026-03-26 – A framework for building reactive, full-stack web applications entirely with python .
  * [tornado](https://github.com/tornadoweb/tornado) ⭐ 22,409 | 🐛 211 | 🌐 Python | 📅 2026-03-23 - A web framework and asynchronous networking library.
  * [starlette](https://github.com/Kludex/starlette) ⭐ 12,120 | 🐛 49 | 🌐 Python | 📅 2026-03-22 - A lightweight ASGI framework and toolkit for building high-performance async services.
  * [litestar](https://github.com/litestar-org/litestar) ⭐ 8,119 | 🐛 280 | 🌐 Python | 📅 2026-03-25 - Production-ready, capable and extensible ASGI Web framework.
  * [robyn](https://github.com/sparckles/Robyn) ⭐ 7,170 | 🐛 166 | 🌐 Python | 📅 2026-03-23 - A high-performance async Python web framework with a Rust runtime.
  * [microdot](https://github.com/miguelgrinberg/microdot) ⭐ 2,095 | 🐛 8 | 🌐 Python | 📅 2026-03-10 - The impossibly small web framework for Python and MicroPython.

## Web APIs

*Libraries for building RESTful and GraphQL APIs.*

* Framework Agnostic
  * [fastapi](https://github.com/fastapi/fastapi) ⭐ 96,565 | 🐛 164 | 🌐 Python | 📅 2026-03-24 - A modern, fast, web framework for building APIs with standard Python type hints.
  * [sanic](https://github.com/sanic-org/sanic) ⭐ 18,639 | 🐛 125 | 🌐 Python | 📅 2026-01-07 - A Python 3.6+ web server and web framework that's written to go fast.
  * [falcon](https://github.com/falconry/falcon) ⭐ 9,804 | 🐛 164 | 🌐 Python | 📅 2026-03-10 - A high-performance framework for building cloud APIs and web app backends.
  * [strawberry](https://github.com/strawberry-graphql/strawberry) ⭐ 4,635 | 🐛 447 | 🌐 Python | 📅 2026-03-25 - A GraphQL library that leverages Python type annotations for schema definition.
  * [connexion](https://github.com/spec-first/connexion) ⭐ 4,577 | 🐛 177 | 🌐 Python | 📅 2026-03-02 - A spec-first framework that automatically handles requests based on your OpenAPI specification.
  * [webargs](https://github.com/marshmallow-code/webargs) ⭐ 1,405 | 🐛 6 | 🌐 Python | 📅 2026-03-16 - A friendly library for parsing HTTP request arguments with built-in support for popular web frameworks.
* Django
  * [django-rest-framework](https://github.com/encode/django-rest-framework) ⭐ 29,941 | 🐛 78 | 🌐 Python | 📅 2026-03-24 - A powerful and flexible toolkit to build web APIs.
  * [django-ninja](https://github.com/vitalik/django-ninja) ⭐ 8,967 | 🐛 218 | 🌐 Python | 📅 2026-03-18 - Fast, Django REST framework based on type hints and Pydantic.
  * [strawberry-django](https://github.com/strawberry-graphql/strawberry-django) ⭐ 488 | 🐛 93 | 🌐 Python | 📅 2026-03-23 - Strawberry GraphQL integration with Django.
* Flask
  * [apiflask](https://github.com/apiflask/apiflask) ⭐ 1,124 | 🐛 33 | 🌐 Python | 📅 2026-03-21 - A lightweight Python web API framework based on Flask and Marshmallow.

## Web Servers

*ASGI and WSGI compatible web servers.*

* RPC
  * [grpcio](https://github.com/grpc/grpc) ⭐ 44,547 | 🐛 1,216 | 🌐 C++ | 📅 2026-03-25 - HTTP/2-based RPC framework with Python bindings, built by Google.
  * [rpyc](https://github.com/tomerfiliba-org/rpyc) ⭐ 1,694 | 🐛 95 | 🌐 Python | 📅 2025-08-14 (Remote Python Call) - A transparent and symmetric RPC library for Python.
* ASGI
  * [uvicorn](https://github.com/Kludex/uvicorn) ⭐ 10,527 | 🐛 85 | 🌐 Python | 📅 2026-03-16 - A lightning-fast ASGI server implementation, using uvloop and httptools.
  * [granian](https://github.com/emmett-framework/granian) ⭐ 5,185 | 🐛 39 | 🌐 Rust | 📅 2026-03-22 - A Rust HTTP server for Python applications built on top of Hyper and Tokio, supporting WSGI/ASGI/RSGI.
  * [daphne](https://github.com/django/daphne) ⭐ 2,654 | 🐛 38 | 🌐 Python | 📅 2026-01-05 - A HTTP, HTTP2 and WebSocket protocol server for ASGI and ASGI-HTTP.
  * [hypercorn](https://github.com/pgjones/hypercorn) ⭐ 1,539 | 🐛 128 | 🌐 Python | 📅 2025-11-08 - An ASGI and WSGI Server based on Hyper libraries and inspired by Gunicorn.
* WSGI
  * [gunicorn](https://github.com/benoitc/gunicorn) ⭐ 10,495 | 🐛 117 | 🌐 Python | 📅 2026-03-25 - Pre-forked, ported from Ruby's Unicorn project.
  * [uwsgi](https://github.com/unbit/uwsgi) ⭐ 3,543 | 🐛 873 | 🌐 C | 📅 2025-10-11 - A project aims at developing a full stack for building hosting services, written in C.
  * [waitress](https://github.com/Pylons/waitress) ⭐ 1,572 | 🐛 23 | 🌐 Python | 📅 2026-03-20 - Multi-threaded, powers Pyramid.

## WebSocket

*Libraries for working with WebSocket.*

* [channels](https://github.com/django/channels) ⭐ 6,338 | 🐛 119 | 🌐 Python | 📅 2026-03-07 - Developer-friendly asynchrony for Django.
* [websockets](https://github.com/python-websockets/websockets) ⭐ 5,647 | 🐛 19 | 🌐 Python | 📅 2026-03-08 - A library for building WebSocket servers and clients with a focus on correctness and simplicity.
* [flask-socketio](https://github.com/miguelgrinberg/Flask-SocketIO) ⭐ 5,508 | 🐛 7 | 🌐 Python | 📅 2026-02-21 - Socket.IO integration for Flask applications.
* [autobahn-python](https://github.com/crossbario/autobahn-python) ⭐ 2,534 | 🐛 193 | 🌐 Python | 📅 2026-01-14 - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html).

## Template Engines

*Libraries and tools for templating and lexing.*

* [jinja](https://github.com/pallets/jinja) ⭐ 11,523 | 🐛 97 | 🌐 Python | 📅 2025-06-14 - A modern and designer friendly templating language.
* [mako](https://github.com/sqlalchemy/mako) ⭐ 430 | 🐛 72 | 🌐 Python | 📅 2025-08-16 - Hyperfast and lightweight templating for the Python platform.

## Web Asset Management

*Tools for managing, compressing and minifying website assets.*

* [django-storages](https://github.com/jschneier/django-storages) ⭐ 2,941 | 🐛 181 | 🌐 Python | 📅 2025-06-18 - A collection of custom storage back ends for Django.
* [django-compressor](https://github.com/django-compressor/django-compressor) ⭐ 2,872 | 🐛 120 | 🌐 Python | 📅 2026-03-23 - Compresses linked and inline JavaScript or CSS into a single cached file.

## Authentication

*Libraries for implementing authentication schemes.*

* OAuth
  * [django-allauth](https://github.com/pennersr/django-allauth) ⭐ 10,310 | 🐛 1 | 🌐 Python | 📅 2026-03-09 - Authentication app for Django that "just works."
  * [authlib](https://github.com/authlib/authlib) ⭐ 5,255 | 🐛 131 | 🌐 Python | 📅 2026-03-25 - JavaScript Object Signing and Encryption draft implementation.
  * [django-oauth-toolkit](https://github.com/django-oauth/django-oauth-toolkit) ⭐ 3,312 | 🐛 147 | 🌐 Python | 📅 2026-03-13 - OAuth 2 goodies for Django.
  * [oauthlib](https://github.com/oauthlib/oauthlib) ⭐ 2,960 | 🐛 102 | 🌐 Python | 📅 2026-02-28 - A generic and thorough implementation of the OAuth request-signing logic.
* JWT
  * [pyjwt](https://github.com/jpadilla/pyjwt) ⭐ 5,630 | 🐛 41 | 🌐 Python | 📅 2026-03-23 - JSON Web Token implementation in Python.
* Permissions
  * [django-guardian](https://github.com/django-guardian/django-guardian) ⭐ 3,894 | 🐛 40 | 🌐 Python | 📅 2026-03-26 - Implementation of per object permissions for Django 1.2+
  * [django-rules](https://github.com/dfunckt/django-rules) ⭐ 1,971 | 🐛 41 | 🌐 Python | 📅 2025-10-11 - A tiny but powerful app providing object-level permissions to Django, without requiring a database.

## Admin Panels

*Libraries for administrative interfaces.*

* [ajenti](https://github.com/ajenti/ajenti) ⭐ 7,908 | 🐛 13 | 🌐 Python | 📅 2026-02-26 - The admin panel your servers deserve.
* [flower](https://github.com/mher/flower) ⭐ 7,135 | 🐛 189 | 🌐 Python | 📅 2026-03-26 - Real-time monitor and web admin for Celery.
* [flask-admin](https://github.com/pallets-eco/flask-admin) ⭐ 6,058 | 🐛 141 | 🌐 Python | 📅 2026-03-24 - Simple and extensible administrative interface framework for Flask.
* [django-grappelli](https://github.com/sehmaschine/django-grappelli) ⭐ 3,926 | 🐛 9 | 🌐 HTML | 📅 2026-01-29 - A jazzy skin for the Django Admin-Interface.
* [django-unfold](https://github.com/unfoldadmin/django-unfold) ⭐ 3,382 | 🐛 21 | 🌐 Python | 📅 2026-03-25 - Elevate your Django admin with a stunning modern interface, powerful features, and seamless user experience.
* [jet-bridge](https://github.com/jet-admin/jet-bridge) ⭐ 1,795 | 🐛 10 | 🌐 Python | 📅 2026-02-20 - Admin panel framework for any application with nice UI (ex Jet Django).
* [func-to-web](https://github.com/offerrall/FuncToWeb) ⭐ 394 | 🐛 2 | 🌐 Python | 📅 2026-01-20 - Instantly create web UIs from Python functions using type hints. Zero frontend code required.

## CMS

*Content Management Systems.*

* [wagtail](https://github.com/wagtail/wagtail) ⭐ 20,254 | 🐛 1,032 | 🌐 Python | 📅 2026-03-25 - A Django content management system.
* [django-cms](https://github.com/django-cms/django-cms) ⭐ 10,640 | 🐛 20 | 🌐 Python | 📅 2026-03-25 - The easy-to-use and developer-friendly enterprise CMS powered by Django.
* [indico](https://github.com/indico/indico) ⭐ 2,040 | 🐛 844 | 🌐 Python | 📅 2026-03-25 - A feature-rich event management system, made @ [CERN](https://en.wikipedia.org/wiki/CERN).

## Static Site Generators

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [pelican](https://github.com/getpelican/pelican) ⭐ 13,253 | 🐛 108 | 🌐 Python | 📅 2026-02-03 - Static site generator that supports Markdown and reST syntax.
* [lektor](https://github.com/lektor/lektor) ⭐ 3,925 | 🐛 249 | 🌐 Python | 📅 2026-03-25 - An easy to use static CMS and blog engine.
* [nikola](https://github.com/getnikola/nikola) ⭐ 2,726 | 🐛 94 | 🌐 Python | 📅 2026-03-23 - A static website and blog generator.

**HTTP & Scraping**

## HTTP Clients

*Libraries for working with HTTP.*

* [requests](https://github.com/psf/requests) ⭐ 53,873 | 🐛 285 | 🌐 Python | 📅 2026-03-25 - HTTP Requests for Humans.
* [aiohttp](https://github.com/aio-libs/aiohttp) ⭐ 16,384 | 🐛 277 | 🌐 Python | 📅 2026-03-26 - Asynchronous HTTP client/server framework for asyncio and Python.
* [httpx](https://github.com/encode/httpx) ⭐ 15,151 | 🐛 149 | 🌐 Python | 📅 2026-03-01 - A next generation HTTP client for Python.
* [urllib3](https://github.com/urllib3/urllib3) ⭐ 4,010 | 🐛 1,157 | 🌐 Python | 📅 2026-03-23 - A HTTP library with thread-safe connection pooling, file post support, sanity friendly.
* [furl](https://github.com/gruns/furl) ⭐ 2,798 | 🐛 45 | 🌐 Python | 📅 2026-02-22 - A small Python library that makes parsing and manipulating URLs easy.

## Web Scraping

*Libraries to automate web scraping and extract web content.*

* Frameworks
  * [browser-use](https://github.com/browser-use/browser-use) ⭐ 84,478 | 🐛 192 | 🌐 Python | 📅 2026-03-25 - Make websites accessible for AI agents with easy browser automation.
  * [crawl4ai](https://github.com/unclecode/crawl4ai) ⭐ 62,580 | 🐛 37 | 🌐 Python | 📅 2026-03-25 - An open-source, LLM-friendly web crawler that provides lightning-fast, structured data extraction specifically designed for AI agents.
  * [scrapy](https://github.com/scrapy/scrapy) ⭐ 60,963 | 🐛 649 | 🌐 Python | 📅 2026-03-25 - A fast high-level screen scraping and web crawling framework.
  * [mechanicalsoup](https://github.com/MechanicalSoup/MechanicalSoup) ⭐ 4,851 | 🐛 43 | 🌐 Python | 📅 2026-02-19 - A Python library for automating interaction with websites.
* Content Extraction
  * [trafilatura](https://github.com/adbar/trafilatura) ⭐ 5,593 | 🐛 105 | 🌐 Python | 📅 2025-09-12 - A tool for gathering text and metadata from the web, with built-in content filtering.
  * [sumy](https://github.com/miso-belica/sumy) ⭐ 3,669 | 🐛 28 | 🌐 Python | 📅 2026-02-14 - A module for automatic summarization of text documents and HTML pages.
  * [feedparser](https://github.com/kurtmckee/feedparser) ⭐ 2,336 | 🐛 100 | 🌐 Python | 📅 2026-03-02 - Universal feed parser.
  * [html2text](https://github.com/Alir3z4/html2text) ⭐ 2,136 | 🐛 92 | 🌐 Python | 📅 2025-10-28 - Convert HTML to Markdown-formatted text.
  * [micawber](https://github.com/coleifer/micawber) ⭐ 674 | 🐛 0 | 🌐 Python | 📅 2026-03-10 - A small library for extracting rich content from URLs.

## Email

*Libraries for sending and parsing email, and mail server management.*

* [modoboa](https://github.com/modoboa/modoboa) ⭐ 3,473 | 🐛 63 | 🌐 Python | 📅 2026-03-25 - A mail hosting and management platform including a modern Web UI.
* [yagmail](https://github.com/kootenpv/yagmail) ⭐ 2,724 | 🐛 110 | 🌐 Python | 📅 2022-09-28 - Yet another Gmail/SMTP client.

**Database & Storage**

## ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
  * [django.db.models](https://github.com/django/django) ⭐ 87,122 | 🐛 424 | 🌐 Python | 📅 2026-03-25 - The Django [ORM](https://docs.djangoproject.com/en/dev/topics/db/models/).
  * [sqlmodel](https://github.com/fastapi/sqlmodel) ⭐ 17,753 | 🐛 114 | 🌐 Python | 📅 2026-03-25 - SQLModel is based on Python type annotations, and powered by Pydantic and SQLAlchemy.
  * [peewee](https://github.com/coleifer/peewee) ⭐ 11,956 | 🐛 0 | 🌐 Python | 📅 2026-03-25 - A small, expressive ORM.
  * [sqlalchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 11,703 | 🐛 209 | 🌐 Python | 📅 2026-03-24 - The Python SQL Toolkit and Object Relational Mapper.
    * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) ⭐ 3,036 | 🐛 8 | 🌐 Python | 📅 2026-02-25
  * [tortoise-orm](https://github.com/tortoise/tortoise-orm) ⭐ 5,527 | 🐛 498 | 🌐 Python | 📅 2026-03-21 - An easy-to-use asyncio ORM inspired by Django, with relations support.
  * [dataset](https://github.com/pudo/dataset) ⭐ 4,854 | 🐛 44 | 🌐 Python | 📅 2025-02-05 - Store Python dicts in a database - works with SQLite, MySQL, and PostgreSQL.
  * [pony](https://github.com/ponyorm/pony/) ⭐ 3,826 | 🐛 360 | 🌐 Python | 📅 2025-07-03 - ORM that provides a generator-oriented interface to SQL.
* NoSQL Databases
  * [mongoengine](https://github.com/MongoEngine/mongoengine) ⭐ 4,349 | 🐛 347 | 🌐 Python | 📅 2026-03-10 - A Python Object-Document-Mapper for working with MongoDB.
  * [beanie](https://github.com/BeanieODM/beanie) ⭐ 2,666 | 🐛 88 | 🌐 Python | 📅 2026-03-26 - An asynchronous Python object-document mapper (ODM) for MongoDB.
  * [pynamodb](https://github.com/pynamodb/PynamoDB) ⭐ 2,647 | 🐛 318 | 🌐 Python | 📅 2026-01-06 - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/).

## Database Drivers

*Libraries for connecting and operating databases.*

* NoSQL Databases
  * [redis-py](https://github.com/redis/redis-py) ⭐ 13,526 | 🐛 88 | 🌐 Python | 📅 2026-03-25 - The Python client for Redis.
  * [pymongo](https://github.com/mongodb/mongo-python-driver) ⭐ 4,342 | 🐛 12 | 🌐 Python | 📅 2026-03-23 - The official Python client for MongoDB.
  * [cassandra-driver](https://github.com/apache/cassandra-python-driver) ⭐ 1,426 | 🐛 14 | 🌐 Python | 📅 2026-03-24 - The Python Driver for Apache Cassandra.
  * [django-mongodb-backend](https://github.com/mongodb/django-mongodb-backend) ⭐ 218 | 🐛 8 | 🌐 Python | 📅 2026-03-26 - Official MongoDB database backend for Django.
* PostgreSQL - [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres) ⭐ 11,788 | 🐛 30 | 📅 2026-02-22
  * [psycopg](https://github.com/psycopg/psycopg) ⭐ 2,330 | 🐛 48 | 🌐 Python | 📅 2026-03-19 - The most popular PostgreSQL adapter for Python.
* MySQL - [awesome-mysql](https://github.com/shlomi-noach/awesome-mysql) ⭐ 2,554 | 🐛 16 | 🌐 Python | 📅 2026-02-25
  * [pymysql](https://github.com/PyMySQL/PyMySQL) ⭐ 7,836 | 🐛 24 | 🌐 Python | 📅 2025-08-24 - A pure Python MySQL driver compatible to mysql-python.
  * [mysqlclient](https://github.com/PyMySQL/mysqlclient) ⭐ 2,524 | 🐛 9 | 🌐 Python | 📅 2026-02-12 - MySQL connector with Python 3 support ([mysql-python](https://sourceforge.net/projects/mysql-python/) fork).
* Other Relational Databases
  * [clickhouse-driver](https://github.com/mymarilyn/clickhouse-driver) ⭐ 1,293 | 🐛 81 | 🌐 Python | 📅 2025-11-17 - Python driver with native interface for ClickHouse.
  * [mssql-python](https://github.com/microsoft/mssql-python) ⭐ 404 | 🐛 42 | 🌐 Python | 📅 2026-03-25 - Official Microsoft driver for SQL Server and Azure SQL, built on ODBC for high performance and low memory usage.
* SQlite - [awesome-sqlite](https://github.com/planetopendata/awesome-sqlite) ⭐ 390 | 🐛 1 | 📅 2026-03-19
  * [sqlite-utils](https://github.com/simonw/sqlite-utils) ⭐ 2,020 | 🐛 138 | 🌐 Python | 📅 2026-01-21 - Python CLI utility and library for manipulating SQLite databases.
  * [sqlite3](https://docs.python.org/3/library/sqlite3.html) - (Python standard library) SQlite interface compliant with DB-API 2.0.

## Database

*Databases implemented in Python.*

* [duckdb](https://github.com/duckdb/duckdb) ⭐ 36,954 | 🐛 633 | 🌐 C++ | 📅 2026-03-25 - An in-process SQL OLAP database management system; optimized for analytics and fast queries, similar to SQLite but for analytical workloads.
* [chromadb](https://github.com/chroma-core/chroma) ⭐ 26,826 | 🐛 524 | 🌐 Rust | 📅 2026-03-26 - An open-source embedding database for building AI applications with embeddings and semantic search.
* [tinydb](https://github.com/msiemens/tinydb) ⭐ 7,493 | 🐛 9 | 🌐 Python | 📅 2026-01-17 - A tiny, document-oriented database.
* [pickledb](https://github.com/patx/pickledb) ⭐ 1,069 | 🐛 18 | 🌐 Python | 📅 2026-01-06 - A simple and lightweight key-value store for Python.
* [ZODB](https://github.com/zopefoundation/ZODB) ⭐ 752 | 🐛 76 | 🌐 Python | 📅 2026-03-23 - A native object database for Python. A key-value and object graph database.

## Caching

*Libraries for caching data.*

* [python-diskcache](https://github.com/grantjenks/python-diskcache) ⭐ 2,849 | 🐛 70 | 🌐 Python | 📅 2024-08-10 - SQLite and file backed cache backend with faster lookups than memcached and redis.
* [cachetools](https://github.com/tkem/cachetools) ⭐ 2,718 | 🐛 1 | 🌐 Python | 📅 2026-03-23 - Extensible memoizing collections and decorators.
* [django-cacheops](https://github.com/Suor/django-cacheops) ⭐ 2,265 | 🐛 21 | 🌐 Python | 📅 2026-03-04 - A slick ORM cache with automatic granular event-driven invalidation.
* [dogpile.cache](https://github.com/sqlalchemy/dogpile.cache) ⭐ 294 | 🐛 49 | 🌐 Python | 📅 2026-01-12 - dogpile.cache is a next generation replacement for Beaker made by the same authors.

## Search

*Libraries and software for indexing and performing search queries on data.*

* [elasticsearch-py](https://github.com/elastic/elasticsearch-py) ⭐ 4,372 | 🐛 69 | 🌐 Python | 📅 2026-03-23 - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [django-haystack](https://github.com/django-haystack/django-haystack) ⭐ 3,799 | 🐛 582 | 🌐 Python | 📅 2026-03-14 - Modular search for Django.
* [pysolr](https://github.com/django-haystack/pysolr) ⭐ 697 | 🐛 24 | 🌐 Python | 📅 2026-03-14 - A lightweight Python wrapper for [Apache Solr](https://lucene.apache.org/solr/).

## Serialization

*Libraries for serializing complex data types.*

* [orjson](https://github.com/ijl/orjson) ⭐ 7,985 | 🐛 0 | 🌐 Python | 📅 2026-03-03 - Fast, correct JSON library.
* [marshmallow](https://github.com/marshmallow-code/marshmallow) ⭐ 7,229 | 🐛 143 | 🌐 Python | 📅 2026-03-25 - A lightweight library for converting complex objects to and from simple Python datatypes.
* [msgpack](https://github.com/msgpack/msgpack-python) ⭐ 2,073 | 🐛 9 | 🌐 Python | 📅 2026-02-21 - MessagePack serializer implementation for Python.

**Data & Science**

## Data Analysis

*Libraries for data analysis.*

* Financial Data
  * [openbb](https://github.com/OpenBB-finance/OpenBB) ⭐ 63,578 | 🐛 71 | 🌐 Python | 📅 2026-03-26 - A financial data platform for analysts, quants and AI agents.
  * [yfinance](https://github.com/ranaroussi/yfinance) ⭐ 22,337 | 🐛 154 | 🌐 Python | 📅 2026-03-22 - Easy Pythonic way to download market and financial data from Yahoo Finance.
  * [akshare](https://github.com/akfamily/akshare) ⭐ 17,728 | 🐛 3 | 🌐 Python | 📅 2026-03-25 - A financial data interface library, built for human beings!
  * [edgartools](https://github.com/dgunning/edgartools) ⭐ 1,898 | 🐛 13 | 🌐 Python | 📅 2026-03-25 - Library for downloading structured data from SEC EDGAR filings and XBRL financial statements.
* General
  * [pathway](https://github.com/pathwaycom/pathway) ⭐ 62,615 | 🐛 30 | 🌐 Python | 📅 2026-03-25 - Real-time data processing framework for Python with reactive dataflows.
  * [pandas](https://github.com/pandas-dev/pandas) ⭐ 48,245 | 🐛 3,614 | 🌐 Python | 📅 2026-03-26 - A library providing high-performance, easy-to-use data structures and data analysis tools.
  * [polars](https://github.com/pola-rs/polars) ⭐ 37,852 | 🐛 2,720 | 🌐 Rust | 📅 2026-03-25 - A fast DataFrame library implemented in Rust with a Python API.
  * [datasette](https://github.com/simonw/datasette) ⭐ 10,870 | 🐛 667 | 🌐 Python | 📅 2026-03-25 - An open source multi-tool for exploring and publishing data.
  * [modin](https://github.com/modin-project/modin) ⭐ 10,364 | 🐛 709 | 🌐 Python | 📅 2026-02-10 - A drop-in pandas replacement that scales workflows by changing a single line of code.
  * [ibis](https://github.com/ibis-project/ibis) ⭐ 6,463 | 🐛 485 | 🌐 Python | 📅 2026-03-26 - A portable Python dataframe library with a single API for 20+ backends.
  * [aws-sdk-pandas](https://github.com/aws/aws-sdk-pandas) ⭐ 4,106 | 🐛 40 | 🌐 Python | 📅 2026-03-23 - Pandas on AWS.
  * [desbordante](https://github.com/desbordante/desbordante-core/) ⭐ 470 | 🐛 88 | 🌐 C++ | 📅 2026-03-24 - An open source data profiler for complex pattern discovery.

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

* [pydantic](https://github.com/pydantic/pydantic) ⭐ 27,319 | 🐛 546 | 🌐 Python | 📅 2026-03-25 - Data validation using Python type hints.
* [jsonschema](https://github.com/python-jsonschema/jsonschema) ⭐ 4,939 | 🐛 49 | 🌐 Python | 📅 2026-03-23 - An implementation of [JSON Schema](http://json-schema.org/) for Python.
* [pandera](https://github.com/unionai-oss/pandera) ⭐ 4,271 | 🐛 461 | 🌐 Python | 📅 2026-03-24 - A data validation library for dataframes, with support for pandas, polars, and Spark.
* [cerberus](https://github.com/pyeve/cerberus) ⭐ 3,272 | 🐛 14 | 🌐 Python | 📅 2026-01-01 - A lightweight and extensible data validation library.

## Data Visualization

*Libraries for visualizing data. Also see [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization) ⭐ 34,939 | 🐛 34 | 📅 2026-03-16.*

* Dashboards and Apps
  * [streamlit](https://github.com/streamlit/streamlit) ⭐ 44,021 | 🐛 1,317 | 🌐 Python | 📅 2026-03-25 - A framework which lets you build dashboards, generate reports, or create chat apps in minutes.
  * [gradio](https://github.com/gradio-app/gradio) ⭐ 42,158 | 🐛 506 | 🌐 Python | 📅 2026-03-25 - Build and share machine learning apps, all in Python.
* Plotting
  * [matplotlib](https://github.com/matplotlib/matplotlib) ⭐ 22,636 | 🐛 1,550 | 🌐 Python | 📅 2026-03-26 - A Python 2D plotting library.
  * [bokeh](https://github.com/bokeh/bokeh) ⭐ 20,385 | 🐛 858 | 🌐 TypeScript | 📅 2026-03-24 - Interactive Web Plotting for Python.
  * [plotly](https://github.com/plotly/plotly.py) ⭐ 18,386 | 🐛 769 | 🌐 Python | 📅 2026-03-25 - Interactive graphing library for Python.
  * [seaborn](https://github.com/mwaskom/seaborn) ⭐ 13,784 | 🐛 211 | 🌐 Python | 📅 2026-01-22 - Statistical data visualization using Matplotlib.
  * [altair](https://github.com/vega/altair) ⭐ 10,316 | 🐛 146 | 🌐 Python | 📅 2026-03-24 - Declarative statistical visualization library for Python.
  * [plotnine](https://github.com/has2k1/plotnine) ⭐ 4,527 | 🐛 82 | 🌐 Python | 📅 2026-03-10 - A grammar of graphics for Python based on ggplot2.
  * [pyqtgraph](https://github.com/pyqtgraph/pyqtgraph) ⭐ 4,319 | 🐛 508 | 🌐 Python | 📅 2026-03-09 - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
  * [bqplot](https://github.com/bqplot/bqplot) ⭐ 3,684 | 🐛 278 | 🌐 TypeScript | 📅 2026-01-23 - Interactive Plotting Library for the Jupyter Notebook.
  * [vispy](https://github.com/vispy/vispy) ⭐ 3,559 | 🐛 384 | 🌐 Python | 📅 2026-03-25 - High-performance scientific visualization based on OpenGL.
  * [pygal](https://github.com/Kozea/pygal) ⭐ 2,752 | 🐛 200 | 🌐 Python | 📅 2025-12-09 - A Python SVG Charts Creator.
  * [ultraplot](https://github.com/ultraplot/UltraPlot) ⭐ 284 | 🐛 23 | 🌐 Python | 📅 2026-03-26 - Matplotlib wrapper for publication-ready scientific figures with minimal code. Includes advanced subplot management, panel layouts, and batteries-included geoscience plotting.
* Specialized
  * [cartopy](https://github.com/SciTools/cartopy) ⭐ 1,595 | 🐛 339 | 🌐 Python | 📅 2026-03-16 - A cartographic python library with matplotlib support.
  * [pygraphviz](https://github.com/pygraphviz/pygraphviz/) ⭐ 835 | 🐛 81 | 🌐 C | 📅 2026-02-10 - Python interface to [Graphviz](http://www.graphviz.org/).

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [geodjango](https://github.com/django/django) ⭐ 87,122 | 🐛 424 | 🌐 Python | 📅 2026-03-25 - A world-class geographic web framework that is part of [Django](https://docs.djangoproject.com/en/dev/ref/contrib/gis/).
* [geopandas](https://github.com/geopandas/geopandas) ⭐ 5,072 | 🐛 414 | 🌐 Python | 📅 2026-03-23 - Python tools for geographic data (GeoSeries/GeoDataFrame) built on pandas.
* [geopy](https://github.com/geopy/geopy) ⭐ 4,789 | 🐛 50 | 🌐 Python | 📅 2026-01-27 - Python Geocoding Toolbox.
* [django-countries](https://github.com/SmileyChris/django-countries) ⭐ 1,522 | 🐛 9 | 🌐 Python | 📅 2026-01-08 - A Django app that provides a country field for models and forms.
* [geojson](https://github.com/jazzband/geojson) ⭐ 984 | 🐛 32 | 🌐 Python | 📅 2026-01-05 - Python bindings and utilities for GeoJSON.

## Science

*Libraries for scientific computing. Also see [Python-for-Scientists](https://github.com/TomNicholas/Python-for-Scientists) ⭐ 356 | 🐛 3 | 📅 2025-06-27.*

* Other
  * [manim](https://github.com/ManimCommunity/manim) ⭐ 37,397 | 🐛 463 | 🌐 Python | 📅 2026-03-18 - An animation engine for explanatory math videos.
  * [networkx](https://github.com/networkx/networkx) ⭐ 16,759 | 🐛 347 | 🌐 Python | 📅 2026-03-26 - A high-productivity software for complex networks.
  * [shapely](https://github.com/shapely/shapely) ⭐ 4,403 | 🐛 221 | 🌐 Python | 📅 2026-03-10 - Manipulation and analysis of geometric objects in the Cartesian plane.
  * [colour](https://github.com/colour-science/colour) ⭐ 2,541 | 🐛 88 | 🌐 Python | 📅 2026-03-24 - Implementing a comprehensive number of colour theory transformations and algorithms.
* Core
  * [numpy](https://github.com/numpy/numpy) ⭐ 31,659 | 🐛 2,334 | 🌐 Python | 📅 2026-03-25 - A fundamental package for scientific computing with Python.
  * [scipy](https://github.com/scipy/scipy) ⭐ 14,561 | 🐛 1,776 | 🌐 Python | 📅 2026-03-26 - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
  * [sympy](https://github.com/sympy/sympy) ⭐ 14,506 | 🐛 5,636 | 🌐 Python | 📅 2026-03-25 - A Python library for symbolic mathematics.
  * [statsmodels](https://github.com/statsmodels/statsmodels) ⭐ 11,317 | 🐛 2,964 | 🌐 Python | 📅 2026-03-19 - Statistical modeling and econometrics in Python.
  * [numba](https://github.com/numba/numba) ⭐ 10,945 | 🐛 1,764 | 🌐 Python | 📅 2026-03-24 - Python JIT compiler to LLVM aimed at scientific Python.
* Physics and Engineering
  * [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐ 28,980 | 🐛 32 | 🌐 Python | 📅 2026-03-23 - This is a compilation of various robotics algorithms with visualizations.
  * [astropy](https://github.com/astropy/astropy) ⭐ 5,094 | 🐛 1,441 | 🌐 Python | 📅 2026-03-24 - A community Python library for Astronomy.
  * [obspy](https://github.com/obspy/obspy) ⭐ 1,289 | 🐛 300 | 🌐 Python | 📅 2026-03-25 - A Python toolbox for seismology.
  * [pydy](https://github.com/pydy/pydy) ⭐ 409 | 🐛 97 | 🌐 Python | 📅 2025-11-03 - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion.
* Simulation and Modeling
  * [pymc](https://github.com/pymc-devs/pymc) ⭐ 9,546 | 🐛 499 | 🌐 Python | 📅 2026-03-25 - Probabilistic programming and Bayesian modeling in Python.
  * [pathsim](https://github.com/pathsim/pathsim) ⭐ 337 | 🐛 15 | 🌐 Python | 📅 2026-03-25 - A block-based system modeling and simulation framework with a browser-based visual editor.
  * [simpy](https://gitlab.com/team-simpy/simpy) - A process-based discrete-event simulation framework.
* Biology and Chemistry
  * [biopython](https://github.com/biopython/biopython) ⭐ 4,933 | 🐛 577 | 🌐 Python | 📅 2026-03-16 - Biopython is a set of freely available tools for biological computation.
  * [rdkit](https://github.com/rdkit/rdkit) ⭐ 3,354 | 🐛 96 | 🌐 HTML | 📅 2026-03-26 - Cheminformatics and Machine Learning Software.
  * [openbabel](https://github.com/openbabel/openbabel) ⭐ 1,295 | 🐛 745 | 🌐 C++ | 📅 2025-03-04 - A chemical toolbox designed to speak the many languages of chemical data.
  * [cclib](https://github.com/cclib/cclib) ⭐ 397 | 🐛 193 | 🌐 Python | 📅 2026-03-23 - A library for parsing and interpreting the results of computational chemistry packages.

## Quantum Computing

*Libraries for quantum computing.*

* [qiskit](https://github.com/Qiskit/qiskit) ⭐ 7,171 | 🐛 1,112 | 🌐 Python | 📅 2026-03-25 — An IBM-backed quantum SDK for building, simulating, and running circuits on real quantum hardware.
* [Cirq](https://github.com/quantumlib/Cirq) ⭐ 4,900 | 🐛 135 | 🌐 Python | 📅 2026-03-26 — A Google-developed framework focused on hardware-aware quantum circuit design for NISQ devices.
* [pennylane](https://github.com/PennyLaneAI/pennylane) ⭐ 3,117 | 🐛 443 | 🌐 Python | 📅 2026-03-26 — A hybrid quantum-classical machine learning library with automatic differentiation support.
* [qutip](https://github.com/qutip/qutip) ⭐ 1,979 | 🐛 150 | 🌐 Python | 📅 2026-03-25 - Quantum Toolbox in Python.

**Developer Tools**

## Algorithms and Design Patterns

*Python implementation of data structures, algorithms and design patterns. Also see [awesome-algorithms](https://github.com/tayllan/awesome-algorithms) ⭐ 24,890 | 🐛 0 | 📅 2026-01-11.*

* Algorithms
  * [thealgorithms](https://github.com/TheAlgorithms/Python) ⭐ 219,055 | 🐛 892 | 🌐 Python | 📅 2026-03-25 - All Algorithms implemented in Python.
  * [algorithms](https://github.com/keon/algorithms) ⭐ 25,407 | 🐛 1 | 🌐 Python | 📅 2026-03-13 - Minimal examples of data structures and algorithms.
  * [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) ⭐ 3,935 | 🐛 36 | 🌐 Python | 📅 2024-03-08 - Fast and pure-Python implementation of sorted collections.
* Design Patterns
  * [python-patterns](https://github.com/faif/python-patterns) ⭐ 42,801 | 🐛 13 | 🌐 Python | 📅 2026-03-13 - A collection of design patterns in Python.
  * [transitions](https://github.com/pytransitions/transitions) ⭐ 6,467 | 🐛 19 | 🌐 Python | 📅 2025-09-11 - A lightweight, object-oriented finite state machine implementation.

## Interactive Interpreter

*Interactive Python interpreters (REPL).*

* [marimo](https://github.com/marimo-team/marimo) ⭐ 19,937 | 🐛 589 | 🌐 Python | 📅 2026-03-26 - Transform data and train models, feels like a next-gen notebook, stored as Git-friendly Python.
* [jupyter](https://github.com/jupyter/notebook) ⭐ 13,030 | 🐛 1,959 | 🌐 Jupyter Notebook | 📅 2026-03-25 - A rich toolkit to help you make the most out of using Python interactively.
  * [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter) ⭐ 4,571 | 🐛 7 | 📅 2026-03-26
* [ptpython](https://github.com/prompt-toolkit/ptpython) ⭐ 5,413 | 🐛 262 | 🌐 Python | 📅 2025-11-21 - Advanced Python REPL built on top of the [python-prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) ⭐ 10,343 | 🐛 698 | 🌐 Python | 📅 2026-03-17.

## Code Analysis

*Tools of static analysis, linters and code quality checkers. Also see [awesome-static-analysis](https://github.com/analysis-tools-dev/static-analysis) ⭐ 14,454 | 🐛 20 | 🌐 Rust | 📅 2026-03-23.*

* Code Formatters
  * [ruff](https://github.com/astral-sh/ruff) ⭐ 46,698 | 🐛 1,956 | 🌐 Rust | 📅 2026-03-26 - An extremely fast Python linter and code formatter.
  * [black](https://github.com/psf/black) ⭐ 41,441 | 🐛 326 | 🌐 Python | 📅 2026-03-23 - The uncompromising Python code formatter.
  * [isort](https://github.com/PyCQA/isort) ⭐ 6,924 | 🐛 119 | 🌐 Python | 📅 2026-03-24 - A Python utility / library to sort imports.
* Code Linters
  * [ruff](https://github.com/astral-sh/ruff) ⭐ 46,698 | 🐛 1,956 | 🌐 Rust | 📅 2026-03-26 - An extremely fast Python linter and code formatter.
  * [bandit](https://github.com/PyCQA/bandit) ⭐ 7,885 | 🐛 220 | 🌐 Python | 📅 2026-03-22 - A tool designed to find common security issues in Python code.
  * [pylint](https://github.com/pylint-dev/pylint) ⭐ 5,667 | 🐛 1,063 | 🌐 Python | 📅 2026-03-23 - A fully customizable source code analyzer.
  * [flake8](https://github.com/PyCQA/flake8) ⭐ 3,773 | 🐛 23 | 🌐 Python | 📅 2025-12-22 - A wrapper around `pycodestyle`, `pyflakes` and McCabe.
    * [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions) ⭐ 1,275 | 🐛 3 | 📅 2026-03-25
* Type Annotations Generators
  * [pytype](https://github.com/google/pytype) ⭐ 5,032 | 🐛 6 | 🌐 Python | 📅 2026-03-16 - Pytype checks and infers types for Python code - without requiring type annotations.
  * [monkeytype](https://github.com/Instagram/MonkeyType) ⭐ 4,999 | 🐛 73 | 🌐 Python | 📅 2026-02-11 - A system for Python that generates static type annotations by collecting runtime types.
* Code Analysis
  * [code2flow](https://github.com/scottrogowski/code2flow) ⭐ 4,551 | 🐛 37 | 🌐 Python | 📅 2025-07-27 - Turn your Python and JavaScript code into DOT flowcharts.
  * [vulture](https://github.com/jendrikseipp/vulture) ⭐ 4,401 | 🐛 56 | 🌐 Python | 📅 2026-03-25 - A tool for finding and analyzing dead Python code.
  * [prospector](https://github.com/prospector-dev/prospector) ⭐ 2,076 | 🐛 34 | 🌐 Python | 📅 2026-03-23 - A tool to analyze Python code.
* Refactoring
  * [rope](https://github.com/python-rope/rope) ⭐ 2,188 | 🐛 130 | 🌐 Python | 📅 2026-01-04 - Rope is a python refactoring library.
* Type Checkers - [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing) ⭐ 1,952 | 🐛 7 | 📅 2026-03-25
  * [mypy](https://github.com/python/mypy) ⭐ 20,333 | 🐛 3,112 | 🌐 Python | 📅 2026-03-26 - Check variable types during compile time.
  * [ty](https://github.com/astral-sh/ty) ⭐ 18,053 | 🐛 752 | 🌐 Python | 📅 2026-03-24 - An extremely fast Python type checker and language server.
  * [pyre-check](https://github.com/facebook/pyre-check) ⭐ 7,149 | 🐛 157 | 🌐 OCaml | 📅 2026-03-25 - Performant type checking.
  * [typeshed](https://github.com/python/typeshed) ⭐ 5,026 | 🐛 338 | 🌐 Python | 📅 2026-03-26 - Collection of library stubs for Python, with static types.

## Testing

*Libraries for testing codebases and generating test data.*

* GUI / Web Testing
  * [selenium](https://github.com/SeleniumHQ/selenium) ⭐ 34,177 | 🐛 195 | 🌐 Java | 📅 2026-03-26 - Python bindings for [Selenium](https://selenium.dev/) [WebDriver](https://selenium.dev/documentation/webdriver/).
  * [locust](https://github.com/locustio/locust) ⭐ 27,640 | 🐛 9 | 🌐 Python | 📅 2026-03-25 - Scalable user load testing tool written in Python.
  * [playwright-python](https://github.com/microsoft/playwright-python) ⭐ 14,434 | 🐛 77 | 🌐 Python | 📅 2026-03-19 - Python version of the Playwright testing and automation library.
  * [pyautogui](https://github.com/asweigart/pyautogui) ⭐ 12,393 | 🐛 577 | 🌐 Python | 📅 2024-08-20 - PyAutoGUI is a cross-platform GUI automation Python module for human beings.
  * [schemathesis](https://github.com/schemathesis/schemathesis) ⭐ 3,157 | 🐛 31 | 🌐 Python | 📅 2026-03-25 - A tool for automatic property-based testing of web applications built with Open API / Swagger specifications.
* Fake Data
  * [faker](https://github.com/joke2k/faker) ⭐ 19,207 | 🐛 16 | 🌐 Python | 📅 2026-03-23 - A Python package that generates fake data.
  * [mimesis](https://github.com/lk-geimfari/mimesis) ⭐ 4,801 | 🐛 17 | 🌐 Python | 📅 2026-03-23 - is a Python library that help you generate fake data.
* Frameworks
  * [pytest](https://github.com/pytest-dev/pytest) ⭐ 13,720 | 🐛 1,017 | 🌐 Python | 📅 2026-03-23 - A mature full-featured Python testing tool.
  * [robotframework](https://github.com/robotframework/robotframework) ⭐ 11,507 | 🐛 288 | 🌐 Python | 📅 2026-03-25 - A generic test automation framework.
  * [hypothesis](https://github.com/HypothesisWorks/hypothesis) ⭐ 8,556 | 🐛 65 | 🌐 Python | 📅 2026-03-25 - Hypothesis is an advanced Quickcheck style property based testing library.
  * [scanapi](https://github.com/scanapi/scanapi) ⭐ 1,472 | 🐛 29 | 🌐 Python | 📅 2026-02-27 - Automated Testing and Documentation for your REST API.
  * [unittest](https://docs.python.org/3/library/unittest.html) - (Python standard library) Unit testing framework.
* Mock
  * [freezegun](https://github.com/spulec/freezegun) ⭐ 4,501 | 🐛 152 | 🌐 Python | 📅 2025-08-19 - Travel through time by mocking the datetime module.
  * [responses](https://github.com/getsentry/responses) ⭐ 4,333 | 🐛 35 | 🌐 Python | 📅 2026-03-23 - A utility library for mocking out the requests Python library.
  * [vcrpy](https://github.com/kevin1024/vcrpy) ⭐ 2,955 | 🐛 159 | 🌐 Python | 📅 2026-03-20 - Record and replay HTTP interactions on your tests.
  * [mocket](https://github.com/mindflayer/python-mocket) ⭐ 309 | 🐛 5 | 🌐 Python | 📅 2026-02-23 - A socket mock framework with gevent/asyncio/SSL support.
  * [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
* Test Runners
  * [tox](https://github.com/tox-dev/tox) ⭐ 3,906 | 🐛 5 | 🌐 Python | 📅 2026-03-25 - Auto builds and tests distributions in multiple Python versions
  * [nox](https://github.com/wntrblm/nox) ⭐ 1,504 | 🐛 80 | 🌐 Python | 📅 2026-03-23 - Flexible test automation for Python.
* Object Factories
  * [factory\_boy](https://github.com/FactoryBoy/factory_boy) ⭐ 3,781 | 🐛 206 | 🌐 Python | 📅 2026-01-01 - A test fixtures replacement for Python.
  * [polyfactory](https://github.com/litestar-org/polyfactory) ⭐ 1,433 | 🐛 63 | 🌐 Python | 📅 2026-03-18 - mock data generation library with support to classes (continuation of `pydantic-factories`)
* Code Coverage
  * [coverage](https://github.com/coveragepy/coveragepy) ⭐ 3,337 | 🐛 268 | 🌐 Python | 📅 2026-03-25 - Code coverage measurement.

## Debugging Tools

*Libraries for debugging code.*

* Profiler
  * [py-spy](https://github.com/benfred/py-spy) ⭐ 15,060 | 🐛 230 | 🌐 Rust | 📅 2026-03-05 - A sampling profiler for Python programs. Written in Rust.
  * [scalene](https://github.com/plasma-umass/scalene) ⭐ 13,331 | 🐛 155 | 🌐 JavaScript | 📅 2026-03-23 - A high-performance, high-precision CPU, GPU, and memory profiler for Python.
* Others
  * [icecream](https://github.com/gruns/icecream) ⭐ 10,034 | 🐛 64 | 🌐 Python | 📅 2026-01-21 - Inspect variables, expressions, and program execution with a single, simple function call.
  * [django-debug-toolbar](https://github.com/django-commons/django-debug-toolbar) ⭐ 8,350 | 🐛 84 | 🌐 Python | 📅 2026-03-23 - Display various debug information for Django.
  * [flask-debugtoolbar](https://github.com/pallets-eco/flask-debugtoolbar) ⭐ 979 | 🐛 39 | 🌐 JavaScript | 📅 2026-03-02 - A port of the django-debug-toolbar to flask.
  * [memory\_graph](https://github.com/bterwijn/memory_graph) ⭐ 787 | 🐛 1 | 🌐 Python | 📅 2026-03-25 - Visualize Python data at runtime to debug references, mutability, and aliasing.
* pdb-like Debugger
  * [pudb](https://github.com/inducer/pudb) ⭐ 3,223 | 🐛 163 | 🌐 Python | 📅 2026-03-16 - A full-screen, console-based Python debugger.
  * [ipdb](https://github.com/gotcha/ipdb) ⭐ 1,968 | 🐛 79 | 🌐 Python | 📅 2026-02-27 - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html).
* Tracing
  * [python-hunter](https://github.com/ionelmc/python-hunter) ⭐ 867 | 🐛 47 | 🌐 Python | 📅 2025-08-22 - A flexible code tracing toolkit.
  * [manhole](https://github.com/ionelmc/python-manhole) ⭐ 401 | 🐛 9 | 🌐 Python | 📅 2024-07-04 - Debugging UNIX socket connections and present the stacktraces for all threads and an interactive prompt.

## Build Tools

*Compile software from source code.*

* [platformio](https://github.com/platformio/platformio-core) ⭐ 8,957 | 🐛 295 | 🌐 Python | 📅 2026-02-23 - A console tool to build code with different development platforms.
* [invoke](https://github.com/pyinvoke/invoke) ⭐ 4,722 | 🐛 441 | 🌐 Python | 📅 2026-03-22 - A tool for managing shell-oriented subprocesses and organizing executable Python code into CLI-invokable tasks.
* [scons](https://github.com/SCons/scons) ⭐ 2,361 | 🐛 659 | 🌐 Python | 📅 2026-03-15 - A software construction tool.
* [doit](https://github.com/pydoit/doit) ⭐ 2,034 | 🐛 92 | 🌐 Python | 📅 2026-02-12 - A task runner and build tool.
* [pybuilder](https://github.com/pybuilder/pybuilder) ⭐ 1,961 | 🐛 102 | 🌐 Python | 📅 2026-03-20 - A continuous build tool written in pure Python.
* [bitbake](https://github.com/openembedded/bitbake) ⭐ 511 | 🐛 17 | 🌐 Python | 📅 2026-03-25 - A make-like build tool for embedded Linux.

## Documentation

*Libraries for generating project documentation.*

* [diagrams](https://github.com/mingrammer/diagrams) ⭐ 42,124 | 🐛 384 | 🌐 Python | 📅 2026-02-07 - Diagram as Code.
* [mkdocs](https://github.com/mkdocs/mkdocs/) ⭐ 21,900 | 🐛 142 | 🌐 Python | 📅 2025-10-20 - Markdown friendly documentation generator.
* [sphinx](https://github.com/sphinx-doc/sphinx/) ⭐ 7,747 | 🐛 1,434 | 🌐 Python | 📅 2026-03-22 - Python Documentation generator.
  * [awesome-sphinxdoc](https://github.com/ygzgxyz/awesome-sphinxdoc) ⭐ 973 | 🐛 3 | 🌐 HTML | 📅 2025-10-07
* [pdoc](https://github.com/mitmproxy/pdoc) ⭐ 2,478 | 🐛 58 | 🌐 Python | 📅 2026-03-01 - Epydoc replacement to auto generate API documentation for Python libraries.

**DevOps**

## DevOps Tools

*Software and libraries for DevOps.*

* Configuration Management
  * [ansible](https://github.com/ansible/ansible) ⭐ 68,383 | 🐛 806 | 🌐 Python | 📅 2026-03-26 - A radically simple IT automation platform.
  * [saltstack](https://github.com/saltstack/salt) ⭐ 15,289 | 🐛 2,459 | 🌐 Python | 📅 2026-03-26 - Infrastructure automation and management system.
  * [openstack](https://github.com/openstack/openstack) ⭐ 5,864 | 🐛 1 | 🌐 Python | 📅 2026-03-26 - Open source software for building private and public clouds.
  * [pyinfra](https://github.com/pyinfra-dev/pyinfra) ⭐ 4,906 | 🐛 212 | 🌐 Python | 📅 2026-03-25 - A versatile CLI tools and python libraries to automate infrastructure.
  * [cloudinit](https://github.com/canonical/cloud-init) ⭐ 3,638 | 🐛 524 | 🌐 Python | 📅 2026-03-25 - A multi-distribution package that handles early initialization of a cloud instance.
* Cloud Providers
  * [awscli](https://github.com/aws/aws-cli) ⭐ 16,842 | 🐛 613 | 🌐 Python | 📅 2026-03-25 - Universal Command Line Interface for Amazon Web Services.
  * [boto3](https://github.com/boto/boto3) ⭐ 9,744 | 🐛 183 | 🌐 Python | 📅 2026-03-25 - Python interface to Amazon Web Services.
* Deployment
  * [fabric](https://github.com/fabric/fabric) ⭐ 15,411 | 🐛 497 | 🌐 Python | 📅 2025-07-20 - A simple, Pythonic tool for remote execution and deployment.
  * [chalice](https://github.com/aws/chalice) ⭐ 11,051 | 🐛 494 | 🌐 Python | 📅 2025-05-29 - A Python serverless microframework for AWS.
* Other
  * [pre-commit](https://github.com/pre-commit/pre-commit) ⭐ 15,110 | 🐛 30 | 🌐 Python | 📅 2026-03-23 - A framework for managing and maintaining multi-language pre-commit hooks.
  * [borg](https://github.com/borgbackup/borg) ⭐ 13,118 | 🐛 345 | 🌐 Python | 📅 2026-03-25 - A deduplicating archiver with compression and encryption.
  * [chaostoolkit](https://github.com/chaostoolkit/chaostoolkit) ⭐ 2,003 | 🐛 4 | 🌐 Python | 📅 2024-07-20 - A Chaos Engineering toolkit & Orchestration for Developers.
* Monitoring and Processes
  * [psutil](https://github.com/giampaolo/psutil) ⭐ 11,117 | 🐛 365 | 🌐 Python | 📅 2026-03-26 - A cross-platform process and system utilities module.
  * [supervisor](https://github.com/Supervisor/supervisor) ⭐ 9,011 | 🐛 174 | 🌐 Python | 📅 2025-12-21 - Supervisor process control system for UNIX.
  * [sh](https://github.com/amoffat/sh) ⭐ 7,245 | 🐛 13 | 🌐 Python | 📅 2025-11-01 - A full-fledged subprocess replacement for Python.
  * [sentry-python](https://github.com/getsentry/sentry-python) ⭐ 2,160 | 🐛 389 | 🌐 Python | 📅 2026-03-25 - Sentry SDK for Python.

## Distributed Computing

*Frameworks and libraries for Distributed Computing.*

* Batch Processing
  * [pyspark](https://github.com/apache/spark) ⭐ 43,041 | 🐛 297 | 🌐 Scala | 📅 2026-03-26 - [Apache Spark](https://spark.apache.org/) Python API.
  * [ray](https://github.com/ray-project/ray/) ⭐ 41,860 | 🐛 3,520 | 🌐 Python | 📅 2026-03-26 - A system for parallel and distributed Python that unifies the machine learning ecosystem.
  * [luigi](https://github.com/spotify/luigi) ⭐ 18,704 | 🐛 159 | 🌐 Python | 📅 2026-03-18 - A module that helps you build complex pipelines of batch jobs.
  * [dask](https://github.com/dask/dask) ⭐ 13,775 | 🐛 1,233 | 🌐 Python | 📅 2026-03-24 - A flexible parallel computing library for analytic computing.
  * [joblib](https://github.com/joblib/joblib) ⭐ 4,332 | 🐛 429 | 🌐 Python | 📅 2026-03-03 - A set of tools to provide lightweight pipelining in Python.
  * [mpi4py](https://github.com/mpi4py/mpi4py) ⭐ 904 | 🐛 4 | 🌐 Python | 📅 2026-03-15 - Python bindings for MPI.

## Task Queues

*Libraries for working with task queues.*

* [celery](https://github.com/celery/celery) ⭐ 28,284 | 🐛 770 | 🌐 Python | 📅 2026-03-25 - An asynchronous task queue/job queue based on distributed message passing.
* [rq](https://github.com/rq/rq) ⭐ 10,616 | 🐛 246 | 🌐 Python | 📅 2026-03-25 - Simple job queues for Python.
* [huey](https://github.com/coleifer/huey) ⭐ 5,944 | 🐛 0 | 🌐 Python | 📅 2026-03-25 - Little multi-threaded task queue.
* [dramatiq](https://github.com/Bogdanp/dramatiq) ⭐ 5,186 | 🐛 56 | 🌐 Python | 📅 2026-03-19 - A fast and reliable background task processing library for Python 3.

## Job Schedulers

*Libraries for scheduling jobs.*

* [airflow](https://github.com/apache/airflow) ⭐ 44,787 | 🐛 1,802 | 🌐 Python | 📅 2026-03-26 - Airflow is a platform to programmatically author, schedule and monitor workflows.
* [prefect](https://github.com/PrefectHQ/prefect) ⭐ 21,961 | 🐛 975 | 🌐 Python | 📅 2026-03-26 - A modern workflow orchestration framework that makes it easy to build, schedule and monitor robust data pipelines.
* [dagster](https://github.com/dagster-io/dagster) ⭐ 15,151 | 🐛 2,801 | 🌐 Python | 📅 2026-03-25 - An orchestration platform for the development, production, and observation of data assets.
* [schedule](https://github.com/dbader/schedule) ⭐ 12,244 | 🐛 177 | 🌐 Python | 📅 2024-05-25 - Python job scheduling for humans.
* [apscheduler](https://github.com/agronholm/apscheduler) ⭐ 7,389 | 🐛 50 | 🌐 Python | 📅 2026-03-01 - A light but powerful in-process task scheduler that lets you schedule functions.
* [SpiffWorkflow](https://github.com/sartography/SpiffWorkflow) ⭐ 1,869 | 🐛 9 | 🌐 Python | 📅 2026-03-07 - A powerful workflow engine implemented in pure Python.

## Logging

*Libraries for generating and working with logs.*

* [loguru](https://github.com/Delgan/loguru) ⭐ 23,738 | 🐛 251 | 🌐 Python | 📅 2026-03-21 - Library which aims to bring enjoyable logging in Python.
* [structlog](https://github.com/hynek/structlog) ⭐ 4,669 | 🐛 42 | 🌐 Python | 📅 2026-03-19 - Structured logging made easy.
* [logging](https://docs.python.org/3/library/logging.html) - (Python standard library) Logging facility for Python.

## Network Virtualization

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*

* [scapy](https://github.com/secdev/scapy) ⭐ 12,132 | 🐛 129 | 🌐 Python | 📅 2026-03-23 - A brilliant packet manipulation library.
* [mininet](https://github.com/mininet/mininet) ⭐ 5,792 | 🐛 382 | 🌐 Python | 📅 2024-07-09 - A popular network emulator and API written in Python.
* [napalm](https://github.com/napalm-automation/napalm) ⭐ 2,442 | 🐛 167 | 🌐 Python | 📅 2026-03-16 - Cross-vendor API to manipulate network devices.

**CLI & GUI**

## CLI Development

*Libraries for building command-line applications.*

* Terminal Rendering
  * [rich](https://github.com/Textualize/rich) ⭐ 55,881 | 🐛 309 | 🌐 Python | 📅 2026-02-26 - Python library for rich text and beautiful formatting in the terminal. Also provides a great `RichHandler` log handler.
  * [textual](https://github.com/Textualize/textual) ⭐ 35,055 | 🐛 268 | 🌐 Python | 📅 2026-03-24 - A framework for building interactive user interfaces that run in the terminal and the browser.
  * [tqdm](https://github.com/tqdm/tqdm) ⭐ 31,061 | 🐛 598 | 🌐 Python | 📅 2026-02-14 - Fast, extensible progress bar for loops and CLI.
  * [alive-progress](https://github.com/rsalmei/alive-progress) ⭐ 6,259 | 🐛 17 | 🌐 Python | 📅 2025-10-10 - A new kind of Progress Bar, with real-time throughput, eta and very cool animations.
  * [asciimatics](https://github.com/peterbrittain/asciimatics) ⭐ 4,273 | 🐛 18 | 🌐 Python | 📅 2025-06-03 - A package to create full-screen text UIs (from interactive forms to ASCII animations).
  * [colorama](https://github.com/tartley/colorama) ⭐ 3,772 | 🐛 133 | 🌐 Python | 📅 2025-07-09 - Cross-platform colored terminal text.
* CLI Development
  * [python-fire](https://github.com/google/python-fire) ⭐ 28,161 | 🐛 171 | 🌐 Python | 📅 2026-03-01 - A library for creating command line interfaces from absolutely any Python object.
  * [typer](https://github.com/fastapi/typer) ⭐ 19,079 | 🐛 65 | 🌐 Python | 📅 2026-03-25 - Modern CLI framework that uses Python type hints. Built on Click and Pydantic.
  * [click](https://github.com/pallets/click/) ⭐ 17,364 | 🐛 161 | 🌐 Python | 📅 2026-03-15 - A package for creating beautiful command line interfaces in a composable way.
  * [python-prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) ⭐ 10,343 | 🐛 698 | 🌐 Python | 📅 2026-03-17 - A library for building powerful interactive command lines.
  * [cement](https://github.com/datafolklabs/cement) ⭐ 1,343 | 🐛 85 | 🌐 Python | 📅 2026-03-23 - CLI Application Framework for Python.
  * [argparse](https://docs.python.org/3/library/argparse.html) - (Python standard library) Command-line option and argument parsing.

## CLI Tools

*Useful CLI-based tools for productivity.*

* Productivity Tools
  * [yt-dlp](https://github.com/yt-dlp/yt-dlp) ⭐ 153,299 | 🐛 2,407 | 🌐 Python | 📅 2026-03-21 - A command-line program to download videos from YouTube and other video sites, a fork of youtube-dl.
  * [thefuck](https://github.com/nvbn/thefuck) ⭐ 95,756 | 🐛 418 | 🌐 Python | 📅 2024-07-19 - Correcting your previous console command.
  * [cookiecutter](https://github.com/cookiecutter/cookiecutter) ⭐ 24,775 | 🐛 275 | 🌐 Python | 📅 2026-03-04 - A command-line utility that creates projects from cookiecutters (project templates).
  * [xonsh](https://github.com/xonsh/xonsh/) ⭐ 9,261 | 🐛 321 | 🌐 Python | 📅 2026-03-25 - A Python-powered shell. Full-featured and cross-platform.
  * [tmuxp](https://github.com/tmux-python/tmuxp) ⭐ 4,456 | 🐛 118 | 🌐 Python | 📅 2026-03-24 - A [tmux](https://github.com/tmux/tmux) ⭐ 43,560 | 🐛 62 | 🌐 C | 📅 2026-03-25 session manager.
  * [doitlive](https://github.com/sloria/doitlive) ⭐ 3,566 | 🐛 13 | 🌐 Python | 📅 2026-03-16 - A tool for live presentations in the terminal.
  * [copier](https://github.com/copier-org/copier) ⭐ 3,234 | 🐛 136 | 🌐 Python | 📅 2026-03-25 - A library and command-line utility for rendering projects templates.
* CLI Enhancements
  * [httpie](https://github.com/httpie/cli) ⭐ 37,764 | 🐛 259 | 🌐 Python | 📅 2024-12-17 - A command line HTTP client, a user-friendly cURL replacement.
  * [pgcli](https://github.com/dbcli/pgcli) ⭐ 13,085 | 🐛 64 | 🌐 Python | 📅 2026-03-25 - PostgreSQL CLI with autocompletion and syntax highlighting.
  * [mycli](https://github.com/dbcli/mycli) ⭐ 11,892 | 🐛 18 | 🌐 Python | 📅 2026-03-25 - MySQL CLI with autocompletion and syntax highlighting.
  * [litecli](https://github.com/dbcli/litecli) ⭐ 3,217 | 🐛 35 | 🌐 Python | 📅 2026-02-15 - SQLite CLI with autocompletion and syntax highlighting.
  * [iredis](https://github.com/laixintao/iredis) ⭐ 2,727 | 🐛 53 | 🌐 Python | 📅 2026-03-18 - Redis CLI with autocompletion and syntax highlighting.

## GUI Development

*Libraries for working with graphical user interface applications.*

* Wrappers
  * [gooey](https://github.com/chriskiehl/Gooey) ⭐ 22,032 | 🐛 179 | 🌐 Python | 📅 2026-03-23 - Turn command line programs into a full GUI application with one line.
* Desktop
  * [kivy](https://github.com/kivy/kivy) ⭐ 18,908 | 🐛 873 | 🌐 Python | 📅 2026-03-25 - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
  * [dearpygui](https://github.com/hoffstadt/DearPyGui) ⭐ 15,304 | 🐛 395 | 🌐 C++ | 📅 2026-03-23 - A Simple GPU accelerated Python GUI framework
  * [customtkinter](https://github.com/tomschimansky/customtkinter) ⭐ 13,236 | 🐛 412 | 🌐 Python | 📅 2026-02-24 - A modern and customizable python UI-library based on Tkinter.
  * [toga](https://github.com/beeware/toga) ⭐ 5,328 | 🐛 303 | 🌐 Python | 📅 2026-03-26 - A Python native, OS native GUI toolkit.
  * [wxPython](https://github.com/wxWidgets/Phoenix) ⭐ 2,596 | 🐛 633 | 🌐 Python | 📅 2026-03-24 - A blending of the wxWidgets C++ class library with the Python.
  * [pyglet](https://github.com/pyglet/pyglet) ⭐ 2,176 | 🐛 96 | 🌐 Python | 📅 2026-03-21 - A cross-platform windowing and multimedia library for Python.
  * [enaml](https://github.com/nucleic/enaml) ⭐ 1,576 | 🐛 51 | 🌐 Python | 📅 2026-03-16 - Creating beautiful user-interfaces with Declarative Syntax like QML.
  * [pygobject](https://github.com/GNOME/pygobject) ⭐ 156 | 🐛 0 | 🌐 Python | 📅 2026-03-25 - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3).
  * [pyside](https://github.com/pyside/pyside-setup) ⭐ 119 | 🐛 0 | 🌐 C++ | 📅 2026-03-25 - Qt for Python offers the official Python bindings for [Qt](https://www.qt.io/), this is same as PyQt but it's the official binding with different licensing.
  * [PyQt](https://www.riverbankcomputing.com/static/Docs/PyQt6/) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework.
  * [tkinter](https://docs.python.org/3/library/tkinter.html) - (Python standard library) The standard Python interface to the Tcl/Tk GUI toolkit.
* Web-based
  * [flet](https://github.com/flet-dev/flet) ⭐ 15,800 | 🐛 366 | 🌐 Python | 📅 2026-03-26 - Cross-platform GUI framework for building modern apps in pure Python.
  * [nicegui](https://github.com/zauberzeug/nicegui) ⭐ 15,558 | 🐛 60 | 🌐 Python | 📅 2026-03-25 - An easy-to-use, Python-based UI framework, which shows up in your web browser.
  * [pywebview](https://github.com/r0x0r/pywebview/) ⭐ 5,815 | 🐛 13 | 🌐 Python | 📅 2026-03-18 - A lightweight cross-platform native wrapper around a webview component.
* Terminal
  * [urwid](https://github.com/urwid/urwid) ⭐ 2,995 | 🐛 141 | 🌐 Python | 📅 2026-03-23 - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
  * [curses](https://docs.python.org/3/library/curses.html) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.

**Text & Documents**

## Text Processing

*Libraries for parsing and manipulating plain texts.*

* General
  * [pypinyin](https://github.com/mozillazg/python-pinyin) ⭐ 5,273 | 🐛 41 | 🌐 Python | 📅 2026-03-08 - Convert Chinese hanzi (漢字) to pinyin (拼音).
  * [ftfy](https://github.com/rspeer/python-ftfy) ⭐ 4,016 | 🐛 16 | 🌐 Python | 📅 2024-10-30 - Makes Unicode text less broken and more consistent automagically.
  * [textdistance](https://github.com/life4/textdistance) ⭐ 3,528 | 🐛 9 | 🌐 Python | 📅 2025-04-18 - Compute distance between sequences with 30+ algorithms.
  * [chardet](https://github.com/chardet/chardet) ⭐ 2,502 | 🐛 2 | 🌐 Python | 📅 2026-03-26 - Python 2/3 compatible character encoding detector.
  * [python-slugify](https://github.com/un33k/python-slugify) ⭐ 1,601 | 🐛 7 | 🌐 Python | 📅 2026-01-07 - A Python slugify library that translates unicode to ASCII.
  * [pyfiglet](https://github.com/pwaller/pyfiglet) ⭐ 1,551 | 🐛 3 | 🌐 Python | 📅 2025-08-15 - An implementation of figlet written in Python.
  * [babel](https://github.com/python-babel/babel) ⭐ 1,435 | 🐛 207 | 🌐 Python | 📅 2026-02-18 - An internationalization library for Python.
  * [unidecode](https://github.com/avian2/unidecode) ⭐ 603 | 🐛 23 | 🌐 Python | 📅 2026-01-05 - ASCII transliterations of Unicode text.
  * [pangu.py](https://github.com/vinta/pangu.py) ⭐ 277 | 🐛 3 | 🌐 Python | 📅 2023-03-30 - Paranoid text spacing.
  * [difflib](https://docs.python.org/3/library/difflib.html) - (Python standard library) Helpers for computing deltas.
* Parser
  * [sqlparse](https://github.com/andialbrecht/sqlparse) ⭐ 4,002 | 🐛 256 | 🌐 Python | 📅 2025-12-19 - A non-validating SQL parser.
  * [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) ⭐ 3,722 | 🐛 12 | 🌐 Python | 📅 2026-03-13 - Parsing, formatting, storing and validating international phone numbers.
  * [pyparsing](https://github.com/pyparsing/pyparsing) ⭐ 2,465 | 🐛 39 | 🌐 Python | 📅 2026-02-22 - A general purpose framework for generating parsers.
  * [pygments](https://github.com/pygments/pygments) ⭐ 2,129 | 🐛 585 | 🌐 Python | 📅 2026-03-25 - A generic syntax highlighter.
  * [python-user-agents](https://github.com/selwin/python-user-agents) ⭐ 1,520 | 🐛 47 | 🌐 Python | 📅 2023-02-16 - Browser user agent parser.
  * [python-nameparser](https://github.com/derek73/python-nameparser) ⭐ 704 | 🐛 38 | 🌐 Python | 📅 2024-05-28 - Parsing human names into their individual components.
* Unique identifiers
  * [shortuuid](https://github.com/skorokithakis/shortuuid) ⭐ 2,180 | 🐛 0 | 🌐 Python | 📅 2025-12-01 - A generator library for concise, unambiguous and URL-safe UUIDs.
  * [sqids](https://github.com/sqids/sqids-python) ⭐ 497 | 🐛 1 | 🌐 Python | 📅 2025-10-01 - A library for generating short unique IDs from numbers.

## HTML Manipulation

*Libraries for working with HTML and XML.*

* [xmltodict](https://github.com/martinblech/xmltodict) ⭐ 5,730 | 🐛 1 | 🌐 Python | 📅 2026-03-23 - Working with XML feel like you are working with JSON.
* [lxml](https://github.com/lxml/lxml) ⭐ 3,006 | 🐛 18 | 🌐 Python | 📅 2026-03-25 - A very fast, easy-to-use and versatile library for handling HTML and XML.
* [pyquery](https://github.com/gawel/pyquery) ⭐ 2,379 | 🐛 55 | 🌐 Python | 📅 2026-02-18 - A jQuery-like library for parsing HTML.
* [justhtml](https://github.com/EmilStenstrom/justhtml/) ⭐ 1,121 | 🐛 2 | 🌐 Python | 📅 2026-03-21 - A pure Python HTML5 parser that just works.
* [markupsafe](https://github.com/pallets/markupsafe) ⭐ 685 | 🐛 10 | 🌐 Python | 📅 2025-09-27 - Implements a XML/HTML/XHTML Markup safe string for Python.
* [tinycss2](https://github.com/Kozea/tinycss2) ⭐ 184 | 🐛 5 | 🌐 Python | 📅 2025-11-23 - A low-level CSS parser and generator written in Python.
* [beautifulsoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.

## File Format Processing

*Libraries for parsing and manipulating specific text formats.*

* Markdown
  * [markitdown](https://github.com/microsoft/markitdown) ⭐ 92,449 | 🐛 484 | 🌐 Python | 📅 2026-03-16 - Python tool for converting files and office documents to Markdown.
  * [markdown](https://github.com/waylan/Python-Markdown) ⭐ 4,190 | 🐛 27 | 🌐 Python | 📅 2026-02-09 - A Python implementation of John Gruber’s Markdown.
  * [mistune](https://github.com/lepture/mistune) ⭐ 3,007 | 🐛 42 | 🌐 Python | 📅 2026-03-16 - Fastest and full featured pure Python parsers of Markdown.
  * [markdown-it-py](https://github.com/executablebooks/markdown-it-py) ⭐ 1,265 | 🐛 45 | 🌐 Python | 📅 2026-03-23 - Markdown parser with 100% CommonMark support, extensions, and syntax plugins.
* General
  * [docling](https://github.com/docling-project/docling) ⭐ 56,509 | 🐛 852 | 🌐 Python | 📅 2026-03-25 - Library for converting documents into structured data.
  * [kreuzberg](https://github.com/kreuzberg-dev/kreuzberg) ⭐ 7,115 | 🐛 26 | 🌐 Rust | 📅 2026-03-25 - High-performance document extraction library with a Rust core, supporting 62+ formats including PDF, Office, images with OCR, HTML, email, and archives.
  * [tablib](https://github.com/jazzband/tablib) ⭐ 4,753 | 🐛 34 | 🌐 Python | 📅 2026-01-06 - A module for Tabular Datasets in XLS, CSV, JSON, YAML.
  * [pyelftools](https://github.com/eliben/pyelftools) ⭐ 2,219 | 🐛 77 | 🌐 Python | 📅 2026-03-12 - Parsing and analyzing ELF files and DWARF debugging information.
* PDF
  * [pypdf](https://github.com/py-pdf/pypdf) ⭐ 9,892 | 🐛 126 | 🌐 Python | 📅 2026-03-25 - A library capable of splitting, merging, cropping, and transforming PDF pages.
  * [weasyprint](https://github.com/Kozea/WeasyPrint) ⭐ 8,761 | 🐛 143 | 🌐 Python | 📅 2026-03-25 - A visual rendering engine for HTML and CSS that can export to PDF.
  * [pdfminer.six](https://github.com/pdfminer/pdfminer.six) ⭐ 6,944 | 🐛 211 | 🌐 Python | 📅 2026-03-13 - Pdfminer.six is a community maintained fork of the original PDFMiner.
  * [pikepdf](https://github.com/pikepdf/pikepdf) ⭐ 2,674 | 🐛 44 | 🌐 Python | 📅 2026-03-24 - A powerful library for reading and editing PDF files, based on qpdf.
  * [pdf\_oxide](https://github.com/yfedoseev/pdf_oxide) ⭐ 513 | 🐛 56 | 🌐 Rust | 📅 2026-03-17 - A fast PDF library for text extraction, image extraction, and markdown conversion, powered by Rust.
  * [reportlab](https://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* Data Formats
  * [csvkit](https://github.com/wireservice/csvkit) ⭐ 6,361 | 🐛 34 | 🌐 Python | 📅 2026-03-18 - Utilities for converting to and working with CSV.
  * [pyyaml](https://github.com/yaml/pyyaml) ⭐ 2,871 | 🐛 346 | 🌐 Python | 📅 2025-09-25 - YAML implementations for Python.
  * [tomllib](https://docs.python.org/3/library/tomllib.html) - (Python standard library) Parse TOML files.
* MS Office
  * [python-docx](https://github.com/python-openxml/python-docx) ⭐ 5,502 | 🐛 706 | 🌐 Python | 📅 2025-06-17 - Reads, queries and modifies Microsoft Word 2007/2008 docx files.
  * [xlsxwriter](https://github.com/jmcnamara/XlsxWriter) ⭐ 3,924 | 🐛 25 | 🌐 Python | 📅 2026-03-22 - A Python module for creating Excel .xlsx files.
  * [xlwings](https://github.com/xlwings/xlwings) ⭐ 3,328 | 🐛 408 | 🌐 Python | 📅 2026-03-25 - A BSD-licensed library that makes it easy to call Python from Excel and vice versa.
  * [python-pptx](https://github.com/scanny/python-pptx) ⭐ 3,252 | 🐛 529 | 🌐 Python | 📅 2024-08-07 - Python library for creating and updating PowerPoint (.pptx) files.
  * [docxtpl](https://github.com/elapouya/python-docx-template) ⭐ 2,594 | 🐛 164 | 🌐 Python | 📅 2026-03-12 - Editing a docx document by jinja2 template
  * [pyexcel](https://github.com/pyexcel/pyexcel) ⭐ 1,284 | 🐛 10 | 🌐 Python | 📅 2025-12-10 - Providing one API for reading, manipulating and writing csv, ods, xls, xlsx and xlsm files.
  * [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.

## File Manipulation

*Libraries for file manipulation.*

* [watchdog](https://github.com/gorakhargosh/watchdog) ⭐ 7,296 | 🐛 227 | 🌐 Python | 📅 2026-02-27 - API and shell utilities to monitor file system events.
* [python-magic](https://github.com/ahupp/python-magic) ⭐ 2,900 | 🐛 27 | 🌐 Python | 📅 2026-03-03 - A Python interface to the libmagic file type identification library.
* [watchfiles](https://github.com/samuelcolvin/watchfiles) ⭐ 2,449 | 🐛 45 | 🌐 Python | 📅 2025-11-28 - Simple, modern and fast file watching and code reload in python.
* [mimetypes](https://docs.python.org/3/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python standard library) A cross-platform, object-oriented path library.

**Media**

## Image Processing

*Libraries for manipulating images.*

* [pillow](https://github.com/python-pillow/Pillow) ⭐ 13,466 | 🐛 138 | 🌐 Python | 📅 2026-03-25 - Pillow is the friendly [PIL](https://www.pythonware.com/products/pil/) fork.
* [thumbor](https://github.com/thumbor/thumbor) ⭐ 10,468 | 🐛 27 | 🌐 Python | 📅 2026-03-24 - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images.
* [scikit-image](https://github.com/scikit-image/scikit-image) ⭐ 6,488 | 🐛 884 | 🌐 Python | 📅 2026-03-24 - A Python library for (scientific) image processing.
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) ⭐ 4,873 | 🐛 45 | 🌐 Python | 📅 2026-03-25 - A pure Python QR Code generator.
* [pymatting](https://github.com/pymatting/pymatting) ⭐ 1,892 | 🐛 11 | 🌐 Python | 📅 2026-02-19 - A library for alpha matting.
* [wand](https://github.com/emcconville/wand) ⭐ 1,480 | 🐛 28 | 🌐 Python | 📅 2026-02-24 - Python bindings for [MagickWand](https://www.imagemagick.org/script/magick-wand.php), C API for ImageMagick.
* [pyvips](https://github.com/libvips/pyvips) ⭐ 791 | 🐛 844 | 🌐 Python | 📅 2026-01-20 - A fast image processing library with low memory needs.
* [python-barcode](https://github.com/WhyNotHugo/python-barcode) ⭐ 651 | 🐛 61 | 🌐 Python | 📅 2026-03-08 - Create barcodes in Python with no extra dependencies.

## Audio & Video Processing

*Libraries for manipulating audio, video, and their metadata.*

* Metadata
  * [beets](https://github.com/beetbox/beets) ⭐ 14,879 | 🐛 730 | 🌐 Python | 📅 2026-03-23 - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
  * [mutagen](https://github.com/quodlibet/mutagen) ⭐ 1,875 | 🐛 127 | 🌐 Python | 📅 2026-02-15 - A Python module to handle audio metadata.
  * [tinytag](https://github.com/devsnd/tinytag) ⭐ 806 | 🐛 9 | 🌐 Python | 📅 2026-03-15 - A library for reading music meta data of MP3, OGG, FLAC and Wave files.
* Video
  * [moviepy](https://github.com/Zulko/moviepy) ⭐ 14,478 | 🐛 81 | 🌐 Python | 📅 2026-03-07 - A module for script-based movie editing with many formats, including animated GIFs.
  * [vidgear](https://github.com/abhiTronix/vidgear) ⭐ 3,688 | 🐛 2 | 🌐 Python | 📅 2025-12-25 - Most Powerful multi-threaded Video Processing framework.
* Audio
  * [pydub](https://github.com/jiaaro/pydub) ⭐ 9,750 | 🐛 414 | 🌐 Python | 📅 2026-03-19 - Manipulate audio with a simple and easy high level interface.
  * [librosa](https://github.com/librosa/librosa) ⭐ 8,286 | 🐛 74 | 🌐 Python | 📅 2026-03-24 - Python library for audio and music analysis.
  * [gtts](https://github.com/pndurette/gTTS) ⭐ 2,599 | 🐛 21 | 🌐 Python | 📅 2025-12-15 - Python library and CLI tool for converting text to speech using Google Translate TTS.
  * [matchering](https://github.com/sergree/matchering) ⭐ 2,453 | 🐛 32 | 🌐 Python | 📅 2026-03-15 - A library for automated reference audio mastering.

## Game Development

*Awesome game development libraries.*

* [pygame](https://github.com/pygame/pygame) ⭐ 8,683 | 🐛 727 | 🌐 C | 📅 2025-11-01 - Pygame is a set of Python modules designed for writing games.
* [renpy](https://github.com/renpy/renpy) ⭐ 6,328 | 🐛 259 | 🌐 Ren'Py | 📅 2026-03-26 - A Visual Novel engine.
* [panda3d](https://github.com/panda3d/panda3d) ⭐ 5,073 | 🐛 347 | 🌐 C++ | 📅 2026-02-28 - 3D game engine developed by Disney.
* [arcade](https://github.com/pythonarcade/arcade) ⭐ 2,004 | 🐛 115 | 🌐 Python | 📅 2026-03-26 - Arcade is a modern Python framework for crafting games with compelling graphics and sound.
* [pyopengl](https://github.com/mcfletch/pyopengl) ⭐ 399 | 🐛 93 | 🌐 Python | 📅 2026-01-04 - Python ctypes bindings for OpenGL and it's related APIs.
* [py-sdl2](https://github.com/py-sdl/py-sdl2) ⭐ 338 | 🐛 25 | 🌐 Python | 📅 2025-11-18 - A ctypes based wrapper for the SDL2 library.

**Python Language**

## Implementations

*Implementations of Python.*

* [cpython](https://github.com/python/cpython) ⭐ 72,107 | 🐛 9,329 | 🌐 Python | 📅 2026-03-26 - Default, most widely used implementation of the Python programming language written in C.
* [micropython](https://github.com/micropython/micropython) ⭐ 21,578 | 🐛 1,842 | 🌐 C | 📅 2026-03-25 - A lean and efficient Python programming language implementation.
* [cython](https://github.com/cython/cython) ⭐ 10,662 | 🐛 1,501 | 🌐 Cython | 📅 2026-03-24 - Optimizing Static Compiler for Python.
* [ironpython](https://github.com/IronLanguages/ironpython3) ⭐ 2,739 | 🐛 309 | 🌐 C# | 📅 2026-03-22 - Implementation of the Python programming language written in C#.
* [pypy](https://github.com/pypy/pypy) ⭐ 1,690 | 🐛 766 | 🌐 Python | 📅 2026-03-25 - A very fast and compliant implementation of the Python language.

## Built-in Classes Enhancement

*Libraries for enhancing Python built-in classes.*

* [attrs](https://github.com/python-attrs/attrs) ⭐ 5,753 | 🐛 135 | 🌐 Python | 📅 2026-03-19 - Replacement for `__init__`, `__eq__`, `__repr__`, etc. boilerplate in class definitions.
* [box](https://github.com/cdgriffith/Box) ⭐ 2,824 | 🐛 35 | 🌐 Python | 📅 2026-02-21 - Python dictionaries with advanced dot notation access.
* [bidict](https://github.com/jab/bidict) ⭐ 1,579 | 🐛 1 | 🌐 Python | 📅 2026-02-01 - Efficient, Pythonic bidirectional map data structures and related functionality.

## Functional Programming

*Functional Programming with Python.*

* [toolz](https://github.com/pytoolz/toolz) ⭐ 5,132 | 🐛 127 | 🌐 Python | 📅 2026-01-01 - A collection of functional utilities for iterators, functions, and dictionaries. Also available as [cytoolz](https://github.com/pytoolz/cytoolz/) ⭐ 1,102 | 🐛 34 | 🌐 Python | 📅 2025-12-01 for Cython-accelerated performance.
* [coconut](https://github.com/evhub/coconut) ⭐ 4,313 | 🐛 86 | 🌐 Python | 📅 2026-02-16 - A variant of Python built for simple, elegant, Pythonic functional programming.
* [returns](https://github.com/dry-python/returns) ⭐ 4,243 | 🐛 81 | 🌐 Python | 📅 2026-03-23 - A set of type-safe monads, transformers, and composition utilities.
* [more-itertools](https://github.com/erikrose/more-itertools) ⭐ 4,047 | 🐛 15 | 🌐 Python | 📅 2026-03-24 - More routines for operating on iterables, beyond `itertools`.
* [funcy](https://github.com/Suor/funcy) ⭐ 3,502 | 🐛 12 | 🌐 Python | 📅 2026-03-09 - A fancy and practical functional tools.
* [functools](https://docs.python.org/3/library/functools.html) - (Python standard library) Higher-order functions and operations on callable objects.

## Asynchronous Programming

*Libraries for asynchronous, concurrent and parallel execution. Also see [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio) ⭐ 5,033 | 🐛 12 | 📅 2025-12-01.*

* [uvloop](https://github.com/MagicStack/uvloop) ⭐ 11,721 | 🐛 162 | 🌐 Cython | 📅 2026-01-30 - Ultra fast asyncio event loop.
* [trio](https://github.com/python-trio/trio) ⭐ 7,218 | 🐛 315 | 🌐 Python | 📅 2026-03-23 - A friendly library for async concurrency and I/O.
* [gevent](https://github.com/gevent/gevent) ⭐ 6,448 | 🐛 133 | 🌐 Python | 📅 2026-03-01 - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet) ⭐ 1,816 | 🐛 24 | 🌐 C++ | 📅 2026-03-01.
* [twisted](https://github.com/twisted/twisted) ⭐ 5,955 | 🐛 2,808 | 🌐 Python | 📅 2026-03-25 - An event-driven networking engine.
* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
  * [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio) ⭐ 5,033 | 🐛 12 | 📅 2025-12-01
* [anyio](https://github.com/agronholm/anyio) ⭐ 2,420 | 🐛 82 | 🌐 Python | 📅 2026-03-25 - A high-level async concurrency and networking framework that works on top of asyncio or trio.
* [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - (Python standard library) A high-level interface for asynchronously executing callables.
* [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python standard library) Process-based parallelism.

## Date and Time

*Libraries for working with dates and times.*

* [pendulum](https://github.com/python-pendulum/pendulum) ⭐ 6,634 | 🐛 244 | 🌐 Python | 📅 2026-03-06 - Python datetimes made easy.
* [dateparser](https://github.com/scrapinghub/dateparser) ⭐ 2,796 | 🐛 350 | 🌐 Python | 📅 2026-03-25 - A Python parser for human-readable dates in dozens of languages.
* [dateutil](https://github.com/dateutil/dateutil) ⭐ 2,605 | 🐛 433 | 🌐 Python | 📅 2026-03-03 - Extensions to the standard Python [datetime](https://docs.python.org/3/library/datetime.html) module.
* [zoneinfo](https://docs.python.org/3/library/zoneinfo.html) - (Python standard library) IANA time zone support. Brings the [tz database](https://en.wikipedia.org/wiki/Tz_database) into Python.

**Python Toolchain**

## Environment Management

*Libraries for Python version and virtual environment management.*

* [uv](https://github.com/astral-sh/uv) ⭐ 82,053 | 🐛 2,701 | 🌐 Rust | 📅 2026-03-26 - An extremely fast Python version, package and project manager, written in Rust.
* [pyenv](https://github.com/pyenv/pyenv) ⭐ 44,489 | 🐛 56 | 🌐 Shell | 📅 2026-03-24 - Simple Python version management.
* [pyenv-win](https://github.com/pyenv-win/pyenv-win) ⭐ 7,096 | 🐛 167 | 🌐 VBScript | 📅 2026-03-20 - Pyenv for Windows.
* [virtualenv](https://github.com/pypa/virtualenv) ⭐ 5,020 | 🐛 1 | 🌐 Python | 📅 2026-03-23 - A tool to create isolated Python environments.

## Package Management

*Libraries for package and dependency management.*

* [uv](https://github.com/astral-sh/uv) ⭐ 82,053 | 🐛 2,701 | 🌐 Rust | 📅 2026-03-26 - An extremely fast Python version, package and project manager, written in Rust.
* [poetry](https://github.com/python-poetry/poetry) ⭐ 34,302 | 🐛 559 | 🌐 Python | 📅 2026-03-25 - Python dependency management and packaging made easy.
* [pipx](https://github.com/pypa/pipx) ⭐ 12,650 | 🐛 116 | 🌐 Python | 📅 2026-03-23 - Install and Run Python Applications in Isolated Environments. Like `npx` in Node.js.
* [pip](https://github.com/pypa/pip) ⭐ 10,174 | 🐛 1,055 | 🌐 Python | 📅 2026-03-25 - The package installer for Python.
* [conda](https://github.com/conda/conda/) ⭐ 7,348 | 🐛 607 | 🌐 Python | 📅 2026-03-26 - Cross-platform, Python-agnostic binary package manager.

## Package Repositories

*Local PyPI repository server and proxies.*

* [warehouse](https://github.com/pypa/warehouse) ⭐ 3,986 | 🐛 552 | 🌐 Python | 📅 2026-03-25 - Next generation Python Package Repository (PyPI).
* [devpi](https://github.com/devpi/devpi) ⭐ 1,150 | 🐛 99 | 🌐 Python | 📅 2026-03-17 - PyPI server and packaging/testing/release tool.
* [bandersnatch](https://github.com/pypa/bandersnatch/) ⭐ 531 | 🐛 46 | 🌐 Python | 📅 2026-03-25 - PyPI mirroring tool provided by Python Packaging Authority (PyPA).

## Distribution

*Libraries to create packaged executables for release distribution.*

* [Nuitka](https://github.com/Nuitka/Nuitka) ⭐ 14,666 | 🐛 194 | 🌐 Python | 📅 2026-03-25 - Compiles Python programs into high-performance standalone executables (cross-platform, supports all Python versions).
* [pyinstaller](https://github.com/pyinstaller/pyinstaller) ⭐ 12,931 | 🐛 290 | 🌐 Python | 📅 2026-03-21 - Converts Python programs into stand-alone executables (cross-platform).
* [pyarmor](https://github.com/dashingsoft/pyarmor) ⭐ 4,996 | 🐛 11 | 🌐 Python | 📅 2026-03-18 - A tool used to obfuscate python scripts, bind obfuscated scripts to fixed machine or expire obfuscated scripts.
* [shiv](https://github.com/linkedin/shiv) ⭐ 1,920 | 🐛 65 | 🌐 Python | 📅 2026-01-10 - A command line utility for building fully self-contained zipapps (PEP 441), but with all their dependencies included.
* [cx-Freeze](https://github.com/marcelotduarte/cx_Freeze) ⭐ 1,534 | 🐛 43 | 🌐 Python | 📅 2026-03-24 - It is a Python tool that converts Python scripts into standalone executables and installers for Windows, macOS, and Linux.

## Configuration Files

*Libraries for storing and parsing configuration options.*

* [hydra](https://github.com/facebookresearch/hydra) ⭐ 10,271 | 🐛 388 | 🌐 Python | 📅 2026-02-07 - Hydra is a framework for elegantly configuring complex applications.
* [python-dotenv](https://github.com/theskumar/python-dotenv) ⭐ 8,707 | 🐛 89 | 🌐 Python | 📅 2026-03-09 - Reads key-value pairs from a `.env` file and sets them as environment variables.
* [dynaconf](https://github.com/dynaconf/dynaconf) ⭐ 4,273 | 🐛 160 | 🌐 Python | 📅 2026-03-17 - Dynaconf is a configuration manager with plugins for Django, Flask and FastAPI.
* [python-decouple](https://github.com/HBNetwork/python-decouple) ⭐ 3,021 | 🐛 20 | 🌐 Python | 📅 2024-11-28 - Strict separation of settings from code.
* [configparser](https://docs.python.org/3/library/configparser.html) - (Python standard library) INI file parser.

**Security**

## Cryptography

* [paramiko](https://github.com/paramiko/paramiko) ⭐ 9,715 | 🐛 1,154 | 🌐 Python | 📅 2026-03-01 - The leading native Python SSHv2 protocol library.
* [cryptography](https://github.com/pyca/cryptography) ⭐ 7,524 | 🐛 55 | 🌐 Python | 📅 2026-03-26 - A package designed to expose cryptographic primitives and recipes to Python developers.
* [pynacl](https://github.com/pyca/pynacl) ⭐ 1,185 | 🐛 54 | 🌐 C | 📅 2026-03-18 - Python binding to the Networking and Cryptography (NaCl) library.

## Penetration Testing

*Frameworks and tools for penetration testing.*

* [sherlock](https://github.com/sherlock-project/sherlock) ⭐ 74,083 | 🐛 202 | 🌐 Python | 📅 2026-03-25 - Hunt down social media accounts by username across social networks.
* [mitmproxy](https://github.com/mitmproxy/mitmproxy) ⭐ 42,799 | 🐛 420 | 🌐 Python | 📅 2026-03-24 - An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.
* [sqlmap](https://github.com/sqlmapproject/sqlmap) ⭐ 36,928 | 🐛 60 | 🌐 Python | 📅 2026-03-20 - Automatic SQL injection and database takeover tool.
* [setoolkit](https://github.com/trustedsec/social-engineer-toolkit) ⭐ 14,702 | 🐛 444 | 🌐 Python | 📅 2024-10-21 - A toolkit for social engineering.

**Miscellaneous**

## Hardware

*Libraries for programming with hardware.*

* [bleak](https://github.com/hbldh/bleak) ⭐ 2,359 | 🐛 115 | 🌐 Python | 📅 2026-03-26 - A cross platform Bluetooth Low Energy Client for Python using asyncio.
* [pynput](https://github.com/moses-palmer/pynput) ⭐ 2,128 | 🐛 192 | 🌐 Python | 📅 2025-08-12 - A library to control and monitor input devices.

## Microsoft Windows

*Python programming on Microsoft Windows.*

* [pywin32](https://github.com/mhammond/pywin32) ⭐ 5,536 | 🐛 396 | 🌐 C++ | 📅 2026-03-25 - Python Extensions for Windows.
* [pythonnet](https://github.com/pythonnet/pythonnet) ⭐ 5,421 | 🐛 169 | 🌐 C# | 📅 2026-03-25 - Python Integration with the .NET Common Language Runtime (CLR).
* [winpython](https://github.com/winpython/winpython) ⭐ 2,234 | 🐛 80 | 🌐 Python | 📅 2026-03-10 - Portable development environment for Windows 10/11.

## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [boltons](https://github.com/mahmoud/boltons) ⭐ 6,862 | 🐛 70 | 🌐 Python | 📅 2026-03-06 - A set of pure-Python utilities.
* [itsdangerous](https://github.com/pallets/itsdangerous) ⭐ 3,103 | 🐛 1 | 🌐 Python | 📅 2025-06-14 - Various helpers to pass trusted data to untrusted environments.
* [blinker](https://github.com/jek/blinker) ⭐ 2,035 | 🐛 0 | 🌐 Python | 📅 2025-11-19 - A fast Python in-process signal/event dispatching system.
* [tryton](https://github.com/tryton/tryton) ⭐ 172 | 🐛 0 | 🌐 Python | 📅 2026-03-26 - A general-purpose business framework.

# Resources

Where to discover learning resources or new Python libraries.

## Newsletters

* [Awesome Python Newsletter](http://python.libhunt.com/newsletter)
* [Pycoder's Weekly](https://pycoders.com/)
* [Python Tricks](https://realpython.com/python-tricks/)
* [Python Weekly](https://www.pythonweekly.com/)

## Podcasts

* [Django Chat](https://djangochat.com/)
* [PyPodcats](https://pypodcats.live)
* [Python Bytes](https://pythonbytes.fm)
* [Talk Python To Me](https://talkpython.fm/)
* [The Real Python Podcast](https://realpython.com/podcasts/rpp/)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) ⭐ 289,027 | 🐛 16 | 🌐 Python | 📅 2026-03-25 first.

***

If you have any question about this opinionated list, do not hesitate to contact [@vinta](https://x.com/vinta) on X (Twitter).
