---
layout: page
title: 风格指南
permalink: /styleguide/
---

普通文本.

***

### 默认标题

# 默认标题
## 默认标题
### 默认标题
#### 默认标题
##### 默认标题
###### 默认标题

{% highlight markdown %}
# 默认标题
## 默认标题
### 默认标题
#### 默认标题
##### 默认标题
###### 默认标题
{% endhighlight %}

***

### 列表

#### 有序列表

1. 听君一席话
2. 胜读十年书

***

#### 无序列表

* 听君一席话
* 胜读十年书

{% highlight markdown %}
1. 有序列表文本 1
2. 有序列表文本 2

* 无序列表文本 1
* 无序列表文本 2
{% endhighlight %}

***

### 引用

> 我宁愿犯错，也不愿什么都不做。 — 时间刺客 艾克

***

### 语法高亮显示

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
{% endhighlight %}

***

### 视频

<iframe src="https://www.youtube.com/" frameborder="0" allowfullscreen></iframe>

{% highlight html %}
  <iframe src="https://www.youtube.com/" frameborder="0" allowfullscreen></iframe>
{% endhighlight %}

***

### 图片

![]({{site.baseurl}}/images/lang.jpg)

{% highlight markdown %}
  ![]({{site.baseurl}}/images/lang.jpg)
{% endhighlight %}

*结语*

***