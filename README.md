[[package]]
name = "anyio"
version = "3.6.1"
description = "High level compatibility layer for multiple asynchronous event loop implementations"
category = "main"
optional = false
python-versions = ">=3.6.2"

[package.dependencies]
idna = ">=2.8"
sniffio = ">=1.1"

[package.extras]
doc = ["packaging", "sphinx-autodoc-typehints (>=1.2.0)", "sphinx-rtd-theme"]
test = ["contextlib2", "coverage[toml] (>=4.5)", "hypothesis (>=4.0)", "mock (>=4)", "pytest (>=7.0)", "pytest-mock (>=3.6.1)", "trustme", "uvloop (<0.15)", "uvloop (>=0.15)"]
trio = ["trio (>=0.16)"]

[[package]]
name = "certifi"
version = "2022.9.24"
description = "Python package for providing Mozilla's CA Bundle."
category = "main"
optional = false
python-versions = ">=3.6"

[[package]]
name = "charset-normalizer"
version = "2.1.1"
description = "The Real First Universal Charset Detector. Open, modern and actively maintained alternative to Chardet."
category = "main"
optional = false
python-versions = ">=3.6.0"

[package.extras]
unicode_backport = ["unicodedata2"]

[[package]]
name = "click"
version = "7.1.2"
description = "Composable command line interface toolkit"
category = "main"
optional = false
python-versions = ">=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, !=3.4.*"

[[package]]
name = "colorama"
version = "0.4.5"
description = "Cross-platform colored terminal text."
category = "main"
optional = false
python-versions = ">=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, !=3.4.*"

[[package]]
name = "fastapi"
version = "0.67.0"
description = "FastAPI framework, high performance, easy to learn, fast to code, ready for production"
category = "main"
optional = false
python-versions = ">=3.6"

[package.dependencies]
pydantic = ">=1.6.2,<1.7 || >1.7,<1.7.1 || >1.7.1,<1.7.2 || >1.7.2,<1.7.3 || >1.7.3,<1.8 || >1.8,<1.8.1 || >1.8.1,<2.0.0"
starlette = "0.14.2"

[package.extras]
all = ["aiofiles (>=0.5.0,<0.6.0)", "async_exit_stack (>=1.0.1,<2.0.0)", "async_generator (>=1.10,<2.0.0)", "email_validator (>=1.1.1,<2.0.0)", "graphene (>=2.1.8,<3.0.0)", "itsdangerous (>=1.1.0,<2.0.0)", "jinja2 (>=2.11.2,<3.0.0)", "orjson (>=3.2.1,<4.0.0)", "python-multipart (>=0.0.5,<0.0.6)", "pyyaml (>=5.3.1,<6.0.0)", "requests (>=2.24.0,<3.0.0)", "ujson (>=4.0.1,<5.0.0)", "uvicorn[standard] (>=0.12.0,<0.14.0)"]
dev = ["autoflake (>=1.3.1,<2.0.0)", "flake8 (>=3.8.3,<4.0.0)", "graphene (>=2.1.8,<3.0.0)", "passlib[bcrypt] (>=1.7.2,<2.0.0)", "python-jose[cryptography] (>=3.3.0,<4.0.0)", "uvicorn[standard] (>=0.12.0,<0.14.0)"]
doc = ["markdown-include (>=0.6.0,<0.7.0)", "mkdocs (>=1.1.2,<2.0.0)", "mkdocs-markdownextradata-plugin (>=0.1.7,<0.2.0)", "mkdocs-material (>=7.1.9,<8.0.0)", "pyyaml (>=5.3.1,<6.0.0)", "typer-cli (>=0.0.12,<0.0.13)"]
test = ["aiofiles (>=0.5.0,<0.6.0)", "async_exit_stack (>=1.0.1,<2.0.0)", "async_generator (>=1.10,<2.0.0)", "black (==20.8b1)", "databases[sqlite] (>=0.3.2,<0.4.0)", "email_validator (>=1.1.1,<2.0.0)", "flake8 (>=3.8.3,<4.0.0)", "flask (>=1.1.2,<2.0.0)", "httpx (>=0.14.0,<0.15.0)", "isort (>=5.0.6,<6.0.0)", "mypy (==0.812)", "orjson (>=3.2.1,<4.0.0)", "peewee (>=3.13.3,<4.0.0)", "pytest (>=6.2.4,<7.0.0)", "pytest-asyncio (>=0.14.0,<0.15.0)", "pytest-cov (>=2.12.0,<3.0.0)", "python-multipart (>=0.0.5,<0.0.6)", "requests (>=2.24.0,<3.0.0)", "sqlalchemy (>=1.3.18,<1.4.0)", "ujson (>=4.0.1,<5.0.0)"]

[[package]]
name = "filelock"
version = "3.8.0"
description = "A platform independent file lock."
category = "main"
optional = false
python-versions = ">=3.7"

[package.extras]
docs = ["furo (>=2022.6.21)", "sphinx (>=5.1.1)", "sphinx-autodoc-typehints (>=1.19.1)"]
testing = ["covdefaults (>=2.2)", "coverage (>=6.4.2)", "pytest (>=7.1.2)", "pytest-cov (>=3)", "pytest-timeout (>=2.1)"]

[[package]]
name = "grpcio"
version = "1.49.1"
description = "HTTP/2-based RPC framework"
category = "main"
optional = false
python-versions = ">=3.7"

[package.dependencies]
six = ">=1.5.2"

[package.extras]
protobuf = ["grpcio-tools (>=1.49.1)"]

[[package]]
name = "grpcio-tools"
version = "1.49.1"
description = "Protobuf code generator for gRPC"
category = "main"
optional = false
python-versions = ">=3.7"

[package.dependencies]
grpcio = ">=1.49.1"
protobuf = ">=4.21.3,<5.0dev"
setuptools = "*"

[[package]]
name = "h11"
version = "0.12.0"
description = "A pure-Python, bring-your-own-I/O implementation of HTTP/1.1"
category = "main"
optional = false
python-versions = ">=3.6"

[[package]]
name = "h2"
version = "4.1.0"
description = "HTTP/2 State-Machine based protocol implementation"
category = "main"
optional = false
python-versions = ">=3.6.1"

[package.dependencies]
hpack = ">=4.0,<5"
hyperframe = ">=6.0,<7"

[[package]]
name = "hpack"
version = "4.0.0"
description = "Pure-Python HPACK header compression"
category = "main"
optional = false
python-versions = ">=3.6.1"

[[package]]
name = "httpcore"
version = "0.15.0"
description = "A minimal low-level HTTP client."
category = "main"
optional = false
python-versions = ">=3.7"

[package.dependencies]
anyio = ">=3.0.0,<4.0.0"
certifi = "*"
h11 = ">=0.11,<0.13"
sniffio = ">=1.0.0,<2.0.0"

[package.extras]
http2 = ["h2 (>=3,<5)"]
socks = ["socksio (>=1.0.0,<2.0.0)"]

[[package]]
name = "httpx"
version = "0.23.0"
description = "The next generation HTTP client."
category = "main"
optional = false
python-versions = ">=3.7"

[package.dependencies]
certifi = "*"
h2 = {version = ">=3,<5", optional = true, markers = "extra == \"http2\""}
httpcore = ">=0.15.0,<0.16.0"
rfc3986 = {version = ">=1.3,<2", extras = ["idna2008"]}
sniffio = "*"

[package.extras]
brotli = ["brotli", "brotlicffi"]
cli = ["click (>=8.0.0,<9.0.0)", "pygments (>=2.0.0,<3.0.0)", "rich (>=10,<13)"]
http2 = ["h2 (>=3,<5)"]
socks = ["socksio (>=1.0.0,<2.0.0)"]

[[package]]
name = "huggingface-hub"
version = "0.9.1"
description = "Client library to download and publish models, datasets and other repos on the huggingface.co hub"
category = "main"
optional = false
python-versions = ">=3.7.0"

[package.dependencies]
filelock = "*"
packaging = ">=20.9"
pyyaml = ">=5.1"
requests = "*"
tqdm = "*"
typing-extensions = ">=3.7.4.3"

[package.extras]
all = ["black (==22.3)", "datasets", "flake8 (>=3.8.3)", "flake8-bugbear", "isort (>=5.5.4)", "pytest", "pytest-cov", "soundfile"]
dev = ["black (==22.3)", "datasets", "flake8 (>=3.8.3)", "flake8-bugbear", "isort (>=5.5.4)", "pytest", "pytest-cov", "soundfile"]
fastai = ["fastai (>=2.4)", "fastcore (>=1.3.27)", "toml"]
quality = ["black (==22.3)", "flake8 (>=3.8.3)", "flake8-bugbear", "isort (>=5.5.4)"]
tensorflow = ["graphviz", "pydot", "tensorflow"]
testing = ["datasets", "pytest", "pytest-cov", "soundfile"]
torch = ["torch"]

[[package]]
name = "hyperframe"
version = "6.0.1"
description = "HTTP/2 framing layer for Python"
category = "main"
optional = false
python-versions = ">=3.6.1"

[[package]]
name = "idna"
version = "3.4"
description = "Internationalized Domain Names in Applications (IDNA)"
category = "main"
optional = false
python-versions = ">=3.5"

[[package]]
name = "joblib"
version = "1.2.0"
description = "Lightweight pipelining with Python functions"
category = "main"
optional = false
python-versions = ">=3.7"

[[package]]
name = "loguru"
version = "0.5.3"
description = "Python logging made (stupidly) simple"
category = "main"
optional = false
python-versions = ">=3.5"

[package.dependencies]
colorama = {version = ">=0.3.4", markers = "sys_platform == \"win32\""}
win32-setctime = {version = ">=1.0.0", markers = "sys_platform == \"win32\""}

[package.extras]
dev = ["Sphinx (>=2.2.1)", "black (>=19.10b0)", "codecov (>=2.0.15)", "colorama (>=0.3.4)", "flake8 (>=3.7.7)", "isort (>=5.1.1)", "pytest (>=4.6.2)", "pytest-cov (>=2.7.1)", "sphinx-autobuild (>=0.7.1)", "sphinx-rtd-theme (>=0.4.3)", "tox (>=3.9.0)", "tox-travis (>=0.12)"]

[[package]]
name = "nltk"
version = "3.7"
description = "Natural Language Toolkit"
category = "main"
optional = false
python-versions = ">=3.7"

[package.dependencies]
click = "*"
joblib = "*"
regex = ">=2021.8.3"
tqdm = "*"

[package.extras]
all = ["matplotlib", "numpy", "pyparsing", "python-crfsuite", "requests", "scikit-learn", "scipy", "twython"]
corenlp = ["requests"]
machine_learning = ["numpy", "python-crfsuite", "scikit-learn", "scipy"]
plot = ["matplotlib"]
tgrep = ["pyparsing"]
twitter = ["twython"]

[[package]]
name = "numpy"
version = "1.23.3"
description = "NumPy is the fundamental package for array computing with Python."
category = "main"
optional = false
python-versions = ">=3.8"

[[package]]
name = "packaging"
version = "21.3"
description = "Core utilities for Python packages"
category = "main"
optional = false
python-versions = ">=3.6"

[package.dependencies]
pyparsing = ">=2.0.2,<3.0.5 || >3.0.5"

[[package]]
name = "pandas"
version = "1.5.0"
description = "Powerful data structures for data analysis, time series, and statistics"
category = "main"
optional = false
python-versions = ">=3.8"

[package.dependencies]
numpy = [
    {version = ">=1.21.0", markers = "python_version >= \"3.10\""},
    {version = ">=1.20.3", markers = "python_version < \"3.10\""},
]
python-dateutil = ">=2.8.1"
pytz = ">=2020.1"

[package.extras]
test = ["hypothesis (>=5.5.3)", "pytest (>=6.0)", "pytest-xdist (>=1.31)"]

[[package]]
name = "Pillow"
version = "9.2.0"
description = "Python Imaging Library (Fork)"
category = "main"
optional = false
python-versions = ">=3.7"

[package.extras]
docs = ["furo", "olefile", "sphinx (>=2.4)", "sphinx-copybutton", "sphinx-issues (>=3.0.1)", "sphinx-removed-in", "sphinxext-opengraph"]
tests = ["check-manifest", "coverage", "defusedxml", "markdown2", "olefile", "packaging", "pyroma", "pytest", "pytest-cov", "pytest-timeout"]

[[package]]
name = "protobuf"
version = "4.21.6"
description = ""
category = "main"
optional = false
python-versions = ">=3.7"

[[package]]
name = "psutil"
version = "5.9.2"
description = "Cross-platform lib for process and system monitoring in Python."
category = "main"
optional = false
python-versions = ">=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*"

[package.extras]
test = ["enum34", "ipaddress", "mock", "pywin32", "wmi"]

[[package]]
name = "pydantic"
version = "1.10.2"
description = "Data validation and settings management using python type hints"
category = "main"
optional = false
python-versions = ">=3.7"

[package.dependencies]
typing-extensions = ">=4.1.0"

[package.extras]
dotenv = ["python-dotenv (>=0.10.4)"]
email = ["email-validator (>=1.0.3)"]

[[package]]
name = "pyparsing"
version = "3.0.9"
description = "pyparsing module - Classes and methods to define and execute parsing grammars"
category = "main"
optional = false
python-versions = ">=3.6.8"

[package.extras]
diagrams = ["jinja2", "railroad-diagrams"]

[[package]]
name = "python-dateutil"
version = "2.8.2"
description = "Extensions to the standard Python datetime module"
category = "main"
optional = false
python-versions = "!=3.0.*,!=3.1.*,!=3.2.*,>=2.7"

[package.dependencies]
six = ">=1.5"

[[package]]
name = "pytz"
version = "2022.2.1"
description = "World timezone definitions, modern and historical"
category = "main"
optional = false
python-versions = "*"

[[package]]
name = "PyYAML"
version = "6.0"
description = "YAML parser and emitter for Python"
category = "main"
optional = false
python-versions = ">=3.6"

[[package]]
name = "qdrant-client"
version = "0.10.2"
description = "Client library for the Qdrant vector search engine"
category = "main"
optional = false
python-versions = ">=3.7,<4.0"

[package.dependencies]
grpcio = ">=1.46.0,<2.0.0"
grpcio-tools = ">=1.48.0,<2.0.0"
httpx = {version = ">=0.23.0,<0.24.0", extras = ["http2"]}
loguru = ">=0.5.3,<0.6.0"
numpy = ">=1.21,<2.0"
pydantic = ">=1.8,<2.0"
tqdm = ">=4.56.0,<5.0.0"
typing-extensions = ">=4.0.0,<5.0.0"

[[package]]
name = "regex"
version = "2022.9.13"
description = "Alternative regular expression module, to replace re."
category = "main"
optional = false
python-versions = ">=3.6"

[[package]]
name = "requests"
version = "2.28.1"
description = "Python HTTP for Humans."
category = "main"
optional = false
python-versions = ">=3.7, <4"

[package.dependencies]
certifi = ">=2017.4.17"
charset-normalizer = ">=2,<3"
idna = ">=2.5,<4"
urllib3 = ">=1.21.1,<1.27"

[package.extras]
socks = ["PySocks (>=1.5.6,!=1.5.7)"]
use_chardet_on_py3 = ["chardet (>=3.0.2,<6)"]

[[package]]
name = "rfc3986"
version = "1.5.0"
description = "Validating URI References per RFC 3986"
category = "main"
optional = false
python-versions = "*"

[package.dependencies]
idna = {version = "*", optional = true, markers = "extra == \"idna2008\""}

[package.extras]
idna2008 = ["idna"]

[[package]]
name = "scikit-learn"
version = "1.1.2"
description = "A set of python modules for machine learning and data mining"
category = "main"
optional = false
python-versions = ">=3.8"

[package.dependencies]
joblib = ">=1.0.0"
numpy = ">=1.17.3"
scipy = ">=1.3.2"
threadpoolctl = ">=2.0.0"

[package.extras]
benchmark = ["matplotlib (>=3.1.2)", "memory-profiler (>=0.57.0)", "pandas (>=1.0.5)"]
docs = ["Pillow (>=7.1.2)", "matplotlib (>=3.1.2)", "memory-profiler (>=0.57.0)", "numpydoc (>=1.2.0)", "pandas (>=1.0.5)", "scikit-image (>=0.16.2)", "seaborn (>=0.9.0)", "sphinx (>=4.0.1)", "sphinx-gallery (>=0.7.0)", "sphinx-prompt (>=1.3.0)", "sphinxext-opengraph (>=0.4.2)"]
examples = ["matplotlib (>=3.1.2)", "pandas (>=1.0.5)", "scikit-image (>=0.16.2)", "seaborn (>=0.9.0)"]
tests = ["black (>=22.3.0)", "flake8 (>=3.8.2)", "matplotlib (>=3.1.2)", "mypy (>=0.961)", "numpydoc (>=1.2.0)", "pandas (>=1.0.5)", "pyamg (>=4.0.0)", "pytest (>=5.0.1)", "pytest-cov (>=2.9.0)", "scikit-image (>=0.16.2)"]

[[package]]
name = "scipy"
version = "1.9.1"
description = "SciPy: Scientific Library for Python"
category = "main"
optional = false
python-versions = ">=3.8,<3.12"

[package.dependencies]
numpy = ">=1.18.5,<1.25.0"

[[package]]
name = "sentence-transformers"
version = "2.2.2"
description = "Multilingual text embeddings"
category = "main"
optional = false
python-versions = ">=3.6.0"

[package.dependencies]
huggingface-hub = ">=0.4.0"
nltk = "*"
numpy = "*"
scikit-learn = "*"
scipy = "*"
sentencepiece = "*"
torch = ">=1.6.0"
torchvision = "*"
tqdm = "*"
transformers = ">=4.6.0,<5.0.0"

[[package]]
name = "sentencepiece"
version = "0.1.97"
description = "SentencePiece python wrapper"
category = "main"
optional = false
python-versions = "*"

[[package]]
name = "setuptools"
version = "65.4.0"
description = "Easily download, build, install, upgrade, and uninstall Python packages"
category = "main"
optional = false
python-versions = ">=3.7"

[package.extras]
docs = ["furo", "jaraco.packaging (>=9)", "jaraco.tidelift (>=1.4)", "pygments-github-lexers (==0.0.5)", "rst.linker (>=1.9)", "sphinx", "sphinx-favicon", "sphinx-hoverxref (<2)", "sphinx-inline-tabs", "sphinx-notfound-page (==0.8.3)", "sphinx-reredirects", "sphinxcontrib-towncrier"]
testing = ["build[virtualenv]", "filelock (>=3.4.0)", "flake8 (<5)", "flake8-2020", "ini2toml[lite] (>=0.9)", "jaraco.envs (>=2.2)", "jaraco.path (>=3.2.0)", "mock", "pip (>=19.1)", "pip-run (>=8.8)", "pytest (>=6)", "pytest-black (>=0.3.7)", "pytest-checkdocs (>=2.4)", "pytest-cov", "pytest-enabler (>=1.3)", "pytest-flake8", "pytest-mypy (>=0.9.1)", "pytest-perf", "pytest-xdist", "tomli-w (>=1.0.0)", "virtualenv (>=13.0.0)", "wheel"]
testing-integration = ["build[virtualenv]", "filelock (>=3.4.0)", "jaraco.envs (>=2.2)", "jaraco.path (>=3.2.0)", "pytest", "pytest-enabler", "pytest-xdist", "tomli", "virtualenv (>=13.0.0)", "wheel"]

[[package]]
name = "six"
version = "1.16.0"
description = "Python 2 and 3 compatibility utilities"
category = "main"
optional = false
python-versions = ">=2.7, !=3.0.*, !=3.1.*, !=3.2.*"

[[package]]
name = "sniffio"
version = "1.3.0"
description = "Sniff out which async library your code is running under"
category = "main"
optional = false
python-versions = ">=3.7"

[[package]]
name = "starlette"
version = "0.14.2"
description = "The little ASGI library that shines."
category = "main"
optional = false
python-versions = ">=3.6"

[package.extras]
full = ["aiofiles", "graphene", "itsdangerous", "jinja2", "python-multipart", "pyyaml", "requests"]

[[package]]
name = "threadpoolctl"
version = "3.1.0"
description = "threadpoolctl"
category = "main"
optional = false
python-versions = ">=3.6"

[[package]]
name = "tokenizers"
version = "0.12.1"
description = "Fast and Customizable Tokenizers"
category = "main"
optional = false
python-versions = "*"

[package.extras]
docs = ["setuptools-rust", "sphinx", "sphinx-rtd-theme"]
testing = ["datasets", "numpy", "pytest", "requests"]

[[package]]
name = "torch"
version = "1.12.1"
description = "Tensors and Dynamic neural networks in Python with strong GPU acceleration"
category = "main"
optional = false
python-versions = ">=3.7.0"

[package.dependencies]
typing-extensions = "*"

[[package]]
name = "torchvision"
version = "0.13.1"
description = "image and video datasets and models for torch deep learning"
category = "main"
optional = false
python-versions = ">=3.7"

[package.dependencies]
numpy = "*"
pillow = ">=5.3.0,<8.3.0 || >=8.4.0"
requests = "*"
torch = "1.12.1"
typing-extensions = "*"

[package.extras]
scipy = ["scipy"]

[[package]]
name = "tqdm"
version = "4.64.1"
description = "Fast, Extensible Progress Meter"
category = "main"
optional = false
python-versions = "!=3.0.*,!=3.1.*,!=3.2.*,!=3.3.*,>=2.7"

[package.dependencies]
colorama = {version = "*", markers = "platform_system == \"Windows\""}

[package.extras]
dev = ["py-make (>=0.1.0)", "twine", "wheel"]
notebook = ["ipywidgets (>=6)"]
slack = ["slack-sdk"]
telegram = ["requests"]

[[package]]
name = "transformers"
version = "4.22.1"
description = "State-of-the-art Machine Learning for JAX, PyTorch and TensorFlow"
category = "main"
optional = false
python-versions = ">=3.7.0"

[package.dependencies]
filelock = "*"
huggingface-hub = ">=0.9.0,<1.0"
numpy = ">=1.17"
packaging = ">=20.0"
pyyaml = ">=5.1"
regex = "!=2019.12.17"
requests = "*"
tokenizers = ">=0.11.1,<0.11.3 || >0.11.3,<0.13"
tqdm = ">=4.27"

[package.extras]
accelerate = ["accelerate (>=0.10.0)"]
all = ["Pillow", "accelerate (>=0.10.0)", "codecarbon (==1.2.0)", "flax (>=0.4.1)", "jax (>=0.2.8,!=0.3.2,<=0.3.6)", "jaxlib (>=0.1.65,<=0.3.6)", "librosa", "onnxconverter-common", "optax (>=0.0.8)", "optuna", "phonemizer", "protobuf (<=3.20.1)", "pyctcdecode (>=0.3.0)", "ray[tune]", "sentencepiece (>=0.1.91,!=0.1.92)", "sigopt", "tensorflow (>=2.3)", "tensorflow-text", "tf2onnx", "timm", "tokenizers (>=0.11.1,!=0.11.3,<0.13)", "torch (>=1.0)", "torchaudio"]
audio = ["librosa", "phonemizer", "pyctcdecode (>=0.3.0)"]
codecarbon = ["codecarbon (==1.2.0)"]
deepspeed = ["accelerate (>=0.10.0)", "deepspeed (>=0.6.5)"]
deepspeed-testing = ["GitPython (<3.1.19)", "accelerate (>=0.10.0)", "black (==22.3)", "cookiecutter (==1.7.3)", "datasets", "deepspeed (>=0.6.5)", "dill (<0.3.5)", "evaluate (>=0.2.0)", "faiss-cpu", "hf-doc-builder (>=0.3.0)", "nltk", "optuna", "parameterized", "protobuf (<=3.20.1)", "psutil", "pytest", "pytest-timeout", "pytest-xdist", "rjieba", "rouge-score (!=0.0.7,!=0.0.8,!=0.1,!=0.1.1)", "sacrebleu (>=1.4.12,<2.0.0)", "sacremoses", "timeout-decorator"]
dev = ["GitPython (<3.1.19)", "Pillow", "accelerate (>=0.10.0)", "black (==22.3)", "codecarbon (==1.2.0)", "cookiecutter (==1.7.3)", "datasets", "dill (<0.3.5)", "evaluate (>=0.2.0)", "faiss-cpu", "flake8 (>=3.8.3)", "flax (>=0.4.1)", "fugashi (>=1.0)", "hf-doc-builder", "hf-doc-builder (>=0.3.0)", "ipadic (>=1.0.0,<2.0)", "isort (>=5.5.4)", "jax (>=0.2.8,!=0.3.2,<=0.3.6)", "jaxlib (>=0.1.65,<=0.3.6)", "librosa", "nltk", "onnxconverter-common", "optax (>=0.0.8)", "optuna", "parameterized", "phonemizer", "protobuf (<=3.20.1)", "psutil", "pyctcdecode (>=0.3.0)", "pytest", "pytest-timeout", "pytest-xdist", "ray[tune]", "rjieba", "rouge-score (!=0.0.7,!=0.0.8,!=0.1,!=0.1.1)", "sacrebleu (>=1.4.12,<2.0.0)", "sacremoses", "scikit-learn", "sentencepiece (>=0.1.91,!=0.1.92)", "sigopt", "tensorflow (>=2.3)", "tensorflow-text", "tf2onnx", "timeout-decorator", "timm", "tokenizers (>=0.11.1,!=0.11.3,<0.13)", "torch (>=1.0)", "torchaudio", "unidic (>=1.0.2)", "unidic-lite (>=1.0.7)"]
dev-tensorflow = ["GitPython (<3.1.19)", "Pillow", "black (==22.3)", "cookiecutter (==1.7.3)", "datasets", "dill (<0.3.5)", "evaluate (>=0.2.0)", "faiss-cpu", "flake8 (>=3.8.3)", "hf-doc-builder", "hf-doc-builder (>=0.3.0)", "isort (>=5.5.4)", "librosa", "nltk", "onnxconverter-common", "onnxruntime (>=1.4.0)", "onnxruntime-tools (>=1.4.2)", "parameterized", "phonemizer", "protobuf (<=3.20.1)", "psutil", "pyctcdecode (>=0.3.0)", "pytest", "pytest-timeout", "pytest-xdist", "rjieba", "rouge-score (!=0.0.7,!=0.0.8,!=0.1,!=0.1.1)", "sacrebleu (>=1.4.12,<2.0.0)", "sacremoses", "scikit-learn", "sentencepiece (>=0.1.91,!=0.1.92)", "tensorflow (>=2.3)", "tensorflow-text", "tf2onnx", "timeout-decorator", "tokenizers (>=0.11.1,!=0.11.3,<0.13)"]
dev-torch = ["GitPython (<3.1.19)", "Pillow", "black (==22.3)", "codecarbon (==1.2.0)", "cookiecutter (==1.7.3)", "datasets", "dill (<0.3.5)", "evaluate (>=0.2.0)", "faiss-cpu", "flake8 (>=3.8.3)", "fugashi (>=1.0)", "hf-doc-builder", "hf-doc-builder (>=0.3.0)", "ipadic (>=1.0.0,<2.0)", "isort (>=5.5.4)", "librosa", "nltk", "onnxruntime (>=1.4.0)", "onnxruntime-tools (>=1.4.2)", "optuna", "parameterized", "phonemizer", "protobuf (<=3.20.1)", "psutil", "pyctcdecode (>=0.3.0)", "pytest", "pytest-timeout", "pytest-xdist", "ray[tune]", "rjieba", "rouge-score (!=0.0.7,!=0.0.8,!=0.1,!=0.1.1)", "sacrebleu (>=1.4.12,<2.0.0)", "sacremoses", "scikit-learn", "sentencepiece (>=0.1.91,!=0.1.92)", "sigopt", "timeout-decorator", "timm", "tokenizers (>=0.11.1,!=0.11.3,<0.13)", "torch (>=1.0)", "torchaudio", "unidic (>=1.0.2)", "unidic-lite (>=1.0.7)"]
docs = ["Pillow", "accelerate (>=0.10.0)", "codecarbon (==1.2.0)", "flax (>=0.4.1)", "hf-doc-builder", "jax (>=0.2.8,!=0.3.2,<=0.3.6)", "jaxlib (>=0.1.65,<=0.3.6)", "librosa", "onnxconverter-common", "optax (>=0.0.8)", "optuna", "phonemizer", "protobuf (<=3.20.1)", "pyctcdecode (>=0.3.0)", "ray[tune]", "sentencepiece (>=0.1.91,!=0.1.92)", "sigopt", "tensorflow (>=2.3)", "tensorflow-text", "tf2onnx", "timm", "tokenizers (>=0.11.1,!=0.11.3,<0.13)", "torch (>=1.0)", "torchaudio"]
docs_specific = ["hf-doc-builder"]
fairscale = ["fairscale (>0.3)"]
flax = ["flax (>=0.4.1)", "jax (>=0.2.8,!=0.3.2,<=0.3.6)", "jaxlib (>=0.1.65,<=0.3.6)", "optax (>=0.0.8)"]
flax-speech = ["librosa", "phonemizer", "pyctcdecode (>=0.3.0)"]
ftfy = ["ftfy"]
integrations = ["optuna", "ray[tune]", "sigopt"]
ja = ["fugashi (>=1.0)", "ipadic (>=1.0.0,<2.0)", "unidic (>=1.0.2)", "unidic-lite (>=1.0.7)"]
modelcreation = ["cookiecutter (==1.7.3)"]
onnx = ["onnxconverter-common", "onnxruntime (>=1.4.0)", "onnxruntime-tools (>=1.4.2)", "tf2onnx"]
onnxruntime = ["onnxruntime (>=1.4.0)", "onnxruntime-tools (>=1.4.2)"]
optuna = ["optuna"]
quality = ["GitPython (<3.1.19)", "black (==22.3)", "flake8 (>=3.8.3)", "hf-doc-builder (>=0.3.0)", "isort (>=5.5.4)"]
ray = ["ray[tune]"]
retrieval = ["datasets", "faiss-cpu"]
sagemaker = ["sagemaker (>=2.31.0)"]
sentencepiece = ["protobuf (<=3.20.1)", "sentencepiece (>=0.1.91,!=0.1.92)"]
serving = ["fastapi", "pydantic", "starlette", "uvicorn"]
sigopt = ["sigopt"]
sklearn = ["scikit-learn"]
speech = ["librosa", "phonemizer", "pyctcdecode (>=0.3.0)", "torchaudio"]
testing = ["GitPython (<3.1.19)", "black (==22.3)", "cookiecutter (==1.7.3)", "datasets", "dill (<0.3.5)", "evaluate (>=0.2.0)", "faiss-cpu", "hf-doc-builder (>=0.3.0)", "nltk", "parameterized", "protobuf (<=3.20.1)", "psutil", "pytest", "pytest-timeout", "pytest-xdist", "rjieba", "rouge-score (!=0.0.7,!=0.0.8,!=0.1,!=0.1.1)", "sacrebleu (>=1.4.12,<2.0.0)", "sacremoses", "timeout-decorator"]
tf = ["onnxconverter-common", "tensorflow (>=2.3)", "tensorflow-text", "tf2onnx"]
tf-cpu = ["onnxconverter-common", "tensorflow-cpu (>=2.3)", "tensorflow-text", "tf2onnx"]
tf-speech = ["librosa", "phonemizer", "pyctcdecode (>=0.3.0)"]
timm = ["timm"]
tokenizers = ["tokenizers (>=0.11.1,!=0.11.3,<0.13)"]
torch = ["torch (>=1.0)"]
torch-speech = ["librosa", "phonemizer", "pyctcdecode (>=0.3.0)", "torchaudio"]
torchhub = ["filelock", "huggingface-hub (>=0.9.0,<1.0)", "importlib-metadata", "numpy (>=1.17)", "packaging (>=20.0)", "protobuf (<=3.20.1)", "regex (!=2019.12.17)", "requests", "sentencepiece (>=0.1.91,!=0.1.92)", "tokenizers (>=0.11.1,!=0.11.3,<0.13)", "torch (>=1.0)", "tqdm (>=4.27)"]
vision = ["Pillow"]

[[package]]
name = "typing-extensions"
version = "4.3.0"
description = "Backported and Experimental Type Hints for Python 3.7+"
category = "main"
optional = false
python-versions = ">=3.7"

[[package]]
name = "urllib3"
version = "1.26.12"
description = "HTTP library with thread-safe connection pooling, file post, and more."
category = "main"
optional = false
python-versions = ">=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, !=3.4.*, !=3.5.*, <4"

[package.extras]
brotli = ["brotli (>=1.0.9)", "brotlicffi (>=0.8.0)", "brotlipy (>=0.6.0)"]
secure = ["certifi", "cryptography (>=1.3.4)", "idna (>=2.0.0)", "ipaddress", "pyOpenSSL (>=0.14)", "urllib3-secure-extra"]
socks = ["PySocks (>=1.5.6,!=1.5.7,<2.0)"]

[[package]]
name = "uvicorn"
version = "0.12.3"
description = "The lightning-fast ASGI server."
category = "main"
optional = false
python-versions = "*"

[package.dependencies]
click = ">=7.0.0,<8.0.0"
h11 = ">=0.8"

[package.extras]
standard = ["PyYAML (>=5.1)", "colorama (>=0.4)", "httptools (>=0.1.0,<0.2.0)", "python-dotenv (>=0.13)", "uvloop (>=0.14.0)", "watchgod (>=0.6,<0.7)", "websockets (>=8.0.0,<9.0.0)"]

[[package]]
name = "win32-setctime"
version = "1.1.0"
description = "A small Python utility to set file creation time on Windows"
category = "main"
optional = false
python-versions = ">=3.5"

[package.extras]
dev = ["black (>=19.3b0)", "pytest (>=4.6.2)"]

[metadata]
lock-version = "1.1"
python-versions = ">=3.8,<3.12"
content-hash = "697aad5d560f1f4eb0709f6169146fc0cb7bf7a9bf9f11e4655fba2adf92924e"

[metadata.files]
anyio = [
    {file = "anyio-3.6.1-py3-none-any.whl", hash = "sha256:cb29b9c70620506a9a8f87a309591713446953302d7d995344d0d7c6c0c9a7be"},
    {file = "anyio-3.6.1.tar.gz", hash = "sha256:413adf95f93886e442aea925f3ee43baa5a765a64a0f52c6081894f9992fdd0b"},
]
certifi = [
    {file = "certifi-2022.9.24-py3-none-any.whl", hash = "sha256:90c1a32f1d68f940488354e36370f6cca89f0f106db09518524c88d6ed83f382"},
    {file = "certifi-2022.9.24.tar.gz", hash = "sha256:0d9c601124e5a6ba9712dbc60d9c53c21e34f5f641fe83002317394311bdce14"},
]
charset-normalizer = [
    {file = "charset-normalizer-2.1.1.tar.gz", hash = "sha256:5a3d016c7c547f69d6f81fb0db9449ce888b418b5b9952cc5e6e66843e9dd845"},
    {file = "charset_normalizer-2.1.1-py3-none-any.whl", hash = "sha256:83e9a75d1911279afd89352c68b45348559d1fc0506b054b346651b5e7fee29f"},
]
click = [
    {file = "click-7.1.2-py2.py3-none-any.whl", hash = "sha256:dacca89f4bfadd5de3d7489b7c8a566eee0d3676333fbb50030263894c38c0dc"},
    {file = "click-7.1.2.tar.gz", hash = "sha256:d2b5255c7c6349bc1bd1e59e08cd12acbbd63ce649f2588755783aa94dfb6b1a"},
]
colorama = [
    {file = "colorama-0.4.5-py2.py3-none-any.whl", hash = "sha256:854bf444933e37f5824ae7bfc1e98d5bce2ebe4160d46b5edf346a89358e99da"},
    {file = "colorama-0.4.5.tar.gz", hash = "sha256:e6c6b4334fc50988a639d9b98aa429a0b57da6e17b9a44f0451f930b6967b7a4"},
]
fastapi = [
    {file = "fastapi-0.67.0-py3-none-any.whl", hash = "sha256:b05f5af77af3b21cab896b8dade8b383b2d2f254caae4681a56313e29196f1ac"},
    {file = "fastapi-0.67.0.tar.gz", hash = "sha256:24f45d65e589db3bab162c02a1e2e8b798c098861b1fa3e266efeb71b4faa8e2"},
]
filelock = [
    {file = "filelock-3.8.0-py3-none-any.whl", hash = "sha256:617eb4e5eedc82fc5f47b6d61e4d11cb837c56cb4544e39081099fa17ad109d4"},
    {file = "filelock-3.8.0.tar.gz", hash = "sha256:55447caa666f2198c5b6b13a26d2084d26fa5b115c00d065664b2124680c4edc"},
]
grpcio = [
    {file = "grpcio-1.49.1-cp310-cp310-linux_armv7l.whl", hash = "sha256:fd86040232e805b8e6378b2348c928490ee595b058ce9aaa27ed8e4b0f172b20"},
    {file = "grpcio-1.49.1-cp310-cp310-macosx_10_10_x86_64.whl", hash = "sha256:6fd0c9cede9552bf00f8c5791d257d5bf3790d7057b26c59df08be5e7a1e021d"},
    {file = "grpcio-1.49.1-cp310-cp310-manylinux_2_17_aarch64.whl", hash = "sha256:d0d402e158d4e84e49c158cb5204119d55e1baf363ee98d6cb5dce321c3a065d"},
    {file = "grpcio-1.49.1-cp310-cp310-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:822ceec743d42a627e64ea266059a62d214c5a3cdfcd0d7fe2b7a8e4e82527c7"},
    {file = "grpcio-1.49.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:2106d9c16527f0a85e2eea6e6b91a74fc99579c60dd810d8690843ea02bc0f5f"},
    {file = "grpcio-1.49.1-cp310-cp310-musllinux_1_1_i686.whl", hash = "sha256:52dd02b7e7868233c571b49bc38ebd347c3bb1ff8907bb0cb74cb5f00c790afc"},
    {file = "grpcio-1.49.1-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:120fecba2ec5d14b5a15d11063b39783fda8dc8d24addd83196acb6582cabd9b"},
    {file = "grpcio-1.49.1-cp310-cp310-win32.whl", hash = "sha256:f1a3b88e3c53c1a6e6bed635ec1bbb92201bb6a1f2db186179f7f3f244829788"},
    {file = "grpcio-1.49.1-cp310-cp310-win_amd64.whl", hash = "sha256:a7d0017b92d3850abea87c1bdec6ea41104e71c77bca44c3e17f175c6700af62"},
    {file = "grpcio-1.49.1-cp311-cp311-linux_armv7l.whl", hash = "sha256:9fb17ff8c0d56099ac6ebfa84f670c5a62228d6b5c695cf21c02160c2ac1446b"},
    {file = "grpcio-1.49.1-cp311-cp311-macosx_10_10_x86_64.whl", hash = "sha256:075f2d06e3db6b48a2157a1bcd52d6cbdca980dd18988fe6afdb41795d51625f"},
    {file = "grpcio-1.49.1-cp311-cp311-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:46d93a1b4572b461a227f1db6b8d35a88952db1c47e5fadcf8b8a2f0e1dd9201"},
    {file = "grpcio-1.49.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:dc79b2b37d779ac42341ddef40ad5bf0966a64af412c89fc2b062e3ddabb093f"},
    {file = "grpcio-1.49.1-cp311-cp311-musllinux_1_1_i686.whl", hash = "sha256:5f8b3a971c7820ea9878f3fd70086240a36aeee15d1b7e9ecbc2743b0e785568"},
    {file = "grpcio-1.49.1-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:49b301740cf5bc8fed4fee4c877570189ae3951432d79fa8e524b09353659811"},
    {file = "grpcio-1.49.1-cp311-cp311-win32.whl", hash = "sha256:1c66a25afc6c71d357867b341da594a5587db5849b48f4b7d5908d236bb62ede"},
    {file = "grpcio-1.49.1-cp311-cp311-win_amd64.whl", hash = "sha256:6b6c3a95d27846f4145d6967899b3ab25fffc6ae99544415e1adcacef84842d2"},
    {file = "grpcio-1.49.1-cp37-cp37m-linux_armv7l.whl", hash = "sha256:1cc400c8a2173d1c042997d98a9563e12d9bb3fb6ad36b7f355bc77c7663b8af"},
    {file = "grpcio-1.49.1-cp37-cp37m-macosx_10_10_x86_64.whl", hash = "sha256:34f736bd4d0deae90015c0e383885b431444fe6b6c591dea288173df20603146"},
    {file = "grpcio-1.49.1-cp37-cp37m-manylinux_2_17_aarch64.whl", hash = "sha256:196082b9c89ebf0961dcd77cb114bed8171964c8e3063b9da2fb33536a6938ed"},
    {file = "grpcio-1.49.1-cp37-cp37m-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:8c9f89c42749890618cd3c2464e1fbf88446e3d2f67f1e334c8e5db2f3272bbd"},
    {file = "grpcio-1.49.1-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:64419cb8a5b612cdb1550c2fd4acbb7d4fb263556cf4625f25522337e461509e"},
    {file = "grpcio-1.49.1-cp37-cp37m-musllinux_1_1_i686.whl", hash = "sha256:8a5272061826e6164f96e3255405ef6f73b88fd3e8bef464c7d061af8585ac62"},
    {file = "grpcio-1.49.1-cp37-cp37m-musllinux_1_1_x86_64.whl", hash = "sha256:ea9d0172445241ad7cb49577314e39d0af2c5267395b3561d7ced5d70458a9f3"},
    {file = "grpcio-1.49.1-cp37-cp37m-win32.whl", hash = "sha256:2070e87d95991473244c72d96d13596c751cb35558e11f5df5414981e7ed2492"},
    {file = "grpcio-1.49.1-cp37-cp37m-win_amd64.whl", hash = "sha256:4fcedcab49baaa9db4a2d240ac81f2d57eb0052b1c6a9501b46b8ae912720fbf"},
    {file = "grpcio-1.49.1-cp38-cp38-linux_armv7l.whl", hash = "sha256:afbb3475cf7f4f7d380c2ca37ee826e51974f3e2665613996a91d6a58583a534"},
    {file = "grpcio-1.49.1-cp38-cp38-macosx_10_10_x86_64.whl", hash = "sha256:a4f9ba141380abde6c3adc1727f21529137a2552002243fa87c41a07e528245c"},
    {file = "grpcio-1.49.1-cp38-cp38-manylinux_2_17_aarch64.whl", hash = "sha256:cf0a1fb18a7204b9c44623dfbd1465b363236ce70c7a4ed30402f9f60d8b743b"},
    {file = "grpcio-1.49.1-cp38-cp38-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:17bb6fe72784b630728c6cff9c9d10ccc3b6d04e85da6e0a7b27fb1d135fac62"},
    {file = "grpcio-1.49.1-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:18305d5a082d1593b005a895c10041f833b16788e88b02bb81061f5ebcc465df"},
    {file = "grpcio-1.49.1-cp38-cp38-musllinux_1_1_i686.whl", hash = "sha256:b6a1b39e59ac5a3067794a0e498911cf2e37e4b19ee9e9977dc5e7051714f13f"},
    {file = "grpcio-1.49.1-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:0e20d59aafc086b1cc68400463bddda6e41d3e5ed30851d1e2e0f6a2e7e342d3"},
    {file = "grpcio-1.49.1-cp38-cp38-win32.whl", hash = "sha256:e1e83233d4680863a421f3ee4a7a9b80d33cd27ee9ed7593bc93f6128302d3f2"},
    {file = "grpcio-1.49.1-cp38-cp38-win_amd64.whl", hash = "sha256:221d42c654d2a41fa31323216279c73ed17d92f533bc140a3390cc1bd78bf63c"},
    {file = "grpcio-1.49.1-cp39-cp39-linux_armv7l.whl", hash = "sha256:fa9e6e61391e99708ac87fc3436f6b7b9c6b845dc4639b406e5e61901e1aacde"},
    {file = "grpcio-1.49.1-cp39-cp39-macosx_10_10_x86_64.whl", hash = "sha256:9b449e966ef518ce9c860d21f8afe0b0f055220d95bc710301752ac1db96dd6a"},
    {file = "grpcio-1.49.1-cp39-cp39-manylinux_2_17_aarch64.whl", hash = "sha256:aa34d2ad9f24e47fa9a3172801c676e4037d862247e39030165fe83821a7aafd"},
    {file = "grpcio-1.49.1-cp39-cp39-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:5207f4eed1b775d264fcfe379d8541e1c43b878f2b63c0698f8f5c56c40f3d68"},
    {file = "grpcio-1.49.1-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:0b24a74651438d45619ac67004638856f76cc13d78b7478f2457754cbcb1c8ad"},
    {file = "grpcio-1.49.1-cp39-cp39-musllinux_1_1_i686.whl", hash = "sha256:fe763781669790dc8b9618e7e677c839c87eae6cf28b655ee1fa69ae04eea03f"},
    {file = "grpcio-1.49.1-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:2f2ff7ba0f8f431f32d4b4bc3a3713426949d3533b08466c4ff1b2b475932ca8"},
    {file = "grpcio-1.49.1-cp39-cp39-win32.whl", hash = "sha256:08ff74aec8ff457a89b97152d36cb811dcc1d17cd5a92a65933524e363327394"},
    {file = "grpcio-1.49.1-cp39-cp39-win_amd64.whl", hash = "sha256:274ffbb39717918c514b35176510ae9be06e1d93121e84d50b350861dcb9a705"},
    {file = "grpcio-1.49.1.tar.gz", hash = "sha256:d4725fc9ec8e8822906ae26bb26f5546891aa7fbc3443de970cc556d43a5c99f"},
]
grpcio-tools = [
    {file = "grpcio-tools-1.49.1.tar.gz", hash = "sha256:84cc64e5b46bad43d5d7bd2fd772b656eba0366961187a847e908e2cb735db91"},
    {file = "grpcio_tools-1.49.1-cp310-cp310-linux_armv7l.whl", hash = "sha256:2dfb6c7ece84d46bd690b23d3e060d18115c8bc5047d2e8a33e6747ed323a348"},
    {file = "grpcio_tools-1.49.1-cp310-cp310-macosx_10_10_x86_64.whl", hash = "sha256:8f452a107c054a04db2570f7851a07f060313c6e841b0d394ce6030d598290e6"},
    {file = "grpcio_tools-1.49.1-cp310-cp310-manylinux_2_17_aarch64.whl", hash = "sha256:6a198871b582287213c4d70792bf275e1d7cf34eed1d019f534ddf4cd15ab039"},
    {file = "grpcio_tools-1.49.1-cp310-cp310-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:a0cca67a7d0287bdc855d81fdd38dc949c4273273a74f832f9e520abe4f20bc6"},
    {file = "grpcio_tools-1.49.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:bdaff4c89eecb37c247b93025410db68114d97fa093cbb028e9bd7cda5912473"},
    {file = "grpcio_tools-1.49.1-cp310-cp310-musllinux_1_1_i686.whl", hash = "sha256:bb8773118ad315db317d7b22b5ff75d649ca20931733281209e7cbd8c0fad53e"},
    {file = "grpcio_tools-1.49.1-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:7cc5534023735b8a8f56760b7c533918f874ce5a9064d7c5456d2709ae2b31f9"},
    {file = "grpcio_tools-1.49.1-cp310-cp310-win32.whl", hash = "sha256:d277642acbe305f5586f9597b78fb9970d6633eb9f89c61e429c92c296c37129"},
    {file = "grpcio_tools-1.49.1-cp310-cp310-win_amd64.whl", hash = "sha256:eed599cf08fc1a06c72492d3c5750c32f58de3750eddd984af1f257c14326701"},
    {file = "grpcio_tools-1.49.1-cp311-cp311-linux_armv7l.whl", hash = "sha256:9e5c13809ab2f245398e8446c4c3b399a62d591db651e46806cccf52a700452e"},
    {file = "grpcio_tools-1.49.1-cp311-cp311-macosx_10_10_x86_64.whl", hash = "sha256:ab3d0ee9623720ee585fdf3753b3755d3144a4a8ae35bca8e3655fa2f41056be"},
    {file = "grpcio_tools-1.49.1-cp311-cp311-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:6ba87e3512bc91d78bf9febcfb522eadda171d2d4ddaf886066b0f01aa4929ad"},
    {file = "grpcio_tools-1.49.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:13e13b3643e7577a3ec13b79689eb4d7548890b1e104c04b9ed6557a3c3dd452"},
    {file = "grpcio_tools-1.49.1-cp311-cp311-musllinux_1_1_i686.whl", hash = "sha256:324f67d9cb4b7058b6ce45352fb64c20cc1fa04c34d97ad44772cfe6a4ae0cf5"},
    {file = "grpcio_tools-1.49.1-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:a64bab81b220c50033f584f57978ebbea575f09c1ccee765cd5c462177988098"},
    {file = "grpcio_tools-1.49.1-cp311-cp311-win32.whl", hash = "sha256:f632d376f92f23e5931697a3acf1b38df7eb719774213d93c52e02acd2d529ac"},
    {file = "grpcio_tools-1.49.1-cp311-cp311-win_amd64.whl", hash = "sha256:28ff2b978d9509474928b9c096a0cce4eaa9c8f7046136aee1545f6211ed8126"},
    {file = "grpcio_tools-1.49.1-cp37-cp37m-linux_armv7l.whl", hash = "sha256:46afd3cb7e555187451a5d283f108cdef397952a662cb48680afc615b158864a"},
    {file = "grpcio_tools-1.49.1-cp37-cp37m-macosx_10_10_x86_64.whl", hash = "sha256:9284568b728e41fa8f7e9c2e7399545d605f75d8072ef0e9aa2a05655cb679eb"},
    {file = "grpcio_tools-1.49.1-cp37-cp37m-manylinux_2_17_aarch64.whl", hash = "sha256:aa34442cf787732cb41f2aa6172007e24f480b8b9d3dc5166de80d63e9072ea4"},
    {file = "grpcio_tools-1.49.1-cp37-cp37m-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:3b8c9eb5a4250905414cd53a68caea3eb8f0c515aadb689e6e81b71ebe9ab5c6"},
    {file = "grpcio_tools-1.49.1-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:ab15db024051bf21feb21c29cb2c3ea0a2e4f5cf341d46ef76e17fcf6aaef164"},
    {file = "grpcio_tools-1.49.1-cp37-cp37m-musllinux_1_1_i686.whl", hash = "sha256:502084b622f758bef620a9107c2db9fcdf66d26c7e0e481d6bb87db4dc917d70"},
    {file = "grpcio_tools-1.49.1-cp37-cp37m-musllinux_1_1_x86_64.whl", hash = "sha256:4085890b77c640085f82bf1e90a0ea166ce48000bc2f5180914b974783c9c0a8"},
    {file = "grpcio_tools-1.49.1-cp37-cp37m-win32.whl", hash = "sha256:da0edb984699769ce02e18e3392d54b59a7a3f93acd285a68043f5bde4fc028e"},
    {file = "grpcio_tools-1.49.1-cp37-cp37m-win_amd64.whl", hash = "sha256:9887cd622770271101a7dd1832845d64744c3f88fd11ccb2620394079197a42e"},
    {file = "grpcio_tools-1.49.1-cp38-cp38-linux_armv7l.whl", hash = "sha256:8440fe7dae6a40c279e3a24b82793735babd38ecbb0d07bb712ff9c8963185d9"},
    {file = "grpcio_tools-1.49.1-cp38-cp38-macosx_10_10_x86_64.whl", hash = "sha256:b5de2bb7dd6b6231da9b1556ade981513330b740e767f1d902c71ceee0a7d196"},
    {file = "grpcio_tools-1.49.1-cp38-cp38-manylinux_2_17_aarch64.whl", hash = "sha256:1e6f06a763aea7836b63d9c117347f2bf7038008ceef72758815c9e09c5fb1fc"},
    {file = "grpcio_tools-1.49.1-cp38-cp38-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:e31562f90120318c5395aabec0f2f69ad8c14b6676996b7730d9d2eaf9415d57"},
    {file = "grpcio_tools-1.49.1-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:49ef9a4e389a618157a9daa9fafdfeeaef1ece9adda7f50f85db928f24d4b3e8"},
    {file = "grpcio_tools-1.49.1-cp38-cp38-musllinux_1_1_i686.whl", hash = "sha256:b384cb8e8d9bcb55ee8f9b064374561c7a1a05d848249581403d36fc7060032f"},
    {file = "grpcio_tools-1.49.1-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:73732f77943ac3e898879cbb29c27253aa3c47566b8a59780fd24c6a54de1b66"},
    {file = "grpcio_tools-1.49.1-cp38-cp38-win32.whl", hash = "sha256:b594b2745a5ba9e7a76ce561bc5ab40bc65bb44743c505529b1e4f12af29104d"},
    {file = "grpcio_tools-1.49.1-cp38-cp38-win_amd64.whl", hash = "sha256:680fbc88f8709ddcabb88f86749f2d8e429160890cff2c70680880a6970d4eef"},
    {file = "grpcio_tools-1.49.1-cp39-cp39-linux_armv7l.whl", hash = "sha256:e8c3869121860f6767eedb7d24fc54dfd71e737fdfbb26e1334684606f3274fd"},
    {file = "grpcio_tools-1.49.1-cp39-cp39-macosx_10_10_x86_64.whl", hash = "sha256:73e9d7c886ba10e20c97d1dab0ff961ba5800757ae5e31be21b1cda8130c52f8"},
    {file = "grpcio_tools-1.49.1-cp39-cp39-manylinux_2_17_aarch64.whl", hash = "sha256:1760de2dd2c4f08de87b039043a4797f3c17193656e7e3eb84e92f0517083c0c"},
    {file = "grpcio_tools-1.49.1-cp39-cp39-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:cd4b1e216dd04d9245ee8f4e601a1f98c25e6e417ea5cf8d825c50589a8b447e"},
    {file = "grpcio_tools-1.49.1-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:c1c28751ab5955cae563d07677e799233f0fe1c0fc49d9cbd61ff1957e83617f"},
    {file = "grpcio_tools-1.49.1-cp39-cp39-musllinux_1_1_i686.whl", hash = "sha256:c24239c3ee9ed16314c14b4e24437b5079ebc344f343f33629a582f8699f583b"},
    {file = "grpcio_tools-1.49.1-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:892d3dacf1942820f0b7a868a30e6fbcdf5bec08543b682c7274b0101cee632d"},
    {file = "grpcio_tools-1.49.1-cp39-cp39-win32.whl", hash = "sha256:704d21509ec06efc9d034dbe70e7152715aac004941f4f0f553cf3a0aff15bd5"},
    {file = "grpcio_tools-1.49.1-cp39-cp39-win_amd64.whl", hash = "sha256:1efa0c221c719433f441ac0e026fc3c4dbc9a1a08a552ecdc707775e2f2fbbae"},
]
h11 = [
    {file = "h11-0.12.0-py3-none-any.whl", hash = "sha256:36a3cb8c0a032f56e2da7084577878a035d3b61d104230d4bd49c0c6b555a9c6"},
    {file = "h11-0.12.0.tar.gz", hash = "sha256:47222cb6067e4a307d535814917cd98fd0a57b6788ce715755fa2b6c28b56042"},
]
h2 = [
    {file = "h2-4.1.0-py3-none-any.whl", hash = "sha256:03a46bcf682256c95b5fd9e9a99c1323584c3eec6440d379b9903d709476bc6d"},
    {file = "h2-4.1.0.tar.gz", hash = "sha256:a83aca08fbe7aacb79fec788c9c0bac936343560ed9ec18b82a13a12c28d2abb"},
]
hpack = [
    {file = "hpack-4.0.0-py3-none-any.whl", hash = "sha256:84a076fad3dc9a9f8063ccb8041ef100867b1878b25ef0ee63847a5d53818a6c"},
    {file = "hpack-4.0.0.tar.gz", hash = "sha256:fc41de0c63e687ebffde81187a948221294896f6bdc0ae2312708df339430095"},
]
httpcore = [
    {file = "httpcore-0.15.0-py3-none-any.whl", hash = "sha256:1105b8b73c025f23ff7c36468e4432226cbb959176eab66864b8e31c4ee27fa6"},
    {file = "httpcore-0.15.0.tar.gz", hash = "sha256:18b68ab86a3ccf3e7dc0f43598eaddcf472b602aba29f9aa6ab85fe2ada3980b"},
]
httpx = [
    {file = "httpx-0.23.0-py3-none-any.whl", hash = "sha256:42974f577483e1e932c3cdc3cd2303e883cbfba17fe228b0f63589764d7b9c4b"},
    {file = "httpx-0.23.0.tar.gz", hash = "sha256:f28eac771ec9eb4866d3fb4ab65abd42d38c424739e80c08d8d20570de60b0ef"},
]
huggingface-hub = [
    {file = "huggingface_hub-0.9.1-py3-none-any.whl", hash = "sha256:7a588046bdeb84e7bc99b3da58bbb4312a56d94ba51ebc60dfe610c18b3d0b9f"},
    {file = "huggingface_hub-0.9.1.tar.gz", hash = "sha256:6395f26aaf44bbb4a73d3e14aca228fa39534696f651c6c82a6347f8c9f5950b"},
]
hyperframe = [
    {file = "hyperframe-6.0.1-py3-none-any.whl", hash = "sha256:0ec6bafd80d8ad2195c4f03aacba3a8265e57bc4cff261e802bf39970ed02a15"},
    {file = "hyperframe-6.0.1.tar.gz", hash = "sha256:ae510046231dc8e9ecb1a6586f63d2347bf4c8905914aa84ba585ae85f28a914"},
]
idna = [
    {file = "idna-3.4-py3-none-any.whl", hash = "sha256:90b77e79eaa3eba6de819a0c442c0b4ceefc341a7a2ab77d7562bf49f425c5c2"},
    {file = "idna-3.4.tar.gz", hash = "sha256:814f528e8dead7d329833b91c5faa87d60bf71824cd12a7530b5526063d02cb4"},
]
joblib = [
    {file = "joblib-1.2.0-py3-none-any.whl", hash = "sha256:091138ed78f800342968c523bdde947e7a305b8594b910a0fea2ab83c3c6d385"},
    {file = "joblib-1.2.0.tar.gz", hash = "sha256:e1cee4a79e4af22881164f218d4311f60074197fb707e082e803b61f6d137018"},
]
loguru = [
    {file = "loguru-0.5.3-py3-none-any.whl", hash = "sha256:f8087ac396b5ee5f67c963b495d615ebbceac2796379599820e324419d53667c"},
    {file = "loguru-0.5.3.tar.gz", hash = "sha256:b28e72ac7a98be3d28ad28570299a393dfcd32e5e3f6a353dec94675767b6319"},
]
nltk = [
    {file = "nltk-3.7-py3-none-any.whl", hash = "sha256:ba3de02490308b248f9b94c8bc1ac0683e9aa2ec49ee78536d8667afb5e3eec8"},
    {file = "nltk-3.7.zip", hash = "sha256:d6507d6460cec76d70afea4242a226a7542f85c669177b9c7f562b7cf1b05502"},
]
numpy = [
    {file = "numpy-1.23.3-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:c9f707b5bb73bf277d812ded9896f9512a43edff72712f31667d0a8c2f8e71ee"},
    {file = "numpy-1.23.3-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:ffcf105ecdd9396e05a8e58e81faaaf34d3f9875f137c7372450baa5d77c9a54"},
    {file = "numpy-1.23.3-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:0ea3f98a0ffce3f8f57675eb9119f3f4edb81888b6874bc1953f91e0b1d4f440"},
    {file = "numpy-1.23.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:004f0efcb2fe1c0bd6ae1fcfc69cc8b6bf2407e0f18be308612007a0762b4089"},
    {file = "numpy-1.23.3-cp310-cp310-win32.whl", hash = "sha256:98dcbc02e39b1658dc4b4508442a560fe3ca5ca0d989f0df062534e5ca3a5c1a"},
    {file = "numpy-1.23.3-cp310-cp310-win_amd64.whl", hash = "sha256:39a664e3d26ea854211867d20ebcc8023257c1800ae89773cbba9f9e97bae036"},
    {file = "numpy-1.23.3-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:1f27b5322ac4067e67c8f9378b41c746d8feac8bdd0e0ffede5324667b8a075c"},
    {file = "numpy-1.23.3-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:2ad3ec9a748a8943e6eb4358201f7e1c12ede35f510b1a2221b70af4bb64295c"},
    {file = "numpy-1.23.3-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:bdc9febce3e68b697d931941b263c59e0c74e8f18861f4064c1f712562903411"},
    {file = "numpy-1.23.3-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:301c00cf5e60e08e04d842fc47df641d4a181e651c7135c50dc2762ffe293dbd"},
    {file = "numpy-1.23.3-cp311-cp311-win32.whl", hash = "sha256:7cd1328e5bdf0dee621912f5833648e2daca72e3839ec1d6695e91089625f0b4"},
    {file = "numpy-1.23.3-cp311-cp311-win_amd64.whl", hash = "sha256:8355fc10fd33a5a70981a5b8a0de51d10af3688d7a9e4a34fcc8fa0d7467bb7f"},
    {file = "numpy-1.23.3-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:bc6e8da415f359b578b00bcfb1d08411c96e9a97f9e6c7adada554a0812a6cc6"},
    {file = "numpy-1.23.3-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:22d43376ee0acd547f3149b9ec12eec2f0ca4a6ab2f61753c5b29bb3e795ac4d"},
    {file = "numpy-1.23.3-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:a64403f634e5ffdcd85e0b12c08f04b3080d3e840aef118721021f9b48fc1460"},
    {file = "numpy-1.23.3-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:efd9d3abe5774404becdb0748178b48a218f1d8c44e0375475732211ea47c67e"},
    {file = "numpy-1.23.3-cp38-cp38-win32.whl", hash = "sha256:f8c02ec3c4c4fcb718fdf89a6c6f709b14949408e8cf2a2be5bfa9c49548fd85"},
    {file = "numpy-1.23.3-cp38-cp38-win_amd64.whl", hash = "sha256:e868b0389c5ccfc092031a861d4e158ea164d8b7fdbb10e3b5689b4fc6498df6"},
    {file = "numpy-1.23.3-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:09f6b7bdffe57fc61d869a22f506049825d707b288039d30f26a0d0d8ea05164"},
    {file = "numpy-1.23.3-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:8c79d7cf86d049d0c5089231a5bcd31edb03555bd93d81a16870aa98c6cfb79d"},
    {file = "numpy-1.23.3-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:e5d5420053bbb3dd64c30e58f9363d7a9c27444c3648e61460c1237f9ec3fa14"},
    {file = "numpy-1.23.3-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:d5422d6a1ea9b15577a9432e26608c73a78faf0b9039437b075cf322c92e98e7"},
    {file = "numpy-1.23.3-cp39-cp39-win32.whl", hash = "sha256:c1ba66c48b19cc9c2975c0d354f24058888cdc674bebadceb3cdc9ec403fb5d1"},
    {file = "numpy-1.23.3-cp39-cp39-win_amd64.whl", hash = "sha256:78a63d2df1d947bd9d1b11d35564c2f9e4b57898aae4626638056ec1a231c40c"},
    {file = "numpy-1.23.3-pp38-pypy38_pp73-macosx_10_9_x86_64.whl", hash = "sha256:17c0e467ade9bda685d5ac7f5fa729d8d3e76b23195471adae2d6a6941bd2c18"},
    {file = "numpy-1.23.3-pp38-pypy38_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:91b8d6768a75247026e951dce3b2aac79dc7e78622fc148329135ba189813584"},
    {file = "numpy-1.23.3-pp38-pypy38_pp73-win_amd64.whl", hash = "sha256:94c15ca4e52671a59219146ff584488907b1f9b3fc232622b47e2cf832e94fb8"},
    {file = "numpy-1.23.3.tar.gz", hash = "sha256:51bf49c0cd1d52be0a240aa66f3458afc4b95d8993d2d04f0d91fa60c10af6cd"},
]
packaging = [
    {file = "packaging-21.3-py3-none-any.whl", hash = "sha256:ef103e05f519cdc783ae24ea4e2e0f508a9c99b2d4969652eed6a2e1ea5bd522"},
    {file = "packaging-21.3.tar.gz", hash = "sha256:dd47c42927d89ab911e606518907cc2d3a1f38bbd026385970643f9c5b8ecfeb"},
]
pandas = [
    {file = "pandas-1.5.0-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:0d8d7433d19bfa33f11c92ad9997f15a902bda4f5ad3a4814a21d2e910894484"},
    {file = "pandas-1.5.0-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:5cc47f2ebaa20ef96ae72ee082f9e101b3dfbf74f0e62c7a12c0b075a683f03c"},
    {file = "pandas-1.5.0-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:8e8e5edf97d8793f51d258c07c629bd49d271d536ce15d66ac00ceda5c150eb3"},
    {file = "pandas-1.5.0-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:41aec9f87455306496d4486df07c1b98c15569c714be2dd552a6124cd9fda88f"},
    {file = "pandas-1.5.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:c76f1d104844c5360c21d2ef0e1a8b2ccf8b8ebb40788475e255b9462e32b2be"},
    {file = "pandas-1.5.0-cp310-cp310-win_amd64.whl", hash = "sha256:1642fc6138b4e45d57a12c1b464a01a6d868c0148996af23f72dde8d12486bbc"},
    {file = "pandas-1.5.0-cp311-cp311-macosx_10_9_universal2.whl", hash = "sha256:171cef540bfcec52257077816a4dbbac152acdb8236ba11d3196ae02bf0959d8"},
    {file = "pandas-1.5.0-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:a68a9b9754efff364b0c5ee5b0f18e15ca640c01afe605d12ba8b239ca304d6b"},
    {file = "pandas-1.5.0-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:86d87279ebc5bc20848b4ceb619073490037323f80f515e0ec891c80abad958a"},
    {file = "pandas-1.5.0-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:207d63ac851e60ec57458814613ef4b3b6a5e9f0b33c57623ba2bf8126c311f8"},
    {file = "pandas-1.5.0-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:e252a9e49b233ff96e2815c67c29702ac3a062098d80a170c506dff3470fd060"},
    {file = "pandas-1.5.0-cp311-cp311-win_amd64.whl", hash = "sha256:de34636e2dc04e8ac2136a8d3c2051fd56ebe9fd6cd185581259330649e73ca9"},
    {file = "pandas-1.5.0-cp38-cp38-macosx_10_9_universal2.whl", hash = "sha256:1d34b1f43d9e3f4aea056ba251f6e9b143055ebe101ed04c847b41bb0bb4a989"},
    {file = "pandas-1.5.0-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:1b82ccc7b093e0a93f8dffd97a542646a3e026817140e2c01266aaef5fdde11b"},
    {file = "pandas-1.5.0-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:4e30a31039574d96f3d683df34ccb50bb435426ad65793e42a613786901f6761"},
    {file = "pandas-1.5.0-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:62e61003411382e20d7c2aec1ee8d7c86c8b9cf46290993dd8a0a3be44daeb38"},
    {file = "pandas-1.5.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:fc987f7717e53d372f586323fff441263204128a1ead053c1b98d7288f836ac9"},
    {file = "pandas-1.5.0-cp38-cp38-win32.whl", hash = "sha256:e178ce2d7e3b934cf8d01dc2d48d04d67cb0abfaffdcc8aa6271fd5a436f39c8"},
    {file = "pandas-1.5.0-cp38-cp38-win_amd64.whl", hash = "sha256:33a9d9e21ab2d91e2ab6e83598419ea6a664efd4c639606b299aae8097c1c94f"},
    {file = "pandas-1.5.0-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:73844e247a7b7dac2daa9df7339ecf1fcf1dfb8cbfd11e3ffe9819ae6c31c515"},
    {file = "pandas-1.5.0-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:e9c5049333c5bebf993033f4bf807d163e30e8fada06e1da7fa9db86e2392009"},
    {file = "pandas-1.5.0-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:85a516a7f6723ca1528f03f7851fa8d0360d1d6121cf15128b290cf79b8a7f6a"},
    {file = "pandas-1.5.0-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:947ed9f896ee61adbe61829a7ae1ade493c5a28c66366ec1de85c0642009faac"},
    {file = "pandas-1.5.0-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:c7f38d91f21937fe2bec9449570d7bf36ad7136227ef43b321194ec249e2149d"},
    {file = "pandas-1.5.0-cp39-cp39-win32.whl", hash = "sha256:2504c032f221ef9e4a289f5e46a42b76f5e087ecb67d62e342ccbba95a32a488"},
    {file = "pandas-1.5.0-cp39-cp39-win_amd64.whl", hash = "sha256:8a4fc04838615bf0a8d3a03ed68197f358054f0df61f390bcc64fbe39e3d71ec"},
    {file = "pandas-1.5.0.tar.gz", hash = "sha256:3ee61b881d2f64dd90c356eb4a4a4de75376586cd3c9341c6c0fcaae18d52977"},
]
Pillow = [
    {file = "Pillow-9.2.0-cp310-cp310-macosx_10_10_x86_64.whl", hash = "sha256:a9c9bc489f8ab30906d7a85afac4b4944a572a7432e00698a7239f44a44e6efb"},
    {file = "Pillow-9.2.0-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:510cef4a3f401c246cfd8227b300828715dd055463cdca6176c2e4036df8bd4f"},
    {file = "Pillow-9.2.0-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:7888310f6214f19ab2b6df90f3f06afa3df7ef7355fc025e78a3044737fab1f5"},
    {file = "Pillow-9.2.0-cp310-cp310-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:831e648102c82f152e14c1a0938689dbb22480c548c8d4b8b248b3e50967b88c"},
    {file = "Pillow-9.2.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:1cc1d2451e8a3b4bfdb9caf745b58e6c7a77d2e469159b0d527a4554d73694d1"},
    {file = "Pillow-9.2.0-cp310-cp310-manylinux_2_28_aarch64.whl", hash = "sha256:136659638f61a251e8ed3b331fc6ccd124590eeff539de57c5f80ef3a9594e58"},
    {file = "Pillow-9.2.0-cp310-cp310-manylinux_2_28_x86_64.whl", hash = "sha256:6e8c66f70fb539301e064f6478d7453e820d8a2c631da948a23384865cd95544"},
    {file = "Pillow-9.2.0-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:37ff6b522a26d0538b753f0b4e8e164fdada12db6c6f00f62145d732d8a3152e"},
    {file = "Pillow-9.2.0-cp310-cp310-win32.whl", hash = "sha256:c79698d4cd9318d9481d89a77e2d3fcaeff5486be641e60a4b49f3d2ecca4e28"},
    {file = "Pillow-9.2.0-cp310-cp310-win_amd64.whl", hash = "sha256:254164c57bab4b459f14c64e93df11eff5ded575192c294a0c49270f22c5d93d"},
    {file = "Pillow-9.2.0-cp311-cp311-macosx_10_10_x86_64.whl", hash = "sha256:adabc0bce035467fb537ef3e5e74f2847c8af217ee0be0455d4fec8adc0462fc"},
    {file = "Pillow-9.2.0-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:336b9036127eab855beec9662ac3ea13a4544a523ae273cbf108b228ecac8437"},
    {file = "Pillow-9.2.0-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:50dff9cc21826d2977ef2d2a205504034e3a4563ca6f5db739b0d1026658e004"},
    {file = "Pillow-9.2.0-cp311-cp311-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:cb6259196a589123d755380b65127ddc60f4c64b21fc3bb46ce3a6ea663659b0"},
    {file = "Pillow-9.2.0-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:7b0554af24df2bf96618dac71ddada02420f946be943b181108cac55a7a2dcd4"},
    {file = "Pillow-9.2.0-cp311-cp311-manylinux_2_28_aarch64.whl", hash = "sha256:15928f824870535c85dbf949c09d6ae7d3d6ac2d6efec80f3227f73eefba741c"},
    {file = "Pillow-9.2.0-cp311-cp311-manylinux_2_28_x86_64.whl", hash = "sha256:bdd0de2d64688ecae88dd8935012c4a72681e5df632af903a1dca8c5e7aa871a"},
    {file = "Pillow-9.2.0-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:d5b87da55a08acb586bad5c3aa3b86505f559b84f39035b233d5bf844b0834b1"},
    {file = "Pillow-9.2.0-cp311-cp311-win32.whl", hash = "sha256:b6d5e92df2b77665e07ddb2e4dbd6d644b78e4c0d2e9272a852627cdba0d75cf"},
    {file = "Pillow-9.2.0-cp311-cp311-win_amd64.whl", hash = "sha256:6bf088c1ce160f50ea40764f825ec9b72ed9da25346216b91361eef8ad1b8f8c"},
    {file = "Pillow-9.2.0-cp37-cp37m-macosx_10_10_x86_64.whl", hash = "sha256:2c58b24e3a63efd22554c676d81b0e57f80e0a7d3a5874a7e14ce90ec40d3069"},
    {file = "Pillow-9.2.0-cp37-cp37m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:eef7592281f7c174d3d6cbfbb7ee5984a671fcd77e3fc78e973d492e9bf0eb3f"},
    {file = "Pillow-9.2.0-cp37-cp37m-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:dcd7b9c7139dc8258d164b55696ecd16c04607f1cc33ba7af86613881ffe4ac8"},
    {file = "Pillow-9.2.0-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:a138441e95562b3c078746a22f8fca8ff1c22c014f856278bdbdd89ca36cff1b"},
    {file = "Pillow-9.2.0-cp37-cp37m-manylinux_2_28_aarch64.whl", hash = "sha256:93689632949aff41199090eff5474f3990b6823404e45d66a5d44304e9cdc467"},
    {file = "Pillow-9.2.0-cp37-cp37m-manylinux_2_28_x86_64.whl", hash = "sha256:f3fac744f9b540148fa7715a435d2283b71f68bfb6d4aae24482a890aed18b59"},
    {file = "Pillow-9.2.0-cp37-cp37m-win32.whl", hash = "sha256:fa768eff5f9f958270b081bb33581b4b569faabf8774726b283edb06617101dc"},
    {file = "Pillow-9.2.0-cp37-cp37m-win_amd64.whl", hash = "sha256:69bd1a15d7ba3694631e00df8de65a8cb031911ca11f44929c97fe05eb9b6c1d"},
    {file = "Pillow-9.2.0-cp38-cp38-macosx_10_10_x86_64.whl", hash = "sha256:030e3460861488e249731c3e7ab59b07c7853838ff3b8e16aac9561bb345da14"},
    {file = "Pillow-9.2.0-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:74a04183e6e64930b667d321524e3c5361094bb4af9083db5c301db64cd341f3"},
    {file = "Pillow-9.2.0-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:2d33a11f601213dcd5718109c09a52c2a1c893e7461f0be2d6febc2879ec2402"},
    {file = "Pillow-9.2.0-cp38-cp38-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:1fd6f5e3c0e4697fa7eb45b6e93996299f3feee73a3175fa451f49a74d092b9f"},
    {file = "Pillow-9.2.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:a647c0d4478b995c5e54615a2e5360ccedd2f85e70ab57fbe817ca613d5e63b8"},
    {file = "Pillow-9.2.0-cp38-cp38-manylinux_2_28_aarch64.whl", hash = "sha256:4134d3f1ba5f15027ff5c04296f13328fecd46921424084516bdb1b2548e66ff"},
    {file = "Pillow-9.2.0-cp38-cp38-manylinux_2_28_x86_64.whl", hash = "sha256:bc431b065722a5ad1dfb4df354fb9333b7a582a5ee39a90e6ffff688d72f27a1"},
    {file = "Pillow-9.2.0-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:1536ad017a9f789430fb6b8be8bf99d2f214c76502becc196c6f2d9a75b01b76"},
    {file = "Pillow-9.2.0-cp38-cp38-win32.whl", hash = "sha256:2ad0d4df0f5ef2247e27fc790d5c9b5a0af8ade9ba340db4a73bb1a4a3e5fb4f"},
    {file = "Pillow-9.2.0-cp38-cp38-win_amd64.whl", hash = "sha256:ec52c351b35ca269cb1f8069d610fc45c5bd38c3e91f9ab4cbbf0aebc136d9c8"},
    {file = "Pillow-9.2.0-cp39-cp39-macosx_10_10_x86_64.whl", hash = "sha256:0ed2c4ef2451de908c90436d6e8092e13a43992f1860275b4d8082667fbb2ffc"},
    {file = "Pillow-9.2.0-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:4ad2f835e0ad81d1689f1b7e3fbac7b01bb8777d5a985c8962bedee0cc6d43da"},
    {file = "Pillow-9.2.0-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:ea98f633d45f7e815db648fd7ff0f19e328302ac36427343e4432c84432e7ff4"},
    {file = "Pillow-9.2.0-cp39-cp39-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:7761afe0126d046974a01e030ae7529ed0ca6a196de3ec6937c11df0df1bc91c"},
    {file = "Pillow-9.2.0-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:9a54614049a18a2d6fe156e68e188da02a046a4a93cf24f373bffd977e943421"},
    {file = "Pillow-9.2.0-cp39-cp39-manylinux_2_28_aarch64.whl", hash = "sha256:5aed7dde98403cd91d86a1115c78d8145c83078e864c1de1064f52e6feb61b20"},
    {file = "Pillow-9.2.0-cp39-cp39-manylinux_2_28_x86_64.whl", hash = "sha256:13b725463f32df1bfeacbf3dd197fb358ae8ebcd8c5548faa75126ea425ccb60"},
    {file = "Pillow-9.2.0-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:808add66ea764ed97d44dda1ac4f2cfec4c1867d9efb16a33d158be79f32b8a4"},
    {file = "Pillow-9.2.0-cp39-cp39-win32.whl", hash = "sha256:337a74fd2f291c607d220c793a8135273c4c2ab001b03e601c36766005f36885"},
    {file = "Pillow-9.2.0-cp39-cp39-win_amd64.whl", hash = "sha256:fac2d65901fb0fdf20363fbd345c01958a742f2dc62a8dd4495af66e3ff502a4"},
    {file = "Pillow-9.2.0-pp37-pypy37_pp73-macosx_10_10_x86_64.whl", hash = "sha256:ad2277b185ebce47a63f4dc6302e30f05762b688f8dc3de55dbae4651872cdf3"},
    {file = "Pillow-9.2.0-pp37-pypy37_pp73-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:7c7b502bc34f6e32ba022b4a209638f9e097d7a9098104ae420eb8186217ebbb"},
    {file = "Pillow-9.2.0-pp37-pypy37_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:3d1f14f5f691f55e1b47f824ca4fdcb4b19b4323fe43cc7bb105988cad7496be"},
    {file = "Pillow-9.2.0-pp37-pypy37_pp73-manylinux_2_28_x86_64.whl", hash = "sha256:dfe4c1fedfde4e2fbc009d5ad420647f7730d719786388b7de0999bf32c0d9fd"},
    {file = "Pillow-9.2.0-pp38-pypy38_pp73-macosx_10_10_x86_64.whl", hash = "sha256:f07f1f00e22b231dd3d9b9208692042e29792d6bd4f6639415d2f23158a80013"},
    {file = "Pillow-9.2.0-pp38-pypy38_pp73-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:1802f34298f5ba11d55e5bb09c31997dc0c6aed919658dfdf0198a2fe75d5490"},
    {file = "Pillow-9.2.0-pp38-pypy38_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:17d4cafe22f050b46d983b71c707162d63d796a1235cdf8b9d7a112e97b15bac"},
    {file = "Pillow-9.2.0-pp38-pypy38_pp73-manylinux_2_28_x86_64.whl", hash = "sha256:96b5e6874431df16aee0c1ba237574cb6dff1dcb173798faa6a9d8b399a05d0e"},
    {file = "Pillow-9.2.0-pp38-pypy38_pp73-win_amd64.whl", hash = "sha256:0030fdbd926fb85844b8b92e2f9449ba89607231d3dd597a21ae72dc7fe26927"},
    {file = "Pillow-9.2.0.tar.gz", hash = "sha256:75e636fd3e0fb872693f23ccb8a5ff2cd578801251f3a4f6854c6a5d437d3c04"},
]
protobuf = [
    {file = "protobuf-4.21.6-cp310-abi3-win32.whl", hash = "sha256:49f88d56a9180dbb7f6199c920f5bb5c1dd0172f672983bb281298d57c2ac8eb"},
    {file = "protobuf-4.21.6-cp310-abi3-win_amd64.whl", hash = "sha256:7a6cc8842257265bdfd6b74d088b829e44bcac3cca234c5fdd6052730017b9ea"},
    {file = "protobuf-4.21.6-cp37-abi3-macosx_10_9_universal2.whl", hash = "sha256:ba596b9ffb85c909fcfe1b1a23136224ed678af3faf9912d3fa483d5f9813c4e"},
    {file = "protobuf-4.21.6-cp37-abi3-manylinux2014_aarch64.whl", hash = "sha256:4143513c766db85b9d7c18dbf8339673c8a290131b2a0fe73855ab20770f72b0"},
    {file = "protobuf-4.21.6-cp37-abi3-manylinux2014_x86_64.whl", hash = "sha256:b6cea204865595a92a7b240e4b65bcaaca3ad5d2ce25d9db3756eba06041138e"},
    {file = "protobuf-4.21.6-cp37-cp37m-win32.whl", hash = "sha256:9666da97129138585b26afcb63ad4887f602e169cafe754a8258541c553b8b5d"},
    {file = "protobuf-4.21.6-cp37-cp37m-win_amd64.whl", hash = "sha256:308173d3e5a3528787bb8c93abea81d5a950bdce62840d9760effc84127fb39c"},
    {file = "protobuf-4.21.6-cp38-cp38-win32.whl", hash = "sha256:aa29113ec901281f29d9d27b01193407a98aa9658b8a777b0325e6d97149f5ce"},
    {file = "protobuf-4.21.6-cp38-cp38-win_amd64.whl", hash = "sha256:8f9e60f7d44592c66e7b332b6a7b4b6e8d8b889393c79dbc3a91f815118f8eac"},
    {file = "protobuf-4.21.6-cp39-cp39-win32.whl", hash = "sha256:80e6540381080715fddac12690ee42d087d0d17395f8d0078dfd6f1181e7be4c"},
    {file = "protobuf-4.21.6-cp39-cp39-win_amd64.whl", hash = "sha256:77b355c8604fe285536155286b28b0c4cbc57cf81b08d8357bf34829ea982860"},
    {file = "protobuf-4.21.6-py2.py3-none-any.whl", hash = "sha256:07a0bb9cc6114f16a39c866dc28b6e3d96fa4ffb9cc1033057412547e6e75cb9"},
    {file = "protobuf-4.21.6-py3-none-any.whl", hash = "sha256:c7c864148a237f058c739ae7a05a2b403c0dfa4ce7d1f3e5213f352ad52d57c6"},
    {file = "protobuf-4.21.6.tar.gz", hash = "sha256:6b1040a5661cd5f6e610cbca9cfaa2a17d60e2bb545309bc1b278bb05be44bdd"},
]
psutil = [
    {file = "psutil-5.9.2-cp27-cp27m-manylinux2010_i686.whl", hash = "sha256:8f024fbb26c8daf5d70287bb3edfafa22283c255287cf523c5d81721e8e5d82c"},
    {file = "psutil-5.9.2-cp27-cp27m-manylinux2010_x86_64.whl", hash = "sha256:b2f248ffc346f4f4f0d747ee1947963613216b06688be0be2e393986fe20dbbb"},
    {file = "psutil-5.9.2-cp27-cp27m-win32.whl", hash = "sha256:b1928b9bf478d31fdffdb57101d18f9b70ed4e9b0e41af751851813547b2a9ab"},
    {file = "psutil-5.9.2-cp27-cp27m-win_amd64.whl", hash = "sha256:404f4816c16a2fcc4eaa36d7eb49a66df2d083e829d3e39ee8759a411dbc9ecf"},
    {file = "psutil-5.9.2-cp27-cp27mu-manylinux2010_i686.whl", hash = "sha256:94e621c6a4ddb2573d4d30cba074f6d1aa0186645917df42c811c473dd22b339"},
    {file = "psutil-5.9.2-cp27-cp27mu-manylinux2010_x86_64.whl", hash = "sha256:256098b4f6ffea6441eb54ab3eb64db9ecef18f6a80d7ba91549195d55420f84"},
    {file = "psutil-5.9.2-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:614337922702e9be37a39954d67fdb9e855981624d8011a9927b8f2d3c9625d9"},
    {file = "psutil-5.9.2-cp310-cp310-manylinux_2_12_i686.manylinux2010_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:39ec06dc6c934fb53df10c1672e299145ce609ff0611b569e75a88f313634969"},
    {file = "psutil-5.9.2-cp310-cp310-manylinux_2_12_x86_64.manylinux2010_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:e3ac2c0375ef498e74b9b4ec56df3c88be43fe56cac465627572dbfb21c4be34"},
    {file = "psutil-5.9.2-cp310-cp310-win32.whl", hash = "sha256:e4c4a7636ffc47b7141864f1c5e7d649f42c54e49da2dd3cceb1c5f5d29bfc85"},
    {file = "psutil-5.9.2-cp310-cp310-win_amd64.whl", hash = "sha256:f4cb67215c10d4657e320037109939b1c1d2fd70ca3d76301992f89fe2edb1f1"},
    {file = "psutil-5.9.2-cp36-cp36m-macosx_10_9_x86_64.whl", hash = "sha256:dc9bda7d5ced744622f157cc8d8bdd51735dafcecff807e928ff26bdb0ff097d"},
    {file = "psutil-5.9.2-cp36-cp36m-manylinux_2_12_i686.manylinux2010_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:d75291912b945a7351d45df682f9644540d564d62115d4a20d45fa17dc2d48f8"},
    {file = "psutil-5.9.2-cp36-cp36m-manylinux_2_12_x86_64.manylinux2010_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:b4018d5f9b6651f9896c7a7c2c9f4652e4eea53f10751c4e7d08a9093ab587ec"},
    {file = "psutil-5.9.2-cp36-cp36m-win32.whl", hash = "sha256:f40ba362fefc11d6bea4403f070078d60053ed422255bd838cd86a40674364c9"},
    {file = "psutil-5.9.2-cp36-cp36m-win_amd64.whl", hash = "sha256:9770c1d25aee91417eba7869139d629d6328a9422ce1cdd112bd56377ca98444"},
    {file = "psutil-5.9.2-cp37-cp37m-macosx_10_9_x86_64.whl", hash = "sha256:42638876b7f5ef43cef8dcf640d3401b27a51ee3fa137cb2aa2e72e188414c32"},
    {file = "psutil-5.9.2-cp37-cp37m-manylinux_2_12_i686.manylinux2010_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:91aa0dac0c64688667b4285fa29354acfb3e834e1fd98b535b9986c883c2ce1d"},
    {file = "psutil-5.9.2-cp37-cp37m-manylinux_2_12_x86_64.manylinux2010_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:4fb54941aac044a61db9d8eb56fc5bee207db3bc58645d657249030e15ba3727"},
    {file = "psutil-5.9.2-cp37-cp37m-win32.whl", hash = "sha256:7cbb795dcd8ed8fd238bc9e9f64ab188f3f4096d2e811b5a82da53d164b84c3f"},
    {file = "psutil-5.9.2-cp37-cp37m-win_amd64.whl", hash = "sha256:5d39e3a2d5c40efa977c9a8dd4f679763c43c6c255b1340a56489955dbca767c"},
    {file = "psutil-5.9.2-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:fd331866628d18223a4265371fd255774affd86244fc307ef66eaf00de0633d5"},
    {file = "psutil-5.9.2-cp38-cp38-manylinux_2_12_i686.manylinux2010_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:b315febaebae813326296872fdb4be92ad3ce10d1d742a6b0c49fb619481ed0b"},
    {file = "psutil-5.9.2-cp38-cp38-manylinux_2_12_x86_64.manylinux2010_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:f7929a516125f62399d6e8e026129c8835f6c5a3aab88c3fff1a05ee8feb840d"},
    {file = "psutil-5.9.2-cp38-cp38-win32.whl", hash = "sha256:561dec454853846d1dd0247b44c2e66a0a0c490f937086930ec4b8f83bf44f06"},
    {file = "psutil-5.9.2-cp38-cp38-win_amd64.whl", hash = "sha256:67b33f27fc0427483b61563a16c90d9f3b547eeb7af0ef1b9fe024cdc9b3a6ea"},
    {file = "psutil-5.9.2-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:b3591616fa07b15050b2f87e1cdefd06a554382e72866fcc0ab2be9d116486c8"},
    {file = "psutil-5.9.2-cp39-cp39-manylinux_2_12_i686.manylinux2010_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:14b29f581b5edab1f133563272a6011925401804d52d603c5c606936b49c8b97"},
    {file = "psutil-5.9.2-cp39-cp39-manylinux_2_12_x86_64.manylinux2010_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:4642fd93785a29353d6917a23e2ac6177308ef5e8be5cc17008d885cb9f70f12"},
    {file = "psutil-5.9.2-cp39-cp39-win32.whl", hash = "sha256:ed29ea0b9a372c5188cdb2ad39f937900a10fb5478dc077283bf86eeac678ef1"},
    {file = "psutil-5.9.2-cp39-cp39-win_amd64.whl", hash = "sha256:68b35cbff92d1f7103d8f1db77c977e72f49fcefae3d3d2b91c76b0e7aef48b8"},
    {file = "psutil-5.9.2.tar.gz", hash = "sha256:feb861a10b6c3bb00701063b37e4afc754f8217f0f09c42280586bd6ac712b5c"},
]
pydantic = [
    {file = "pydantic-1.10.2-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:bb6ad4489af1bac6955d38ebcb95079a836af31e4c4f74aba1ca05bb9f6027bd"},
    {file = "pydantic-1.10.2-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:a1f5a63a6dfe19d719b1b6e6106561869d2efaca6167f84f5ab9347887d78b98"},
    {file = "pydantic-1.10.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:352aedb1d71b8b0736c6d56ad2bd34c6982720644b0624462059ab29bd6e5912"},
    {file = "pydantic-1.10.2-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:19b3b9ccf97af2b7519c42032441a891a5e05c68368f40865a90eb88833c2559"},
    {file = "pydantic-1.10.2-cp310-cp310-musllinux_1_1_i686.whl", hash = "sha256:e9069e1b01525a96e6ff49e25876d90d5a563bc31c658289a8772ae186552236"},
    {file = "pydantic-1.10.2-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:355639d9afc76bcb9b0c3000ddcd08472ae75318a6eb67a15866b87e2efa168c"},
    {file = "pydantic-1.10.2-cp310-cp310-win_amd64.whl", hash = "sha256:ae544c47bec47a86bc7d350f965d8b15540e27e5aa4f55170ac6a75e5f73b644"},
    {file = "pydantic-1.10.2-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:a4c805731c33a8db4b6ace45ce440c4ef5336e712508b4d9e1aafa617dc9907f"},
    {file = "pydantic-1.10.2-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:d49f3db871575e0426b12e2f32fdb25e579dea16486a26e5a0474af87cb1ab0a"},
    {file = "pydantic-1.10.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:37c90345ec7dd2f1bcef82ce49b6235b40f282b94d3eec47e801baf864d15525"},
    {file = "pydantic-1.10.2-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:7b5ba54d026c2bd2cb769d3468885f23f43710f651688e91f5fb1edcf0ee9283"},
    {file = "pydantic-1.10.2-cp311-cp311-musllinux_1_1_i686.whl", hash = "sha256:05e00dbebbe810b33c7a7362f231893183bcc4251f3f2ff991c31d5c08240c42"},
    {file = "pydantic-1.10.2-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:2d0567e60eb01bccda3a4df01df677adf6b437958d35c12a3ac3e0f078b0ee52"},
    {file = "pydantic-1.10.2-cp311-cp311-win_amd64.whl", hash = "sha256:c6f981882aea41e021f72779ce2a4e87267458cc4d39ea990729e21ef18f0f8c"},
    {file = "pydantic-1.10.2-cp37-cp37m-macosx_10_9_x86_64.whl", hash = "sha256:c4aac8e7103bf598373208f6299fa9a5cfd1fc571f2d40bf1dd1955a63d6eeb5"},
    {file = "pydantic-1.10.2-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:81a7b66c3f499108b448f3f004801fcd7d7165fb4200acb03f1c2402da73ce4c"},
    {file = "pydantic-1.10.2-cp37-cp37m-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:bedf309630209e78582ffacda64a21f96f3ed2e51fbf3962d4d488e503420254"},
    {file = "pydantic-1.10.2-cp37-cp37m-musllinux_1_1_i686.whl", hash = "sha256:9300fcbebf85f6339a02c6994b2eb3ff1b9c8c14f502058b5bf349d42447dcf5"},
    {file = "pydantic-1.10.2-cp37-cp37m-musllinux_1_1_x86_64.whl", hash = "sha256:216f3bcbf19c726b1cc22b099dd409aa371f55c08800bcea4c44c8f74b73478d"},
    {file = "pydantic-1.10.2-cp37-cp37m-win_amd64.whl", hash = "sha256:dd3f9a40c16daf323cf913593083698caee97df2804aa36c4b3175d5ac1b92a2"},
    {file = "pydantic-1.10.2-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:b97890e56a694486f772d36efd2ba31612739bc6f3caeee50e9e7e3ebd2fdd13"},
    {file = "pydantic-1.10.2-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:9cabf4a7f05a776e7793e72793cd92cc865ea0e83a819f9ae4ecccb1b8aa6116"},
    {file = "pydantic-1.10.2-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:06094d18dd5e6f2bbf93efa54991c3240964bb663b87729ac340eb5014310624"},
    {file = "pydantic-1.10.2-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:cc78cc83110d2f275ec1970e7a831f4e371ee92405332ebfe9860a715f8336e1"},
    {file = "pydantic-1.10.2-cp38-cp38-musllinux_1_1_i686.whl", hash = "sha256:1ee433e274268a4b0c8fde7ad9d58ecba12b069a033ecc4645bb6303c062d2e9"},
    {file = "pydantic-1.10.2-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:7c2abc4393dea97a4ccbb4ec7d8658d4e22c4765b7b9b9445588f16c71ad9965"},
    {file = "pydantic-1.10.2-cp38-cp38-win_amd64.whl", hash = "sha256:0b959f4d8211fc964772b595ebb25f7652da3f22322c007b6fed26846a40685e"},
    {file = "pydantic-1.10.2-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:c33602f93bfb67779f9c507e4d69451664524389546bacfe1bee13cae6dc7488"},
    {file = "pydantic-1.10.2-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:5760e164b807a48a8f25f8aa1a6d857e6ce62e7ec83ea5d5c5a802eac81bad41"},
    {file = "pydantic-1.10.2-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:6eb843dcc411b6a2237a694f5e1d649fc66c6064d02b204a7e9d194dff81eb4b"},
    {file = "pydantic-1.10.2-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:4b8795290deaae348c4eba0cebb196e1c6b98bdbe7f50b2d0d9a4a99716342fe"},
    {file = "pydantic-1.10.2-cp39-cp39-musllinux_1_1_i686.whl", hash = "sha256:e0bedafe4bc165ad0a56ac0bd7695df25c50f76961da29c050712596cf092d6d"},
    {file = "pydantic-1.10.2-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:2e05aed07fa02231dbf03d0adb1be1d79cabb09025dd45aa094aa8b4e7b9dcda"},
    {file = "pydantic-1.10.2-cp39-cp39-win_amd64.whl", hash = "sha256:c1ba1afb396148bbc70e9eaa8c06c1716fdddabaf86e7027c5988bae2a829ab6"},
    {file = "pydantic-1.10.2-py3-none-any.whl", hash = "sha256:1b6ee725bd6e83ec78b1aa32c5b1fa67a3a65badddde3976bca5fe4568f27709"},
    {file = "pydantic-1.10.2.tar.gz", hash = "sha256:91b8e218852ef6007c2b98cd861601c6a09f1aa32bbbb74fab5b1c33d4a1e410"},
]
pyparsing = [
    {file = "pyparsing-3.0.9-py3-none-any.whl", hash = "sha256:5026bae9a10eeaefb61dab2f09052b9f4307d44aee4eda64b309723d8d206bbc"},
    {file = "pyparsing-3.0.9.tar.gz", hash = "sha256:2b020ecf7d21b687f219b71ecad3631f644a47f01403fa1d1036b0c6416d70fb"},
]
python-dateutil = [
    {file = "python-dateutil-2.8.2.tar.gz", hash = "sha256:0123cacc1627ae19ddf3c27a5de5bd67ee4586fbdd6440d9748f8abb483d3e86"},
    {file = "python_dateutil-2.8.2-py2.py3-none-any.whl", hash = "sha256:961d03dc3453ebbc59dbdea9e4e11c5651520a876d0f4db161e8674aae935da9"},
]
pytz = [
    {file = "pytz-2022.2.1-py2.py3-none-any.whl", hash = "sha256:220f481bdafa09c3955dfbdddb7b57780e9a94f5127e35456a48589b9e0c0197"},
    {file = "pytz-2022.2.1.tar.gz", hash = "sha256:cea221417204f2d1a2aa03ddae3e867921971d0d76f14d87abb4414415bbdcf5"},
]
PyYAML = [
    {file = "PyYAML-6.0-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:d4db7c7aef085872ef65a8fd7d6d09a14ae91f691dec3e87ee5ee0539d516f53"},
    {file = "PyYAML-6.0-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:9df7ed3b3d2e0ecfe09e14741b857df43adb5a3ddadc919a2d94fbdf78fea53c"},
    {file = "PyYAML-6.0-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:77f396e6ef4c73fdc33a9157446466f1cff553d979bd00ecb64385760c6babdc"},
    {file = "PyYAML-6.0-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:a80a78046a72361de73f8f395f1f1e49f956c6be882eed58505a15f3e430962b"},
    {file = "PyYAML-6.0-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:f84fbc98b019fef2ee9a1cb3ce93e3187a6df0b2538a651bfb890254ba9f90b5"},
    {file = "PyYAML-6.0-cp310-cp310-win32.whl", hash = "sha256:2cd5df3de48857ed0544b34e2d40e9fac445930039f3cfe4bcc592a1f836d513"},
    {file = "PyYAML-6.0-cp310-cp310-win_amd64.whl", hash = "sha256:daf496c58a8c52083df09b80c860005194014c3698698d1a57cbcfa182142a3a"},
    {file = "PyYAML-6.0-cp36-cp36m-macosx_10_9_x86_64.whl", hash = "sha256:897b80890765f037df3403d22bab41627ca8811ae55e9a722fd0392850ec4d86"},
    {file = "PyYAML-6.0-cp36-cp36m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:50602afada6d6cbfad699b0c7bb50d5ccffa7e46a3d738092afddc1f9758427f"},
    {file = "PyYAML-6.0-cp36-cp36m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:48c346915c114f5fdb3ead70312bd042a953a8ce5c7106d5bfb1a5254e47da92"},
    {file = "PyYAML-6.0-cp36-cp36m-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:98c4d36e99714e55cfbaaee6dd5badbc9a1ec339ebfc3b1f52e293aee6bb71a4"},
    {file = "PyYAML-6.0-cp36-cp36m-win32.whl", hash = "sha256:0283c35a6a9fbf047493e3a0ce8d79ef5030852c51e9d911a27badfde0605293"},
    {file = "PyYAML-6.0-cp36-cp36m-win_amd64.whl", hash = "sha256:07751360502caac1c067a8132d150cf3d61339af5691fe9e87803040dbc5db57"},
    {file = "PyYAML-6.0-cp37-cp37m-macosx_10_9_x86_64.whl", hash = "sha256:819b3830a1543db06c4d4b865e70ded25be52a2e0631ccd2f6a47a2822f2fd7c"},
    {file = "PyYAML-6.0-cp37-cp37m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:473f9edb243cb1935ab5a084eb238d842fb8f404ed2193a915d1784b5a6b5fc0"},
    {file = "PyYAML-6.0-cp37-cp37m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:0ce82d761c532fe4ec3f87fc45688bdd3a4c1dc5e0b4a19814b9009a29baefd4"},
    {file = "PyYAML-6.0-cp37-cp37m-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:231710d57adfd809ef5d34183b8ed1eeae3f76459c18fb4a0b373ad56bedcdd9"},
    {file = "PyYAML-6.0-cp37-cp37m-win32.whl", hash = "sha256:c5687b8d43cf58545ade1fe3e055f70eac7a5a1a0bf42824308d868289a95737"},
    {file = "PyYAML-6.0-cp37-cp37m-win_amd64.whl", hash = "sha256:d15a181d1ecd0d4270dc32edb46f7cb7733c7c508857278d3d378d14d606db2d"},
    {file = "PyYAML-6.0-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:0b4624f379dab24d3725ffde76559cff63d9ec94e1736b556dacdfebe5ab6d4b"},
    {file = "PyYAML-6.0-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:213c60cd50106436cc818accf5baa1aba61c0189ff610f64f4a3e8c6726218ba"},
    {file = "PyYAML-6.0-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:9fa600030013c4de8165339db93d182b9431076eb98eb40ee068700c9c813e34"},
    {file = "PyYAML-6.0-cp38-cp38-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:277a0ef2981ca40581a47093e9e2d13b3f1fbbeffae064c1d21bfceba2030287"},
    {file = "PyYAML-6.0-cp38-cp38-win32.whl", hash = "sha256:d4eccecf9adf6fbcc6861a38015c2a64f38b9d94838ac1810a9023a0609e1b78"},
    {file = "PyYAML-6.0-cp38-cp38-win_amd64.whl", hash = "sha256:1e4747bc279b4f613a09eb64bba2ba602d8a6664c6ce6396a4d0cd413a50ce07"},
    {file = "PyYAML-6.0-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:055d937d65826939cb044fc8c9b08889e8c743fdc6a32b33e2390f66013e449b"},
    {file = "PyYAML-6.0-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:e61ceaab6f49fb8bdfaa0f92c4b57bcfbea54c09277b1b4f7ac376bfb7a7c174"},
    {file = "PyYAML-6.0-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:d67d839ede4ed1b28a4e8909735fc992a923cdb84e618544973d7dfc71540803"},
    {file = "PyYAML-6.0-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:cba8c411ef271aa037d7357a2bc8f9ee8b58b9965831d9e51baf703280dc73d3"},
    {file = "PyYAML-6.0-cp39-cp39-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:40527857252b61eacd1d9af500c3337ba8deb8fc298940291486c465c8b46ec0"},
    {file = "PyYAML-6.0-cp39-cp39-win32.whl", hash = "sha256:b5b9eccad747aabaaffbc6064800670f0c297e52c12754eb1d976c57e4f74dcb"},
    {file = "PyYAML-6.0-cp39-cp39-win_amd64.whl", hash = "sha256:b3d267842bf12586ba6c734f89d1f5b871df0273157918b0ccefa29deb05c21c"},
    {file = "PyYAML-6.0.tar.gz", hash = "sha256:68fb519c14306fec9720a2a5b45bc9f0c8d1b9c72adf45c37baedfcd949c35a2"},
]
qdrant-client = [
    {file = "qdrant_client-0.10.2-py3-none-any.whl", hash = "sha256:41a16a5730ae98d503571713091de654633bf9f529bd48087ba9b770c2b6abe1"},
    {file = "qdrant_client-0.10.2.tar.gz", hash = "sha256:3c831c48b86f74fcd187bdd070449cde9606567fae1f424ec13d28810bd78a72"},
]
regex = [
    {file = "regex-2022.9.13-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:0394265391a86e2bbaa7606e59ac71bd9f1edf8665a59e42771a9c9adbf6fd4f"},
    {file = "regex-2022.9.13-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:86df2049b18745f3cd4b0f4c4ef672bfac4b80ca488e6ecfd2bbfe68d2423a2c"},
    {file = "regex-2022.9.13-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:ce331b076b2b013e7d7f07157f957974ef0b0881a808e8a4a4b3b5105aee5d04"},
    {file = "regex-2022.9.13-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:360ffbc9357794ae41336b681dff1c0463193199dfb91fcad3ec385ea4972f46"},
    {file = "regex-2022.9.13-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:18e503b1e515a10282b3f14f1b3d856194ecece4250e850fad230842ed31227f"},
    {file = "regex-2022.9.13-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:f6e167d1ccd41d27b7b6655bb7a2dcb1b1eb1e0d2d662043470bd3b4315d8b2b"},
    {file = "regex-2022.9.13-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:4146cb7ae6029fc83b5c905ec6d806b7e5568dc14297c423e66b86294bad6c39"},
    {file = "regex-2022.9.13-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:a1aec4ae549fd7b3f52ceaf67e133010e2fba1538bf4d5fc5cd162a5e058d5df"},
    {file = "regex-2022.9.13-cp310-cp310-musllinux_1_1_aarch64.whl", hash = "sha256:cab548d6d972e1de584161487b2ac1aa82edd8430d1bde69587ba61698ad1cfb"},
    {file = "regex-2022.9.13-cp310-cp310-musllinux_1_1_i686.whl", hash = "sha256:3d64e1a7e6d98a4cdc8b29cb8d8ed38f73f49e55fbaa737bdb5933db99b9de22"},
    {file = "regex-2022.9.13-cp310-cp310-musllinux_1_1_ppc64le.whl", hash = "sha256:67a4c625361db04ae40ef7c49d3cbe2c1f5ff10b5a4491327ab20f19f2fb5d40"},
    {file = "regex-2022.9.13-cp310-cp310-musllinux_1_1_s390x.whl", hash = "sha256:5d0dd8b06896423211ce18fba0c75dacc49182a1d6514c004b535be7163dca0f"},
    {file = "regex-2022.9.13-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:4318f69b79f9f7d84a7420e97d4bfe872dc767c72f891d4fea5fa721c74685f7"},
    {file = "regex-2022.9.13-cp310-cp310-win32.whl", hash = "sha256:26df88c9636a0c3f3bd9189dd435850a0c49d0b7d6e932500db3f99a6dd604d1"},
    {file = "regex-2022.9.13-cp310-cp310-win_amd64.whl", hash = "sha256:6fe1dd1021e0f8f3f454ce2811f1b0b148f2d25bb38c712fec00316551e93650"},
    {file = "regex-2022.9.13-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:83cc32a1a2fa5bac00f4abc0e6ce142e3c05d3a6d57e23bd0f187c59b4e1e43b"},
    {file = "regex-2022.9.13-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:a2effeaf50a6838f3dd4d3c5d265f06eabc748f476e8441892645ae3a697e273"},
    {file = "regex-2022.9.13-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:59a786a55d00439d8fae4caaf71581f2aaef7297d04ee60345c3594efef5648a"},
    {file = "regex-2022.9.13-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:b7b701dbc124558fd2b1b08005eeca6c9160e209108fbcbd00091fcfac641ac7"},
    {file = "regex-2022.9.13-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:dab81cc4d58026861445230cfba27f9825e9223557926e7ec22156a1a140d55c"},
    {file = "regex-2022.9.13-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:7b0c5cc3d1744a67c3b433dce91e5ef7c527d612354c1f1e8576d9e86bc5c5e2"},
    {file = "regex-2022.9.13-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:518272f25da93e02af4f1e94985f5042cec21557ef3591027d0716f2adda5d0a"},
    {file = "regex-2022.9.13-cp311-cp311-musllinux_1_1_aarch64.whl", hash = "sha256:8418ee2cb857b83881b8f981e4c636bc50a0587b12d98cb9b947408a3c484fe7"},
    {file = "regex-2022.9.13-cp311-cp311-musllinux_1_1_i686.whl", hash = "sha256:cfa4c956ff0a977c4823cb3b930b0a4e82543b060733628fec7ab3eb9b1abe37"},
    {file = "regex-2022.9.13-cp311-cp311-musllinux_1_1_ppc64le.whl", hash = "sha256:a1c4d17879dd4c4432c08a1ca1ab379f12ab54af569e945b6fc1c4cf6a74ca45"},
    {file = "regex-2022.9.13-cp311-cp311-musllinux_1_1_s390x.whl", hash = "sha256:77c2879d3ba51e5ca6c2b47f2dcf3d04a976a623a8fc8236010a16c9e0b0a3c7"},
    {file = "regex-2022.9.13-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:d2885ec6eea629c648ecc9bde0837ec6b92208b7f36381689937fe5d64a517e8"},
    {file = "regex-2022.9.13-cp311-cp311-win32.whl", hash = "sha256:2dda4b096a6f630d6531728a45bd12c67ec3badf44342046dc77d4897277d4f2"},
    {file = "regex-2022.9.13-cp311-cp311-win_amd64.whl", hash = "sha256:592b9e2e1862168e71d9e612bfdc22c451261967dbd46681f14e76dfba7105fd"},
    {file = "regex-2022.9.13-cp36-cp36m-macosx_10_9_x86_64.whl", hash = "sha256:df8fe00b60e4717662c7f80c810ba66dcc77309183c76b7754c0dff6f1d42054"},
    {file = "regex-2022.9.13-cp36-cp36m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:995e70bb8c91d1b99ed2aaf8ec44863e06ad1dfbb45d7df95f76ef583ec323a9"},
    {file = "regex-2022.9.13-cp36-cp36m-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:ad75173349ad79f9d21e0d0896b27dcb37bfd233b09047bc0b4d226699cf5c87"},
    {file = "regex-2022.9.13-cp36-cp36m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:7681c49da1a2d4b905b4f53d86c9ba4506e79fba50c4a664d9516056e0f7dfcc"},
    {file = "regex-2022.9.13-cp36-cp36m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:9bc8edc5f8ef0ebb46f3fa0d02bd825bbe9cc63d59e428ffb6981ff9672f6de1"},
    {file = "regex-2022.9.13-cp36-cp36m-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:b7bee775ff05c9d519195bd9e8aaaccfe3971db60f89f89751ee0f234e8aeac5"},
    {file = "regex-2022.9.13-cp36-cp36m-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:1a901ce5cd42658ab8f8eade51b71a6d26ad4b68c7cfc86b87efc577dfa95602"},
    {file = "regex-2022.9.13-cp36-cp36m-musllinux_1_1_aarch64.whl", hash = "sha256:14a7ab070fa3aec288076eed6ed828587b805ef83d37c9bfccc1a4a7cfbd8111"},
    {file = "regex-2022.9.13-cp36-cp36m-musllinux_1_1_i686.whl", hash = "sha256:d23ac6b4bf9e32fcde5fcdb2e1fd5e7370d6693fcac51ee1d340f0e886f50d1f"},
    {file = "regex-2022.9.13-cp36-cp36m-musllinux_1_1_ppc64le.whl", hash = "sha256:4cdbfa6d2befeaee0c899f19222e9b20fc5abbafe5e9c43a46ef819aeb7b75e5"},
    {file = "regex-2022.9.13-cp36-cp36m-musllinux_1_1_s390x.whl", hash = "sha256:ab07934725e6f25c6f87465976cc69aef1141e86987af49d8c839c3ffd367c72"},
    {file = "regex-2022.9.13-cp36-cp36m-musllinux_1_1_x86_64.whl", hash = "sha256:d2a1371dc73e921f3c2e087c05359050f3525a9a34b476ebc8130e71bec55e97"},
    {file = "regex-2022.9.13-cp36-cp36m-win32.whl", hash = "sha256:fcbd1edff1473d90dc5cf4b52d355cf1f47b74eb7c85ba6e45f45d0116b8edbd"},
    {file = "regex-2022.9.13-cp36-cp36m-win_amd64.whl", hash = "sha256:fe428822b7a8c486bcd90b334e9ab541ce6cc0d6106993d59f201853e5e14121"},
    {file = "regex-2022.9.13-cp37-cp37m-macosx_10_9_x86_64.whl", hash = "sha256:d7430f041755801b712ec804aaf3b094b9b5facbaa93a6339812a8e00d7bd53a"},
    {file = "regex-2022.9.13-cp37-cp37m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:079c182f99c89524069b9cd96f5410d6af437e9dca576a7d59599a574972707e"},
    {file = "regex-2022.9.13-cp37-cp37m-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:59bac44b5a07b08a261537f652c26993af9b1bbe2a29624473968dd42fc29d56"},
    {file = "regex-2022.9.13-cp37-cp37m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:a59d0377e58d96a6f11636e97992f5b51b7e1e89eb66332d1c01b35adbabfe8a"},
    {file = "regex-2022.9.13-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:b9d68eb704b24bc4d441b24e4a12653acd07d2c39940548761e0985a08bc1fff"},
    {file = "regex-2022.9.13-cp37-cp37m-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:0385d66e73cdd4462f3cc42c76a6576ddcc12472c30e02a2ae82061bff132c32"},
    {file = "regex-2022.9.13-cp37-cp37m-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:db45016364eec9ddbb5af93c8740c5c92eb7f5fc8848d1ae04205a40a1a2efc6"},
    {file = "regex-2022.9.13-cp37-cp37m-musllinux_1_1_aarch64.whl", hash = "sha256:03ff695518482b946a6d3d4ce9cbbd99a21320e20d94913080aa3841f880abcd"},
    {file = "regex-2022.9.13-cp37-cp37m-musllinux_1_1_i686.whl", hash = "sha256:6b32b45433df1fad7fed738fe15200b6516da888e0bd1fdd6aa5e50cc16b76bc"},
    {file = "regex-2022.9.13-cp37-cp37m-musllinux_1_1_ppc64le.whl", hash = "sha256:003a2e1449d425afc817b5f0b3d4c4aa9072dd5f3dfbf6c7631b8dc7b13233de"},
    {file = "regex-2022.9.13-cp37-cp37m-musllinux_1_1_s390x.whl", hash = "sha256:a9eb9558e1d0f78e07082d8a70d5c4d631c8dd75575fae92105df9e19c736730"},
    {file = "regex-2022.9.13-cp37-cp37m-musllinux_1_1_x86_64.whl", hash = "sha256:f6e0321921d2fdc082ef90c1fd0870f129c2e691bfdc4937dcb5cd308aba95c4"},
    {file = "regex-2022.9.13-cp37-cp37m-win32.whl", hash = "sha256:3f3b4594d564ed0b2f54463a9f328cf6a5b2a32610a90cdff778d6e3e561d08b"},
    {file = "regex-2022.9.13-cp37-cp37m-win_amd64.whl", hash = "sha256:8aba0d01e3dfd335f2cb107079b07fdddb4cd7fb2d8c8a1986f9cb8ce9246c24"},
    {file = "regex-2022.9.13-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:944567bb08f52268d8600ee5bdf1798b2b62ea002cc692a39cec113244cbdd0d"},
    {file = "regex-2022.9.13-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:0b664a4d33ffc6be10996606dfc25fd3248c24cc589c0b139feb4c158053565e"},
    {file = "regex-2022.9.13-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:f06cc1190f3db3192ab8949e28f2c627e1809487e2cfc435b6524c1ce6a2f391"},
    {file = "regex-2022.9.13-cp38-cp38-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:6c57d50d4d5eb0c862569ca3c840eba2a73412f31d9ecc46ef0d6b2e621a592b"},
    {file = "regex-2022.9.13-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:19a4da6f513045f5ba00e491215bd00122e5bd131847586522463e5a6b2bd65f"},
    {file = "regex-2022.9.13-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:a926339356fe29595f8e37af71db37cd87ff764e15da8ad5129bbaff35bcc5a6"},
    {file = "regex-2022.9.13-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:091efcfdd4178a7e19a23776dc2b1fafb4f57f4d94daf340f98335817056f874"},
    {file = "regex-2022.9.13-cp38-cp38-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:880dbeb6bdde7d926b4d8e41410b16ffcd4cb3b4c6d926280fea46e2615c7a01"},
    {file = "regex-2022.9.13-cp38-cp38-musllinux_1_1_aarch64.whl", hash = "sha256:73b985c9fc09a7896846e26d7b6f4d1fd5a20437055f4ef985d44729f9f928d0"},
    {file = "regex-2022.9.13-cp38-cp38-musllinux_1_1_i686.whl", hash = "sha256:c0b7cb9598795b01f9a3dd3f770ab540889259def28a3bf9b2fa24d52edecba3"},
    {file = "regex-2022.9.13-cp38-cp38-musllinux_1_1_ppc64le.whl", hash = "sha256:37e5a26e76c46f54b3baf56a6fdd56df9db89758694516413757b7d127d4c57b"},
    {file = "regex-2022.9.13-cp38-cp38-musllinux_1_1_s390x.whl", hash = "sha256:99945ddb4f379bb9831c05e9f80f02f079ba361a0fb1fba1fc3b267639b6bb2e"},
    {file = "regex-2022.9.13-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:8dcbcc9e72a791f622a32d17ff5011326a18996647509cac0609a7fc43adc229"},
    {file = "regex-2022.9.13-cp38-cp38-win32.whl", hash = "sha256:d3102ab9bf16bf541ca228012d45d88d2a567c9682a805ae2c145a79d3141fdd"},
    {file = "regex-2022.9.13-cp38-cp38-win_amd64.whl", hash = "sha256:14216ea15efc13f28d0ef1c463d86d93ca7158a79cd4aec0f9273f6d4c6bb047"},
    {file = "regex-2022.9.13-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:9a165a05979e212b2c2d56a9f40b69c811c98a788964e669eb322de0a3e420b4"},
    {file = "regex-2022.9.13-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:14c71437ffb89479c89cc7022a5ea2075a842b728f37205e47c824cc17b30a42"},
    {file = "regex-2022.9.13-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:ee7045623a5ace70f3765e452528b4c1f2ce669ed31959c63f54de64fe2f6ff7"},
    {file = "regex-2022.9.13-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:6e521d9db006c5e4a0f8acfef738399f72b704913d4e083516774eb51645ad7c"},
    {file = "regex-2022.9.13-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:b86548b8234b2be3985dbc0b385e35f5038f0f3e6251464b827b83ebf4ed90e5"},
    {file = "regex-2022.9.13-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:a2b39ee3b280e15824298b97cec3f7cbbe6539d8282cc8a6047a455b9a72c598"},
    {file = "regex-2022.9.13-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:e6e6e61e9a38b6cc60ca3e19caabc90261f070f23352e66307b3d21a24a34aaf"},
    {file = "regex-2022.9.13-cp39-cp39-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:d837ccf3bd2474feabee96cd71144e991472e400ed26582edc8ca88ce259899c"},
    {file = "regex-2022.9.13-cp39-cp39-musllinux_1_1_aarch64.whl", hash = "sha256:6adfe300848d61a470ec7547adc97b0ccf86de86a99e6830f1d8c8d19ecaf6b3"},
    {file = "regex-2022.9.13-cp39-cp39-musllinux_1_1_i686.whl", hash = "sha256:d5b003d248e6f292475cd24b04e5f72c48412231961a675edcb653c70730e79e"},
    {file = "regex-2022.9.13-cp39-cp39-musllinux_1_1_ppc64le.whl", hash = "sha256:d5edd3eb877c9fc2e385173d4a4e1d792bf692d79e25c1ca391802d36ecfaa01"},
    {file = "regex-2022.9.13-cp39-cp39-musllinux_1_1_s390x.whl", hash = "sha256:50e764ffbd08b06aa8c4e86b8b568b6722c75d301b33b259099f237c46b2134e"},
    {file = "regex-2022.9.13-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:6d43bd402b27e0e7eae85c612725ba1ce7798f20f6fab4e8bc3de4f263294f03"},
    {file = "regex-2022.9.13-cp39-cp39-win32.whl", hash = "sha256:7fcf7f94ccad19186820ac67e2ec7e09e0ac2dac39689f11cf71eac580503296"},
    {file = "regex-2022.9.13-cp39-cp39-win_amd64.whl", hash = "sha256:322bd5572bed36a5b39952d88e072738926759422498a96df138d93384934ff8"},
    {file = "regex-2022.9.13.tar.gz", hash = "sha256:f07373b6e56a6f3a0df3d75b651a278ca7bd357a796078a26a958ea1ce0588fd"},
]
requests = [
    {file = "requests-2.28.1-py3-none-any.whl", hash = "sha256:8fefa2a1a1365bf5520aac41836fbee479da67864514bdb821f31ce07ce65349"},
    {file = "requests-2.28.1.tar.gz", hash = "sha256:7c5599b102feddaa661c826c56ab4fee28bfd17f5abca1ebbe3e7f19d7c97983"},
]
rfc3986 = [
    {file = "rfc3986-1.5.0-py2.py3-none-any.whl", hash = "sha256:a86d6e1f5b1dc238b218b012df0aa79409667bb209e58da56d0b94704e712a97"},
    {file = "rfc3986-1.5.0.tar.gz", hash = "sha256:270aaf10d87d0d4e095063c65bf3ddbc6ee3d0b226328ce21e036f946e421835"},
]
scikit-learn = [
    {file = "scikit-learn-1.1.2.tar.gz", hash = "sha256:7c22d1305b16f08d57751a4ea36071e2215efb4c09cb79183faa4e8e82a3dbf8"},
    {file = "scikit_learn-1.1.2-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:6c840f662b5d3377c4ccb8be1fc21bb52cb5d8b8790f8d6bf021739f84e543cf"},
    {file = "scikit_learn-1.1.2-cp310-cp310-macosx_12_0_arm64.whl", hash = "sha256:2b8db962360c93554cab7bb3c096c4a24695da394dd4b3c3f13409f409b425bc"},
    {file = "scikit_learn-1.1.2-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:3e7d1fc817867a350133f937aaebcafbc06192517cbdf0cf7e5774ad4d1adb9f"},
    {file = "scikit_learn-1.1.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:5ec3ea40d467966821843210c02117d82b097b54276fdcfb50f4dfb5c60dbe39"},
    {file = "scikit_learn-1.1.2-cp310-cp310-win_amd64.whl", hash = "sha256:bbef6ea1c012ff9f3e6f6e9ca006b8772d8383e177b898091e68fbd9b3f840f9"},
    {file = "scikit_learn-1.1.2-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:a90ca42fe8242fd6ff56cda2fecc5fca586a88a24ab602d275d2d0dcc0b928fb"},
    {file = "scikit_learn-1.1.2-cp38-cp38-macosx_12_0_arm64.whl", hash = "sha256:a682ec0f82b6f30fb07486daed1c8001b6683cc66b51877644dfc532bece6a18"},
    {file = "scikit_learn-1.1.2-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:c33e16e9a165af6012f5be530ccfbb672e2bc5f9b840238a05eb7f6694304e3f"},
    {file = "scikit_learn-1.1.2-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:f94c0146bad51daef919c402a3da8c1c6162619653e1c00c92baa168fda292f2"},
    {file = "scikit_learn-1.1.2-cp38-cp38-win32.whl", hash = "sha256:2f46c6e3ff1054a5ec701646dcfd61d43b8ecac4d416014daed8843cf4c33d4d"},
    {file = "scikit_learn-1.1.2-cp38-cp38-win_amd64.whl", hash = "sha256:b1e706deca9b2ad87ae27dafd5ac4e8eff01b6db492ed5c12cef4735ec5f21ea"},
    {file = "scikit_learn-1.1.2-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:567417dbbe6a6278399c3e6daf1654414a5a1a4d818d28f251fa7fc28730a1bf"},
    {file = "scikit_learn-1.1.2-cp39-cp39-macosx_12_0_arm64.whl", hash = "sha256:d6f232779023c3b060b80b5c82e5823723bc424dcac1d1a148aa2492c54d245d"},
    {file = "scikit_learn-1.1.2-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:589d46f28460469f444b898223b13d99db9463e1038dc581ba698111f612264b"},
    {file = "scikit_learn-1.1.2-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:76800652fb6d6bf527bce36ecc2cc25738b28fe1a17bd294a218fff8e8bd6d50"},
    {file = "scikit_learn-1.1.2-cp39-cp39-win32.whl", hash = "sha256:1c8fecb7c9984d9ec2ea48898229f98aad681a0873e0935f2b7f724fbce4a047"},
    {file = "scikit_learn-1.1.2-cp39-cp39-win_amd64.whl", hash = "sha256:407e9a1cb9e6ba458a539986a9bd25546a757088095b3aab91d465b79a760d37"},
]
scipy = [
    {file = "scipy-1.9.1-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:c61b4a91a702e8e04aeb0bfc40460e1f17a640977c04dda8757efb0199c75332"},
    {file = "scipy-1.9.1-cp310-cp310-macosx_12_0_arm64.whl", hash = "sha256:d79da472015d0120ba9b357b28a99146cd6c17b9609403164b1a8ed149b4dfc8"},
    {file = "scipy-1.9.1-cp310-cp310-macosx_12_0_universal2.macosx_10_9_x86_64.whl", hash = "sha256:825951b88f56765aeb6e5e38ac9d7d47407cfaaeb008d40aa1b45a2d7ea2731e"},
    {file = "scipy-1.9.1-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:f950a04b33e17b38ff561d5a0951caf3f5b47caa841edd772ffb7959f20a6af0"},
    {file = "scipy-1.9.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:8cc81ac25659fec73599ccc52c989670e5ccd8974cf34bacd7b54a8d809aff1a"},
    {file = "scipy-1.9.1-cp310-cp310-win_amd64.whl", hash = "sha256:8d3faa40ac16c6357aaf7ea50394ea6f1e8e99d75e927a51102b1943b311b4d9"},
    {file = "scipy-1.9.1-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:7a412c476a91b080e456229e413792bbb5d6202865dae963d1e6e28c2bb58691"},
    {file = "scipy-1.9.1-cp38-cp38-macosx_12_0_arm64.whl", hash = "sha256:eb954f5aca4d26f468bbebcdc5448348eb287f7bea536c6306f62ea062f63d9a"},
    {file = "scipy-1.9.1-cp38-cp38-macosx_12_0_universal2.macosx_10_9_x86_64.whl", hash = "sha256:3c6f5d1d4b9a5e4fe5e14f26ffc9444fc59473bbf8d45dc4a9a15283b7063a72"},
    {file = "scipy-1.9.1-cp38-cp38-manylinux_2_12_i686.manylinux2010_i686.whl", hash = "sha256:bc4e2c77d4cd015d739e75e74ebbafed59ba8497a7ed0fd400231ed7683497c4"},
    {file = "scipy-1.9.1-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:0419485dbcd0ed78c0d5bf234c5dd63e86065b39b4d669e45810d42199d49521"},
    {file = "scipy-1.9.1-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:34441dfbee5b002f9e15285014fd56e5e3372493c3e64ae297bae2c4b9659f5a"},
    {file = "scipy-1.9.1-cp38-cp38-win32.whl", hash = "sha256:b97b479f39c7e4aaf807efd0424dec74bbb379108f7d22cf09323086afcd312c"},
    {file = "scipy-1.9.1-cp38-cp38-win_amd64.whl", hash = "sha256:e8fe305d9d67a81255e06203454729405706907dccbdfcc330b7b3482a6c371d"},
    {file = "scipy-1.9.1-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:39ab9240cd215a9349c85ab908dda6d732f7d3b4b192fa05780812495536acc4"},
    {file = "scipy-1.9.1-cp39-cp39-macosx_12_0_arm64.whl", hash = "sha256:71487c503e036740635f18324f62a11f283a632ace9d35933b2b0a04fd898c98"},
    {file = "scipy-1.9.1-cp39-cp39-macosx_12_0_universal2.macosx_10_9_x86_64.whl", hash = "sha256:3bc1ab68b9a096f368ba06c3a5e1d1d50957a86665fc929c4332d21355e7e8f4"},
    {file = "scipy-1.9.1-cp39-cp39-manylinux_2_12_i686.manylinux2010_i686.whl", hash = "sha256:f7c39f7dbb57cce00c108d06d731f3b0e2a4d3a95c66d96bce697684876ce4d4"},
    {file = "scipy-1.9.1-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:47d1a95bd9d37302afcfe1b84c8011377c4f81e33649c5a5785db9ab827a6ade"},
    {file = "scipy-1.9.1-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:96d7cf7b25c9f23c59a766385f6370dab0659741699ecc7a451f9b94604938ce"},
    {file = "scipy-1.9.1-cp39-cp39-win32.whl", hash = "sha256:09412eb7fb60b8f00b328037fd814d25d261066ebc43a1e339cdce4f7502877e"},
    {file = "scipy-1.9.1-cp39-cp39-win_amd64.whl", hash = "sha256:90c805f30c46cf60f1e76e947574f02954d25e3bb1e97aa8a07bc53aa31cf7d1"},
    {file = "scipy-1.9.1.tar.gz", hash = "sha256:26d28c468900e6d5fdb37d2812ab46db0ccd22c63baa095057871faa3a498bc9"},
]
sentence-transformers = [
    {file = "sentence-transformers-2.2.2.tar.gz", hash = "sha256:dbc60163b27de21076c9a30d24b5b7b6fa05141d68cf2553fa9a77bf79a29136"},
]
sentencepiece = [
    {file = "sentencepiece-0.1.97-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:6f249c8f1852893be86eae66b19d522c5fb30bbad4fe2d1b07f06fdc86e1907e"},
    {file = "sentencepiece-0.1.97-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:09e1bc53178de70c557a9ba4fece07364b4416ce3d36570726b3372b68aea135"},
    {file = "sentencepiece-0.1.97-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:667193c57fb48b238be7e3d7636cfc8da56cb5bac5559d8f0b647334e1175be8"},
    {file = "sentencepiece-0.1.97-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:2780531985af79c6163f63d4f200fec8a28b70b6768d2c19f70d01568a4524e8"},
    {file = "sentencepiece-0.1.97-cp310-cp310-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:205050670c53ef9015e2a98cce3934bfbcf0aafaa14caa0c618dd5667bc217ee"},
    {file = "sentencepiece-0.1.97-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:28b183dadef8e8b6b4645c1c20692d7be0a13ecc3ec1a07b3885c8905516675f"},
    {file = "sentencepiece-0.1.97-cp310-cp310-win32.whl", hash = "sha256:ee3c9dbd558d8d85bb1617087b86df6ea2b856a528669630ce6cedeb4353b823"},
    {file = "sentencepiece-0.1.97-cp310-cp310-win_amd64.whl", hash = "sha256:f7dc55379e2f7dee86537180283db2e5f8418c6825fdd2fe436c724eb5604c05"},
    {file = "sentencepiece-0.1.97-cp36-cp36m-macosx_10_9_x86_64.whl", hash = "sha256:ba1b4154f9144c5a7528b00aff5cffaa1a896a1c6ca53ca78b6e74cd2dae5244"},
    {file = "sentencepiece-0.1.97-cp36-cp36m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:ac3d90aee5581e55d029d124ac11b6ae2fbae0817863b664b2f2302e966ababb"},
    {file = "sentencepiece-0.1.97-cp36-cp36m-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:1c27400f1ac46518a01c87cb7703650e4e48728649feb115d2e3f1102a946a42"},
    {file = "sentencepiece-0.1.97-cp36-cp36m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:c6e12a166eba75994ca749aadc4a5056b91b31405f805d6de6e8914cc9741c60"},
    {file = "sentencepiece-0.1.97-cp36-cp36m-win32.whl", hash = "sha256:ed85dff5c0a9b3dd1a414c7e1119f2a19e863fc3f81da525bf7f885ebc883de0"},
    {file = "sentencepiece-0.1.97-cp36-cp36m-win_amd64.whl", hash = "sha256:91a19ab6f40ffbae6d6127119953d2c6a85e93d734953dbc8629fde0d21ace66"},
    {file = "sentencepiece-0.1.97-cp37-cp37m-macosx_10_9_x86_64.whl", hash = "sha256:bae580e4a35a9314ff49561ac7c06574fe6afc71b821ed6bb00534e571458156"},
    {file = "sentencepiece-0.1.97-cp37-cp37m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:4ad7262e7530c683b186672b5dd0082f82719a50a500a8cfbc4bbd7cde5bff8c"},
    {file = "sentencepiece-0.1.97-cp37-cp37m-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:620cee35279720016735a7c7103cddbd9b84fe5e2f098bd5e673834d69fee2b8"},
    {file = "sentencepiece-0.1.97-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:93b921b59914c0ec6697e8c6d5e6b44d99d1298fb1a0af56980a79ade0540c19"},
    {file = "sentencepiece-0.1.97-cp37-cp37m-win32.whl", hash = "sha256:9b9a4c44a31d5f47616e9568dcf31e029b0bfa776e0a252c0b59247881598b09"},
    {file = "sentencepiece-0.1.97-cp37-cp37m-win_amd64.whl", hash = "sha256:f31533cdacced56219e239d3459a003ece35116920dd64b2309d4ad047b77644"},
    {file = "sentencepiece-0.1.97-cp38-cp38-macosx_10_9_universal2.whl", hash = "sha256:7d643c01d1cad13b9206a276bbe5bc1a468e3d7cf6a26bde7783f945277f859d"},
    {file = "sentencepiece-0.1.97-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:542f1985b1ee279a92bef7740ec0781452372028ce01e15aa88df3228b197ba3"},
    {file = "sentencepiece-0.1.97-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:93701da21fea906dd244bf88cdbe640385a89c45d3c1812b76dbadf8782cdbcd"},
    {file = "sentencepiece-0.1.97-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:a51514047b964047b7fadb480d88a5e0f72c02f6ca1ba96258fbbc6e79274a94"},
    {file = "sentencepiece-0.1.97-cp38-cp38-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:e3ae2e9b7a5b6f2aa64ec9240b0c185dabe597d0e787dc4344acfbaef1ffe0b2"},
    {file = "sentencepiece-0.1.97-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:923ee4af16dbae1f2ab358ed09f8a0eb89e40a8198a8b343bf54181482342721"},
    {file = "sentencepiece-0.1.97-cp38-cp38-win32.whl", hash = "sha256:fa6f2b88850b5fae3a05053658824cf9f147c8e3c3b40eb64539a976c83d8a24"},
    {file = "sentencepiece-0.1.97-cp38-cp38-win_amd64.whl", hash = "sha256:5137ff0d0b1cc574751d178650ef800ff8d90bf21eb9f71e9567d4a0548940a5"},
    {file = "sentencepiece-0.1.97-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:f92876271a10494671431ad955bff2d6f8ea59baaf957f5ae5946aff56dfcb90"},
    {file = "sentencepiece-0.1.97-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:35c227b6d55e473033db7e0ecc51b1e99e6ed7607cc08602fb5768132543c81d"},
    {file = "sentencepiece-0.1.97-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:1706a8a8188f7b3d4b7922db9bb00c64c4e16ee68ab4caaae79f55b3e18748c7"},
    {file = "sentencepiece-0.1.97-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:ce61efc1862ccb18856c4aabbd930e13d5bfbb4b09b4f111081ac53a9dc62275"},
    {file = "sentencepiece-0.1.97-cp39-cp39-manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:a78c03800ef9f02d320e0159f5768b15357f3e9ebea545c9c4ba7928ba8ba254"},
    {file = "sentencepiece-0.1.97-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:753b8088fd685ee787d9f54c84275ab347de558c7c4ebc6accb4c35bf7776f20"},
    {file = "sentencepiece-0.1.97-cp39-cp39-win32.whl", hash = "sha256:24306fd86031c17a1a6ae92671e76a350390a3140a65620bc2843dad7db24e2a"},
    {file = "sentencepiece-0.1.97-cp39-cp39-win_amd64.whl", hash = "sha256:c6641d0b7acec61fde5881ea6ebe098c169557ac9aa3bdabdf124eab5a5592bb"},
    {file = "sentencepiece-0.1.97.tar.gz", hash = "sha256:c901305e0a710bbcd296f66d79e96f744e6e175b29812bd5178318437d4e1f6c"},
]
setuptools = [
    {file = "setuptools-65.4.0-py3-none-any.whl", hash = "sha256:c2d2709550f15aab6c9110196ea312f468f41cd546bceb24127a1be6fdcaeeb1"},
    {file = "setuptools-65.4.0.tar.gz", hash = "sha256:a8f6e213b4b0661f590ccf40de95d28a177cd747d098624ad3f69c40287297e9"},
]
six = [
    {file = "six-1.16.0-py2.py3-none-any.whl", hash = "sha256:8abb2f1d86890a2dfb989f9a77cfcfd3e47c2a354b01111771326f8aa26e0254"},
    {file = "six-1.16.0.tar.gz", hash = "sha256:1e61c37477a1626458e36f7b1d82aa5c9b094fa4802892072e49de9c60c4c926"},
]
sniffio = [
    {file = "sniffio-1.3.0-py3-none-any.whl", hash = "sha256:eecefdce1e5bbfb7ad2eeaabf7c1eeb404d7757c379bd1f7e5cce9d8bf425384"},
    {file = "sniffio-1.3.0.tar.gz", hash = "sha256:e60305c5e5d314f5389259b7f22aaa33d8f7dee49763119234af3755c55b9101"},
]
starlette = [
    {file = "starlette-0.14.2-py3-none-any.whl", hash = "sha256:3c8e48e52736b3161e34c9f0e8153b4f32ec5d8995a3ee1d59410d92f75162ed"},
    {file = "starlette-0.14.2.tar.gz", hash = "sha256:7d49f4a27f8742262ef1470608c59ddbc66baf37c148e938c7038e6bc7a998aa"},
]
threadpoolctl = [
    {file = "threadpoolctl-3.1.0-py3-none-any.whl", hash = "sha256:8b99adda265feb6773280df41eece7b2e6561b772d21ffd52e372f999024907b"},
    {file = "threadpoolctl-3.1.0.tar.gz", hash = "sha256:a335baacfaa4400ae1f0d8e3a58d6674d2f8828e3716bb2802c44955ad391380"},
]
tokenizers = [
    {file = "tokenizers-0.12.1-cp310-cp310-macosx_10_11_x86_64.whl", hash = "sha256:d737df0f8f26e093a82bfb106b6cfb510a0e9302d35834568e5b20b73ddc5a9c"},
    {file = "tokenizers-0.12.1-cp310-cp310-manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:f1271224acafb27639c432e1ce4e7d38eab40305ba1c546e871d5c8a32f4f195"},
    {file = "tokenizers-0.12.1-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:cdeba37c2fb44e1aec8a72af4cb369655b59ba313181b1b4b8183f08e759c49c"},
    {file = "tokenizers-0.12.1-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:53b5f4012ce3ffddd5b00827441b80dc7a0f6b41f4fc5248ae6d36e7d3920c6d"},
    {file = "tokenizers-0.12.1-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:5188e13fc09edfe05712ca3ae5a44e7f2b0137927b1ca210d0fad90d3e58315a"},
    {file = "tokenizers-0.12.1-cp310-cp310-win32.whl", hash = "sha256:eff5ff411f18a201eec137b7b32fcb55e0c48b372d370bd24f965f5bad471fa4"},
    {file = "tokenizers-0.12.1-cp310-cp310-win_amd64.whl", hash = "sha256:bdbca79726fe883c696088ea163715b2f902aec638a8e24bcf9790ff8fa45019"},
    {file = "tokenizers-0.12.1-cp36-cp36m-manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:28825dade9e52ad464164020758f9d49eb7251c32b6ae146601c506a23c67c0e"},
    {file = "tokenizers-0.12.1-cp36-cp36m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:91906d725cb84d8ee71ce05fbb155d39d494849622b4f9349e5176a8eb01c49b"},
    {file = "tokenizers-0.12.1-cp36-cp36m-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:230f51a0a82ca7b90077eaca2415f12ff9bd144607888b9c50c2ee543452322e"},
    {file = "tokenizers-0.12.1-cp36-cp36m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:8d4339c376b695de2ad8ccaebffa75e4dc1d7857be1103d80e7925b34af8cf78"},
    {file = "tokenizers-0.12.1-cp37-cp37m-macosx_10_11_x86_64.whl", hash = "sha256:27d93b712aa2d4346aa506ecd4ec9e94edeebeaf2d484357b482cdeffc02b5f5"},
    {file = "tokenizers-0.12.1-cp37-cp37m-manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:7f4cb68dc538b52240d1986d2034eb0a6373be2ab5f0787d1be3ad1444ce71b7"},
    {file = "tokenizers-0.12.1-cp37-cp37m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:ae6c04b629ac2cd2f695739988cb70b9bd8d5e7f849f5b14c4510e942bee5770"},
    {file = "tokenizers-0.12.1-cp37-cp37m-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:6a38b2019d4807d42afeff603a119094ee00f63bea2921136524c8814e9003f8"},
    {file = "tokenizers-0.12.1-cp37-cp37m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:fde8dccb9033fa344ffce3ee1837939a50e7a210a768f1cf2059beeafa755481"},
    {file = "tokenizers-0.12.1-cp37-cp37m-win32.whl", hash = "sha256:38625595b2fd37bfcce64ff9bfb6868c07e9a7b7f205c909d94a615ce9472287"},
    {file = "tokenizers-0.12.1-cp37-cp37m-win_amd64.whl", hash = "sha256:01abe6fbfe55e4131ca0c4c3d1a9d7ef5df424a8d536e998d2a4fc0bc57935f4"},
    {file = "tokenizers-0.12.1-cp38-cp38-macosx_10_11_x86_64.whl", hash = "sha256:7c5c54080a7d5c89c990e0d478e0882dbac88926d43323a3aa236492a3c9455f"},
    {file = "tokenizers-0.12.1-cp38-cp38-manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:419d113e3bcc4fe20a313afc47af81e62906306b08fe1601e1443d747d46af1f"},
    {file = "tokenizers-0.12.1-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:b9779944559cb7ace6a8516e402895f239b0d9d3c833c67dbaec496310e7e206"},
    {file = "tokenizers-0.12.1-cp38-cp38-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:7d43de14b4469b57490dbaf136a31c266cb676fa22320f01f230af9219ae9034"},
    {file = "tokenizers-0.12.1-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:258873634406bd1d438c799993a5e44bbc0132ff055985c03c4fe30f702e9a33"},
    {file = "tokenizers-0.12.1-cp38-cp38-win32.whl", hash = "sha256:3f2647cc256d6a53d18b9dcd71d377828e9f8991fbcbd6fcd8ca2ceb174552b0"},
    {file = "tokenizers-0.12.1-cp38-cp38-win_amd64.whl", hash = "sha256:62a723bd4b18bc55121f5c34cd8efd6c651f2d3b81f81dd50e5351fb65b8a617"},
    {file = "tokenizers-0.12.1-cp39-cp39-macosx_10_11_x86_64.whl", hash = "sha256:411ebc89228f30218ffa9d9c49d414864b0df5026a47c24820431821c4360460"},
    {file = "tokenizers-0.12.1-cp39-cp39-manylinux_2_12_x86_64.manylinux2010_x86_64.whl", hash = "sha256:619728df2551bdfe6f96ff177f9ded958e7ed9e2af94c8d5ac2834d1eb06d112"},
    {file = "tokenizers-0.12.1-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:8cea98f3f9577d1541b7bb0f7a3308a911751067e1d83e01485c9d3411bbf087"},
    {file = "tokenizers-0.12.1-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:664f36f0a0d409c24f2201d495161fec4d8bc93e091fbb78814eb426f29905a3"},
    {file = "tokenizers-0.12.1-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:0bf2380ad59c50222959a9b6f231339200a826fc5cb2be09ff96d8a59f65fc5e"},
    {file = "tokenizers-0.12.1-cp39-cp39-win32.whl", hash = "sha256:6a7a106d04154c2159db6cd7d042af2e2e0e53aee432f872fe6c8be45100436a"},
    {file = "tokenizers-0.12.1-cp39-cp39-win_amd64.whl", hash = "sha256:2158baf80cbc09259bfd6e0e0fc4597b611e7a72ad5443dad63918a90f1dd304"},
    {file = "tokenizers-0.12.1.tar.gz", hash = "sha256:070746f86efa6c873db341e55cf17bb5e7bdd5450330ca8eca542f5c3dab2c66"},
]
torch = [
    {file = "torch-1.12.1-cp310-cp310-manylinux1_x86_64.whl", hash = "sha256:9c038662db894a23e49e385df13d47b2a777ffd56d9bcd5b832593fab0a7e286"},
    {file = "torch-1.12.1-cp310-cp310-manylinux2014_aarch64.whl", hash = "sha256:4e1b9c14cf13fd2ab8d769529050629a0e68a6fc5cb8e84b4a3cc1dd8c4fe541"},
    {file = "torch-1.12.1-cp310-cp310-win_amd64.whl", hash = "sha256:e9c8f4a311ac29fc7e8e955cfb7733deb5dbe1bdaabf5d4af2765695824b7e0d"},
    {file = "torch-1.12.1-cp310-none-macosx_10_9_x86_64.whl", hash = "sha256:976c3f997cea38ee91a0dd3c3a42322785414748d1761ef926b789dfa97c6134"},
    {file = "torch-1.12.1-cp310-none-macosx_11_0_arm64.whl", hash = "sha256:68104e4715a55c4bb29a85c6a8d57d820e0757da363be1ba680fa8cc5be17b52"},
    {file = "torch-1.12.1-cp37-cp37m-manylinux1_x86_64.whl", hash = "sha256:743784ccea0dc8f2a3fe6a536bec8c4763bd82c1352f314937cb4008d4805de1"},
    {file = "torch-1.12.1-cp37-cp37m-manylinux2014_aarch64.whl", hash = "sha256:b5dbcca369800ce99ba7ae6dee3466607a66958afca3b740690d88168752abcf"},
    {file = "torch-1.12.1-cp37-cp37m-win_amd64.whl", hash = "sha256:f3b52a634e62821e747e872084ab32fbcb01b7fa7dbb7471b6218279f02a178a"},
    {file = "torch-1.12.1-cp37-none-macosx_10_9_x86_64.whl", hash = "sha256:8a34a2fbbaa07c921e1b203f59d3d6e00ed379f2b384445773bd14e328a5b6c8"},
    {file = "torch-1.12.1-cp37-none-macosx_11_0_arm64.whl", hash = "sha256:42f639501928caabb9d1d55ddd17f07cd694de146686c24489ab8c615c2871f2"},
    {file = "torch-1.12.1-cp38-cp38-manylinux1_x86_64.whl", hash = "sha256:0b44601ec56f7dd44ad8afc00846051162ef9c26a8579dda0a02194327f2d55e"},
    {file = "torch-1.12.1-cp38-cp38-manylinux2014_aarch64.whl", hash = "sha256:cd26d8c5640c3a28c526d41ccdca14cf1cbca0d0f2e14e8263a7ac17194ab1d2"},
    {file = "torch-1.12.1-cp38-cp38-win_amd64.whl", hash = "sha256:42e115dab26f60c29e298559dbec88444175528b729ae994ec4c65d56fe267dd"},
    {file = "torch-1.12.1-cp38-none-macosx_10_9_x86_64.whl", hash = "sha256:a8320ba9ad87e80ca5a6a016e46ada4d1ba0c54626e135d99b2129a4541c509d"},
    {file = "torch-1.12.1-cp38-none-macosx_11_0_arm64.whl", hash = "sha256:03e31c37711db2cd201e02de5826de875529e45a55631d317aadce2f1ed45aa8"},
    {file = "torch-1.12.1-cp39-cp39-manylinux1_x86_64.whl", hash = "sha256:9b356aea223772cd754edb4d9ecf2a025909b8615a7668ac7d5130f86e7ec421"},
    {file = "torch-1.12.1-cp39-cp39-manylinux2014_aarch64.whl", hash = "sha256:6cf6f54b43c0c30335428195589bd00e764a6d27f3b9ba637aaa8c11aaf93073"},
    {file = "torch-1.12.1-cp39-cp39-win_amd64.whl", hash = "sha256:f00c721f489089dc6364a01fd84906348fe02243d0af737f944fddb36003400d"},
    {file = "torch-1.12.1-cp39-none-macosx_10_9_x86_64.whl", hash = "sha256:bfec2843daa654f04fda23ba823af03e7b6f7650a873cdb726752d0e3718dada"},
    {file = "torch-1.12.1-cp39-none-macosx_11_0_arm64.whl", hash = "sha256:69fe2cae7c39ccadd65a123793d30e0db881f1c1927945519c5c17323131437e"},
]
torchvision = [
    {file = "torchvision-0.13.1-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:19286a733c69dcbd417b86793df807bd227db5786ed787c17297741a9b0d0fc7"},
    {file = "torchvision-0.13.1-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:08f592ea61836ebeceb5c97f4d7a813b9d7dc651bbf7ce4401563ccfae6a21fc"},
    {file = "torchvision-0.13.1-cp310-cp310-manylinux1_x86_64.whl", hash = "sha256:ef5fe3ec1848123cd0ec74c07658192b3147dcd38e507308c790d5943e87b88c"},
    {file = "torchvision-0.13.1-cp310-cp310-manylinux2014_aarch64.whl", hash = "sha256:099874088df104d54d8008f2a28539ca0117b512daed8bf3c2bbfa2b7ccb187a"},
    {file = "torchvision-0.13.1-cp310-cp310-win_amd64.whl", hash = "sha256:8e4d02e4d8a203e0c09c10dfb478214c224d080d31efc0dbf36d9c4051f7f3c6"},
    {file = "torchvision-0.13.1-cp37-cp37m-macosx_10_9_x86_64.whl", hash = "sha256:5e631241bee3661de64f83616656224af2e3512eb2580da7c08e08b8c965a8ac"},
    {file = "torchvision-0.13.1-cp37-cp37m-manylinux1_x86_64.whl", hash = "sha256:899eec0b9f3b99b96d6f85b9aa58c002db41c672437677b553015b9135b3be7e"},
    {file = "torchvision-0.13.1-cp37-cp37m-manylinux2014_aarch64.whl", hash = "sha256:83e9e2457f23110fd53b0177e1bc621518d6ea2108f570e853b768ce36b7c679"},
    {file = "torchvision-0.13.1-cp37-cp37m-win_amd64.whl", hash = "sha256:7552e80fa222252b8b217a951c85e172a710ea4cad0ae0c06fbb67addece7871"},
    {file = "torchvision-0.13.1-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:f230a1a40ed70d51e463ce43df243ec520902f8725de2502e485efc5eea9d864"},
    {file = "torchvision-0.13.1-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:e9a563894f9fa40692e24d1aa58c3ef040450017cfed3598ff9637f404f3fe3b"},
    {file = "torchvision-0.13.1-cp38-cp38-manylinux1_x86_64.whl", hash = "sha256:7cb789ceefe6dcd0dc8eeda37bfc45efb7cf34770eac9533861d51ca508eb5b3"},
    {file = "torchvision-0.13.1-cp38-cp38-manylinux2014_aarch64.whl", hash = "sha256:87c137f343197769a51333076e66bfcd576301d2cd8614b06657187c71b06c4f"},
    {file = "torchvision-0.13.1-cp38-cp38-win_amd64.whl", hash = "sha256:4d8bf321c4380854ef04613935fdd415dce29d1088a7ff99e06e113f0efe9203"},
    {file = "torchvision-0.13.1-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:0298bae3b09ac361866088434008d82b99d6458fe8888c8df90720ef4b347d44"},
    {file = "torchvision-0.13.1-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:c5ed609c8bc88c575226400b2232e0309094477c82af38952e0373edef0003fd"},
    {file = "torchvision-0.13.1-cp39-cp39-manylinux1_x86_64.whl", hash = "sha256:3567fb3def829229ec217c1e38f08c5128ff7fb65854cac17ebac358ff7aa309"},
    {file = "torchvision-0.13.1-cp39-cp39-manylinux2014_aarch64.whl", hash = "sha256:b167934a5943242da7b1e59318f911d2d253feeca0d13ad5d832b58eed943401"},
    {file = "torchvision-0.13.1-cp39-cp39-win_amd64.whl", hash = "sha256:0e77706cc90462653620e336bb90daf03d7bf1b88c3a9a3037df8d111823a56e"},
]
tqdm = [
    {file = "tqdm-4.64.1-py2.py3-none-any.whl", hash = "sha256:6fee160d6ffcd1b1c68c65f14c829c22832bc401726335ce92c52d395944a6a1"},
    {file = "tqdm-4.64.1.tar.gz", hash = "sha256:5f4f682a004951c1b450bc753c710e9280c5746ce6ffedee253ddbcbf54cf1e4"},
]
transformers = [
    {file = "transformers-4.22.1-py3-none-any.whl", hash = "sha256:8f06d0dbdb95717fc4a48c61d876f25a35ca67e95851581c681fe4e6d1cf9f94"},
    {file = "transformers-4.22.1.tar.gz", hash = "sha256:b9834aa01979778c16130ad260e41d314f4c3a65930bdc40b1232833c988280b"},
]
typing-extensions = [
    {file = "typing_extensions-4.3.0-py3-none-any.whl", hash = "sha256:25642c956049920a5aa49edcdd6ab1e06d7e5d467fc00e0506c44ac86fbfca02"},
    {file = "typing_extensions-4.3.0.tar.gz", hash = "sha256:e6d2677a32f47fc7eb2795db1dd15c1f34eff616bcaf2cfb5e997f854fa1c4a6"},
]
urllib3 = [
    {file = "urllib3-1.26.12-py2.py3-none-any.whl", hash = "sha256:b930dd878d5a8afb066a637fbb35144fe7901e3b209d1cd4f524bd0e9deee997"},
    {file = "urllib3-1.26.12.tar.gz", hash = "sha256:3fa96cf423e6987997fc326ae8df396db2a8b7c667747d47ddd8ecba91f4a74e"},
]
uvicorn = [
    {file = "uvicorn-0.12.3-py3-none-any.whl", hash = "sha256:562ef6aaa8fa723ab6b82cf9e67a774088179d0ec57cb17e447b15d58b603bcf"},
    {file = "uvicorn-0.12.3.tar.gz", hash = "sha256:5836edaf4d278fe67ba0298c0537bdb6398cf359eb644f79e6500ca1aad232b3"},
]
win32-setctime = [
    {file = "win32_setctime-1.1.0-py3-none-any.whl", hash = "sha256:231db239e959c2fe7eb1d7dc129f11172354f98361c4fa2d6d2d7e278baa8aad"},
    {file = "win32_setctime-1.1.0.tar.gz", hash = "sha256:15cf5750465118d6929ae4de4eb46e8edae9a5634350c01ba582df868e932cb2"},
]
