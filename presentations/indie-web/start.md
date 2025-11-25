[back](better) [top](.) [next](demo)

---

# How To Start?

To start making your own web-site, you just need 2-3 things:
- [Hosting](#hosting) \[free\]
- [Layout & Style](#layout--style) \[free\]
- (optional) [Custom domain](#custom-domain) \[$$\]
- (later) [Static-Site Generator](#static-site-generator) \[free\]

### Hosting

Place where you can store your website so that people can find it.
There's endless options on the internet, most of them paid (around 5-10$/month), but there are free options. 
Here's a couple I know about & trust:

- [Neocities](https://neocities.org/)
    - Most popular free hosting option 1GB free storage (more than enough if you don't plan to host audio/video)
    - A spiritual successor to Geocities
- [Nekoweb](https://nekoweb.org/)
    - In similar vein, 500MB free storage, supports any file types
- [GitHub](https://github.com) Pages
    - Requires some technical setup
    - Unlimited storage
    - Comes with built-in static site generator - Jekyll
    - Microsoft will likely train AI on your code

### Layout & Style

<span style="background: white; color: black; font-family:'Times New Roman'">Unless you want plain black Times New Roman on white background…</span>
You are going to need some sort of layout & theme. These usually consist of a:
- `HTML` template that dictates the structure/layout
- `CSS` stylesheet that dictates colors, fonts, highlights, etc.

And for more advanced "scripting" behaviour you might need some `JavaScript`, but you can do perfectly well without it.

Once you know what you are doing, it's not that hard to make something of your own. 
But to get started, it's probably a good idea to get some help & use an available theme. There's plenty of people making their layouts, stylesheets & themes available.

Here's some examples:

- [ribozone](https://ribo.zone/free/layouts/)'s layouts
- [itinerae](https://itinerae.blogspot.com/2024/01/foryou.html)'s themes
- [Petrapixel's Layout Generator](https://petrapixel.neocities.org/layout-generator/)

You can also inspect the code of most websites, learn how they did what they did, and copy them.

### Custom Domain

Now depending on what kind of hosting you are using, this one is completely optional, but if you want a nice domain name without any suffixes, like `*.neocities.org`, you might want to consider buying a domain name.
They'll run you somewhere around 12$ a year, so not a huge investment, but also not free.

Also, watch out for first year discounts — some registrars make the first year very cheap, but then bump the price 3 to 5 times!

### Static-Site Generator

If you plan to write a lot of articles on your site & don't want to always copy your templates, a static-site generator might be a good option for you.
It requires some technical setup, but most of them come with pretty good tutorials. Here's a couple I've tried & recommend:

- [Jekyll](https://jekyllrb.com/)
    - Most popular option for a while, built-into GitHub Pages, so you technically don't need to set it up there
    - This site runs on it
- [Hugo](https://gohugo.io/)
    - A newer option on the block, more flexible than Jekyll, built-in RSS feed, solid templates

A static-site generator takes a template & applies it to your content, so you can write it in Markdown or similar markup language & not have to worry about form.
Then, it creates all of the necessary `HTML` & `CSS` files, which you can just copy & upload to your hosting. 

And voilá, you have a site!

[Let's see it in action!](/indie-web-demo)