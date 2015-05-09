# Some of my own [Jekyll](http://jekyllrb.com/) plugins

## Installation

Clone this repo and move the files into your jekyll `_plugin` folder. If it does not exist, then create one

## Usage

### remote_file_content

Perfect for fetching the file content from a github repository, without any usage of additional javascript. E.x.

```
{% highlight javascript tabsize=4 %}
{% remote_file_content https://raw.githubusercontent.com/dimitri-koenig/jekyll-gulp-optimizations/master/gulpfile.js %}
{% endhighlight %}
```

[Live demo](https://www.dimitrikoenig.net/scoring-100-on-googles-pagespeed-insights.html)