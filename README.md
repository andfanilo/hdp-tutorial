# Big Data tutorial - Hortonworks Platform

Hadoop tutorial using the [Hortonworks Sandbox](https://www.root.com/downloads/hortonworks-sandbox/hdp.html) for university lecture.

## Installation

```
pip install mkdocs-material
```

## Dev

```
mkdocs serve
```

## Build

```
mkdocs build
cd site/
python -m http.server
```

## Deploy 

Because of 2FA, deploy with:

```
mkdocs build
mkdocs gh-deploy
```
