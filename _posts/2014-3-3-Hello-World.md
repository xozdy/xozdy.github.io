---
layout: post
title: SPOJ / TEST
published: true
---

## 1. Life, the Universe, and Everything

## Problem code: TEST

Your program is to use the brute-force approach in order to find the Answer to Life, the Universe, and Everything. More precisely... rewrite small numbers from input to output. Stop processing input after reading in the number 42. All numbers at input are integers of one or two digits.

## Solution

It is dangerous to use C.

{% highlight python %}
a=[];
while True:
    x=int(raw_input(""));
    if x!=42:
        a.append(x);
    else:
        break;
for x in a:
    print x;
{% endhighlight %}

And that concludes my glorius markdown test!