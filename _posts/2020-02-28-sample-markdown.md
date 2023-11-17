---
layout: post
title: ???  버튜버의 시대가 오겠어요?
subtitle: 설마요~
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
thumbnail-img: 0000.jpg
tags: [test]
comments: true
author: 또 누군가
---

## 그녀들의 이야기

![](/0000.jpg){: .mx-auto.d-block :}

버튜버의 시대가 오겠어요?



![](/0001.jpg){: .mx-auto.d-block :}

아 오지요. 100% 오지요. 그거는 반드시 올 수밖에 없죠.



![](/0002.jpg){: .mx-auto.d-block :}

근데, 그런 시대가 오면 나는 없을것 같아요.



![](/0003.gif){: .mx-auto.d-block :}

... 그럴수는 있죠.



![](/0004.jpg){: .mx-auto.d-block :}

오야붕님은 첫 물결이세요.



![](/0005.jpg){: .mx-auto.d-block :}
![](/0006.jpg){: .mx-auto.d-block :}

새로운 파도가 밀려 오는데 그 첫 파도에 타신 분 같아요, 제가 보기에는.



![](/0007.gif){: .mx-auto.d-block :}

그런데 이 첫 파도가 가려고 하는 데까지 바로 갈 수도 있지만



![](/0008.gif){: .mx-auto.d-block :}

...이 파도가 못 가도...



![](/0009.gif){: .mx-auto.d-block :}

그 다음 파도가 오고...



![](/0010.jpg){: .mx-auto.d-block :}
![](/0011.gif){: .mx-auto.d-block :}
![](/0012.gif){: .mx-auto.d-block :}

...그 다음 파도가 와서...



![](/0013.gif){: .mx-auto.d-block :}
![](/0014.gif){: .mx-auto.d-block :}
![](/0015.gif){: .mx-auto.d-block :}

...여러 차례 밀려온다면...



![](/0016.jpg){: .mx-auto.d-block :}

거기 갈 수는 있겠죠.

그러니까 그런 면에서 보면...




![](/0017.gif){: .mx-auto.d-block :}
![](/0018.gif){: .mx-auto.d-block :}
![](/0019.gif){: .mx-auto.d-block :}

새로운 시대정신과....








Here's a table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
