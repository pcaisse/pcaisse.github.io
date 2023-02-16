# Peter Caisse's Personal Site

Based off of the [Gradfolio](https://github.com/jitinnair1/gradfolio) Jekyll theme.

Run locally from project root with Docker via:

```bash
docker run -it -p 4000:4000 --volume=$(pwd):/srv/jekyll jekyll/jekyll bash -c "jekyll build && jekyll serve"
```

Site should then be running on http://localhost:4000
