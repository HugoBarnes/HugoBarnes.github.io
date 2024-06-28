# Hugo Barnes' Personal Site

This is the Github pages repository for my private site, meant to be rendered
using [Jekyll](https://jekyllrb.com/). This is not meant to be publicly consumed
through Github itself, except perhaps as an example (whether or positive or
negative remains to be seen) of how to use Jekyll.

## Notes on Development

This uses a static site generator called Jekyll. I am using a dev container as
specified under `Dockerfile`, with VS Code as my primary editor. The means by
which I set this up was through [Bill Raymond's tutorial][br] on this subject.
(The tutorial is set up in such a way that it assumes that you are creating a
totally fresh GitHub Pages site, but it is relatively easy to adapt.)

Anyway, if you are starting from a fresh computer:

1. In VS Code, using the Dev Containers extension, then choosing the "Dev
   Containers: Open Folder in Container..." This will process the `Dockerfile`
   and set up the minimal environment. I have not published the image on an
   image repository, in the hopes that gem is semi-reliable.
2. Once that remote is set up, in the VS Code terminal we can use `bundle
   upgrade` and suchlike to make sure everything is properly loaded.
3. Using the script to serve/update a local configuration can be fine. This will
   serve it on (in container) `localhost` on port 4000, which the container is
   configured to expose.

The [Jekyll docs][jekyll-docs] have information on Jekyll itself, with GitHub
Pages specific information [here][gh-pages]. Questions can be posted
[here][jekyll-talk].


# Source

This website has been inspired by, in every meaning of the word, Thomas Finley's personal site.
His website is [Here:][th]


[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
[gh-pages]:    https://docs.github.com/en/pages
[billr]: https://gist.github.com/BillRaymond/db761d6b53dc4a237b095819d33c7332
[th]: https://tfinley.net/
