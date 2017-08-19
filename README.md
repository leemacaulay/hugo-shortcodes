This is just a collection of extra [Hugo](https://hugodocs.info/) shortcodes that I'm using on my personal blog.

So far, one shortcode allows you to embed Facebook posts or videos while the other lets you embed Radiopublic podcast series or individual episodes

## Documentation

Add both of these html files to either ../layouts/shortcodes/ or /themes/<THEME>/layouts/shortcodes (you might have to create either folder).

Then add these shortcodes to posts or pages where you want to embed a post or video:
```
{{< facebook-post "POST-PERMALINK-HERE">}} e.g.   
{{< facebook-post "https://www.facebook.com/FacebookUK/posts/10155115541856654">}}

{{< facebook-video "POST-PERMALINK-HERE">}} e.g.   
{{< facebook-video "https://www.facebook.com/FacebookUK/videos/10154618133906654">}}

{{ radiopublic "PODCAST-NAME" (https://play.radiopublic.com/PODCAST-NAME) e.g.
{{ radiopublic "reply-all-OWdvQ8" }}

{{ radiopublic "PODCAST-NAME" "EPISODE" (https://play.radiopublic.com/PODCAST-NAME/ep/EPISODE) e.g.
{{ radiopublic "reply-all-OWdvQ8" "s1!e67733e9c533ed2282d924d2b25993fb6802b4fe" }}
```

[More documentation about creating custom permalinks in Hugo.](https://hugodocs.info/templates/shortcode-templates/#creating-custom-shortcodes)
