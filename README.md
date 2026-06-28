# YAML (YML)

## What is YAML?
YAML stands for "YAML Ain't Markup Language".

It is used for:
- Configuration files
- GitHub Actions workflows
- Automation setup

## Basic Structure

```yaml
on: push

jobs:
  my-job:
    runs-on: ubuntu-latest

    env:
      APP_NAME: EduPak

    steps:
      - run: echo "Hello"
## Use spaces (not tabs)
## Indentation matters
## Use : after keys
## Use - for lists

## YAML Syntax Rules:
## 1. Use Spaces

Correct:

```yaml
name: EduPak
version: 1.0
```

Wrong:

```yaml
name:EduPak
	version:1.0
```

(Tabs should not be used)