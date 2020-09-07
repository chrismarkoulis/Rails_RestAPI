# Ruby on Rails API with MySQL Database

> Simple RESTful API to create, read, update and delete articles

## Quick Start


``` bash
# Install gems
bundler install

# Start dev server at localhost:3000
rails s

```

## Endpoints

### Get All Articles
``` bash
GET api/v1/articles
```
### Get Single Article
``` bash
GET api/v1/article/{id}
```

### Delete Article
``` bash
DELETE api/v1/articles/{id}
```

### Create Article
``` bash
POST api/v1/articles
```

### Update Article
``` bash
PUT api/v1/articles/{id}
