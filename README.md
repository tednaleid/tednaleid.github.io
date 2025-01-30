Quick repo for creating a blog with Jekyll on GitHub Pages.

If you create a repo called `your-username.github.io`, it will automatically setup github actions to build and deploy your blog to `https://your-username.github.io`.


It's using the [Mimima](https://github.com/jekyll/minima) theme.  If you want to override files in that theme, you can copy them from that repo and put them in this repo at the same path.

As an example, I've got `_layouts/post.html` as a copied file from [the minima _layouts/post.html](https://github.com/jekyll/minima/blob/master/_layouts/post.html) file.  You can delete this file if you want the one from the base theme, it's just an example.

The theme can ge changed by changing the `remote_theme` line in `_config.yml`.