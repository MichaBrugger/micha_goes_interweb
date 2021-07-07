---
title: "Bash"
date: "2021-07-07"
author: ""
path: "/bash"
---

- [Create](#create)
  - [Directory](#directory)
  - [File](#file)
- [Custom](#custom)
  - [Alias: Activate virtual env](#alias-activate-virtual-env)
  - [Anideaio frontend](#anideaio-frontend)
  - [Anideaio backend](#anideaio-backend)

      
## Create

### Directory
Create one directory:

```$ mkdir foldername ```

Create multiple folders:

```$ mkdir folder1 folder2```

Nested folders:

```$ mkdir folder1/folder2```

### File
```touch filename.filetype```

## Custom

Stored in ```~/.bashrc```

### Alias: Activate virtual env
```alias venv="source venv/bin/activate"```

### Anideaio frontend

```
start_anideaio_f() {
cd ~
cd ~/Documents/GitHub/projectplaceholder/anideaio_frontend/app
export BROWSER=google-chrome-unstable
npm start
}
```

### Anideaio backend

```
start_anideaio_b() {
cd ~
cd ~/Documents/GitHub/projectplaceholder/anideaio_backend
source venv/bin/activate
python manage.py runserver
}
```