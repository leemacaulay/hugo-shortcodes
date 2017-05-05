This is just a collection of extra [Hugo](https://hugodocs.info/) shortcodes that I'm using on my personal blog.

So far, it's just a couple of shortcodes that let you embed a Facebook post or video.

## Documentation

Add both of these html files to either ../layouts/shortcodes/ or /themes/<THEME>/layouts/shortcodes (you might have to create either folder).

{{< facebook-post "POST-PERMALINK-HERE">}} e.g. {{< facebook-post "<https://www.facebook.com/FacebookUK/posts/10155115541856654>">}}

{{< facebook-video "POST-PERMALINK-HERE">}} e.g. {{< facebook-video "<https://www.facebook.com/FacebookUK/videos/10154618133906654>">}}

[More documentation about creating custom permalinks in Hugo.](https://hugodocs.info/templates/shortcode-templates/#creating-custom-shortcodes)
