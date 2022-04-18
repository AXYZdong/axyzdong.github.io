## Description
The sources of the GitHub Page are from the [dev-portfolio-blog](https://github.com/rohitjain00/dev-portfolio-blog) repository and the user is Rohit Jain.

Lean more from [Here](https://blog.csdn.net/qq_43328313/article/details/124066785) in the Chinese blog.

## Installation
Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "dev-portfolio-blog"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: dev-portfolio-blog
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install dev-portfolio-blog

## Starting from the beginning:

Assuming that you started your first website based on `minima` theme from [here](https://jekyllrb.com/docs/)

1. Add a `favicon.ico` to the root directory for favicon.

2. Create `blog.md` in the root folder ans set its yaml parameters to

```yaml
layout: blog
permalink: /blog/
title: [Blog Page Title]
pagination:
  enabled: true
```

3. Change your `about.md` yaml parameters to following

```yaml
layout: description
permalink: /about/
title: About
```

3. In the `index.md` file add

```yaml
layout: home
home_text: Text
title: [Home Page Title]
```

4. Create a new `categories.md` file in root with following yaml parameters
```yaml
layout: categories
permalink: /categories/
title: Categories
```

5. In the `_config.yml` file add following and change accordingly

Path is relative to the root directory
```yaml
resume_url: [PATH_TO_RESUME]
author_name: [YOUR_NAME]
description: [SITE_DESCRIPTION]
url: [WEBSITE_URL]
google_analytics: '[google analytics Id]'
disqus:
    shortname: [discus-shotname]
```

## Troubleshooting

- ` Could not find a JavaScript runtime. See https://github.com/rails/execjs for a list of available runtimes`
   Node JS is missing from your system. In ubuntu install using `sudo apt-get install nodejs` or refer to [this](https://stackoverflow.com/questions/9202324/execjs-could-not-find-a-javascript-runtime-but-execjs-and-therubyracer-are-in)
- `assets/css/styles.scss'`
 Refer to [here](https://github.com/rohitjain00/dev-portfolio-blog/issues/44) or see the image below.

![image](https://user-images.githubusercontent.com/45477220/162579147-601ec4e7-77fb-49e6-b6b7-97bf144e02a1.png)


## Reference

Most of the contents cite from this link: [https://github.com/rohitjain00/dev-portfolio-blog](https://github.com/rohitjain00/dev-portfolio-blog)


## License
[![License: MIT](https://img.shields.io/github/license/axyzdong/axyzdong.github.io)](https://opensource.org/licenses/MIT)

