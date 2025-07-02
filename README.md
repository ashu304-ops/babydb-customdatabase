https://pypi.org/project/babydb/1.0.1/

````markdown
# SimpleDB

A lightweight key-value database with compression, supporting CLI and web interfaces.

---

## Installation

```bash
pip install babydb
````

---

## Usage

### CLI

```bash
simpledb-cli
```

### Web

```bash
simpledb-web
```

Access the web interface at [http://localhost:5000](http://localhost:5000).

---

## Features

* Compressed storage (`database.json.gz`, `.gz` files)
* CRUD operations, file uploads/downloads, full-text search
* Transaction support (`begin`, `commit`, `rollback`)
* Admin/user roles

  * `admin`: `admin123`
  * `user`: `user123`

---

## Example

```bash
simpledb-cli
> login admin admin123
> create student001 "{\"Name\": \"Alice\", \"Age\": 15, \"Grade\": 10, \"Class\": \"A\", \"Subjects\": [\"Math\", \"Science\"]}"
> upload student001 photo.jpg
> find fulltext "Math Science" sortby Age
```

```

---


```
