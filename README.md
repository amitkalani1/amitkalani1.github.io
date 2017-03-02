

- Install [Jekyll](https://jekyllrb.com/) and other dependencies with the command `make install`*

**Note:** If you're not familiar with Jekyll, please read up on [Jekyll's documentation](http://jekyllrb.com/) first.

[Fork this repo](http://github.com/amitkalani1/personal-website/fork), clone it, and then run:

```
bundle install
```

...which installs `github-pages` gem. After that, run the server:

```
jekyll serve --watch
```

Once the server is started,go to [http://localhost:4000](http://localhost:4000

### Required

You should change these files before deploying:

* `_config.yml`: You must change `baseurl`, `url`, and `title`.

If baseurl is set e.g http://localhost:4000/directory, vist [http://localhost:4000/directory](http://localhost:4000/directory) on web browser.

* `CNAME`: Change this to host on a custom domain.
* `_includes/nav.html`: Modify or remove navigation links.
* `_includes/sidebar.html`: Customize the side bar to display about me(If enabled in config)
* `favicon.ico`: Favicon.

### Customize the Theme

To change color theme, edit `_data/theme.yml`.

#### Credits

* [Elle Kasai](http://github.com/ellekasai) - original theme for blogs 

# amitkalani1.github.io
