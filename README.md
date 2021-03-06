Complete example of how to create a Blog with HTML over the Wire architecture in Python using Django and Channels.

- Change pages.
- List of articles.
- Search engine.
- Single page for each article.
- List of comments for each article.
- Possibility of adding new comments with real-time updating for all users who are connected.
- Static page.
- RSS feed.
- URL update.
- Server-Side Rendering (SSR) of pages for SEO. 
- Cross-site request forgery protection over WebSockets.

## Run 🏃

1. Up

```
docker-compose up
```

2. Add data. 

Run in Django container.

```
./manage.py shell < make_fake_data.py
```

## Thanks 😍

- [Django](https://www.djangoproject.com/)
- [Channels](https://channels.readthedocs.io/en/stable/)
