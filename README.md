# Simple Timezone management by city
using [World Time API](http://worldtimeapi.org)

## Clone the repo

```
git clone https://github.com/arcbjorn/vue-django-graphql-blog.git
cd city_timezone_management_fastapi
```

## Setup virtual environment
```sh
python3 -m venv ./venv
```

## Activate virtual environment

```sh
source ./venv/bin/activate
```

## Install dependencies

```sh
pip3 install -r dependencies.txt
```

## Start the uvicorn server

```sh
uvicorn main:app --reload
```