---
layout: default
title: Home
---

# pages-testing

This site contains various posts and documents, including those with LaTeX-rendered equations.

## Recent Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

## About This Site

This site is generated using [Jekyll](https://jekyllrb.com) and hosted on [GitHub Pages](https://pages.github.com/). It supports LaTeX rendering through MathJax, allowing for the inclusion of complex mathematical equations in the posts.

## Example Equation

Here’s an example of a LaTeX equation rendered using MathJax:

Inline equation: $E = mc^2$

Block equation:

$$
\int_{a}^{b} f(x) \,dx
$$

For more posts, see the list above or navigate to the individual post pages.
