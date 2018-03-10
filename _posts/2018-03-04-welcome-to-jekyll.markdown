---
layout: post
title:  "Welcome to Jekyll!"
date:   2018-03-04 15:09:03 +0900
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Test
$$
\begin{align*}
0&=\langle\phi|\mathcal{H}(a^{+},a)e^{ca^{+}}|0\rangle\\
&=\langle\phi|e^{ca^{+}}\mathcal{H}(a^{+},a+c)|0\rangle\\
&=e^{c\phi^*}\langle\phi|\mathcal{H}(a^{+},a+c)|0\rangle\\
&=e^{c\phi^*}\langle\phi|\mathcal{H}(\phi^*,c)|0\rangle\\
&=e^{c\phi^*}\mathcal{H}(\phi^*,c)\langle\phi|0\rangle\\
\therefore 0&=\mathcal{H}(\phi^*,c),\forall~\phi\in\mathbb{C}.
\end{align*}
$$

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

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
