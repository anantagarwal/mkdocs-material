# mkdocs-material

## Local server

```bash
python3 -m venv venv
source venv/bin/activate
pip install mkdocs-material
mkdocs serve
```

## Docker

### Start development server

```
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material

docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material:9.1.4

```

### Build documentation

```
docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build

docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material:9.1.4 build



```
