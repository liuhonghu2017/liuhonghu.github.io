---
layout: page
title: 风格指南
permalink: /styleguide/
---

### 1. 分割线

{% highlight md %}
***
或
---
{% endhighlight %}

***

### 2. 标题
### 默认标题(h3)
# 一级标题(h1)
## 二级标题(h2)
### 三级标题(h3)
#### 四级标题(h4)
##### 五级标题(h5)
###### 六级标题(h6)

{% highlight markdown %}
### 默认标题(h3)
# 一级标题(h1)
## 二级标题(h2)
### 三级标题(h3)
#### 四级标题(h4)
##### 五级标题(h5)
###### 六级标题(h6)
{% endhighlight %}

***

### 3. 列表
#### 有序列表

1. 听君一席话
2. 胜读十年书

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

### 4. 引用

> 我宁愿犯错，也不愿什么都不做。 — 时间刺客 艾克

{% highlight markdown %}
> 我宁愿犯错，也不愿什么都不做。 — 时间刺客 艾克
{% endhighlight %}

***

### 5. 语法高亮显示

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
{% endhighlight %}

***

### 6. 视频

{% highlight html %}
  <iframe src="https://www.youtube.com/" frameborder="0" allowfullscreen></iframe>
{% endhighlight %}

***

### 7. 图片

![]({{site.baseurl}}/images/lang.jpg)

{% highlight markdown %}
  ![]({{site.baseurl}}/images/lang.jpg)
{% endhighlight %}

***

### 8. 结语
*结语*
{% highlight markdown %}
  *结语* 或 _结语_
{% endhighlight %}