[tool.poetry]
name = "qdrant_demo"
version = "0.1.0"
description = "Qdrant vector similarity engine demo"
authors = ["Andrey Vasnetsov <andrey@vasnetsov.com>"]

[tool.poetry.dependencies]
python = ">=3.8,<3.12"
scipy = "^1.9.1"
fastapi = "^0.67"
uvicorn = "^0.12.3"
sentence-transformers = "^2.2.0"
psutil = "^5.7.3"
nltk = "^3.7"
pandas = "^1.1.5"
loguru = "^0.5.3"
requests = "^2.25.1"
qdrant-client = "0.10.2"

[tool.poetry.dev-dependencies]

[build-system]
requires = ["poetry-core>=1.0.0"]
build-backend = "poetry.core.masonry.api"
