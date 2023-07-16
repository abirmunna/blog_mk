# FastAPI in minutes

## What is FastAPI?

FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.

The key features are:

- **Fast**: Very high performance, on par with **NodeJS** and **Go** (thanks to Starlette and Pydantic). One of the fastest Python frameworks available.
- **Fast to code**: Increase the speed to develop features by about 200% to 300%. *
- **Fewer bugs**: Reduce about 40% of human (developer) induced errors. *
- **Intuitive**: Great editor support. Completion everywhere. Less time debugging.
- **Easy**: Designed to be easy to use and learn. Less time reading docs.
- **Short**: Minimize code duplication. Multiple features from each parameter declaration. Fewer bugs.
- **Robust**: Get production-ready code. With automatic interactive documentation.
- **Standards-based**: Based on (and fully compatible with) the open standards for APIs: **OpenAPI** (previously known as Swagger) and **JSON Schema**.

* estimation based on tests on an internal development team, building production applications.

## Requirements

FastAPI requires Python 3.6, 3.7, 3.8 or 3.9.

## Installation

You can install FastAPI with pip:

```bash
$ pip install fastapi
```

## Example

```python
from fastapi import FastAPI

app = FastAPI()


@app.get("/")
async def root():
    return {"message": "Hello World"}
```

## User Guide

Check out the [User Guide](user-guide/) for more details.

## Interactive API docs

Go to [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs) in your browser to see the automatic interactive API documentation Swagger UI.

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-01-swagger-ui-simple.png)

## Interactive API docs Alternative

Go to [http://127.0.01:8000/redoc](http://127.0.01:8000/redoc) in your browser to see the automatic interactive API documentation ReDoc.

![ReDoc](https://fastapi.tiangolo.com/img/index/index-02-redoc-simple.png)

## So what are we getting with FastAPI?

- An easy to build API with Python
- A modern, asynchronous, Python 3.6+ web framework
- Automatic interactive API documentation
- Data validation
- Dependency injection
- Authentication
- Security
- CORS (Cross Origin Resource Sharing)
- GraphQL integration
- SQLAlchemy integration
- Docker and Kubernetes integration
- Testing utilities
- And many other features

#### Let's get started! with a deep dive into FastAPI. [:octicons-file-directory-symlink-16: Next](todo_l1.md){ .md-button}