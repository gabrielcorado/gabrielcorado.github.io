# My personal blog/website
This website is based on [Kactus Theme](https://github.com/nickbalestra/kactus), thanks to [@nickbalestra](https://github.com/nickbalestra).

## Development
I'm developing this website using **jekyll docker** image. `docker pull jekyll/jekyll:pages`

And running it using the following command inside the project folder
`docker run --rm -it -v (PWD):/srv/jekyll -p 4000:4000 jekyll/jekyll:pages jekyll serve --drafts`

## TODO
A list of todos to make this website better.

* Personal links in the profile `component` (ex.: Github, LinkedIn)
* Share posts into LinkedIn
* Projects Page
* Start writing some posts.
