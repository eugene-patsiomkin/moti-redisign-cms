# CMS

## Running

Install "Docker desktop" <https://www.docker.com/products/docker-desktop>

Clone or copy repository

```bash
docker-compose up
```

## Accessing site

### Content

In the browser open: <http://localhost>

### Administration

In the browser open: <http://localhost/ghost>

```info
user: user@examle.com
password: bitnami123
```

### API

First create an integration to get a content key!

<http://localhost/ghost/api/v3/content/posts?[key=your_key_here]&include=tags,authors>
<http://localhost/ghost/api/v3/content/posts/slug/welcome?key=[key=your_key_here]&include=tags,authors>
