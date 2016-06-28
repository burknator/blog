---
layout: post
title:  "Welcome to Jekyll!"
date:   2016-06-28 20:27:55 +0200
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most {% ihighlight python %} from random import random {% endihighlight %} common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

{% asset_path my-image.png %}
in post 2013-01-01-post-title would output:

/assets/posts/post-title/my-image.png
in page my-first-page would output:

/assets/my-first-page/my-image.png

YouTube:
{% youtube kdjfkjdsh 200 400 %}

<p>This article will take {{ content | reading_time | pluralize: "minute" }} to read.</p>

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
