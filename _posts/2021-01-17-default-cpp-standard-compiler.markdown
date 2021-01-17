---
layout: post
title:  "Default C++ Standard of the Compiler"
date:   2021-01-17 20:28:00 +0100
categories: software
---
How to determine what C++ standard is the default for a C++ compiler?

{% highlight bash %}
g++ -x c++  -E -dM -< /dev/null | grep __cplusplus [1]
{% endhighlight %}

[1] <https://stackoverflow.com/a/56429861/15018495>