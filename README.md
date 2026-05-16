# blog-personal

A small personal blog designed to publish directly with GitHub Pages.

## Local preview

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. Open the repository settings.
3. Go to **Pages**.
4. Set the source to **Deploy from a branch**.
5. Choose `main` and `/root`.

## Writing posts

Posts live in `posts/`. Add a new HTML file there and link it from `index.html`.
