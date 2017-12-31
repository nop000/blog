---
layout: post
title: Another sample
tags: [jekyll, syntax]
categories:
- blog
---

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
<p>它的步骤如下。</p>
<p>第一步，用户开启双因素认证后，服务器生成一个密钥。</p>
<p>第二步：服务器提示用户扫描二维码（或者使用其他方式），把密钥保存到用户的手机。也就是说，服务器和用户的手机，现在都有了同一把密钥。</p>

<p>中文显示</p>

<p>不在p中的字体<br></p>

<p class="enfont">
Tattooed roof party *vinyl* freegan single-origin coffee wayfarers tousled, umami yr 
meggings hella selvage. Butcher bespoke seitan, cornhole umami gentrify put a bird 
on it occupy trust fund. Umami whatever kitsch, locavore fingerstache Tumblr pork belly
[keffiyeh](#). Chia Echo Park Pitchfork, Blue Bottle [hashtag](#) stumptown skateboard selvage 
mixtape. Echo Park retro butcher banjo cardigan, seitan flannel Brooklyn paleo fixie 
Truffaut. Forage mustache Thundercats next level disrupt. Bicycle rights forage tattooed
chia, **wayfarers** swag raw denim hashtag biodiesel occupy gastropub!
</p>

---

$$
\theta_i = \theta_i - \alpha\frac\partial{\partial\theta_i}J(\theta)
$$

# It's all in the game.

## You come at the king, you best not miss.

### Be subtle with it, man. You know what subtle means?

### 这是几级标题

VHS post-ironic cred **bespoke** banjo. Yr wayfarers literally gentrify, flexitarian fap 
dreamcatcher plaid cornhole Intelligentsia paleo. Beard try-hard direct trade, shabby chic 
Helvetica `look ma, I can code`. Lo-fi American Apparel tattooed [Vice](#) tofu, yr vinyl. 
Williamsburg butcher hella mumblecore fixie mlkshk, cliche wolf keytar mixtape kitsch banh mi 
salvia. High Life Odd Future *chambray* kale chips hoodie, cray pop-up. Helvetica narwhal 
iPhone try-hard jean shorts.

> This is a quote from someone famous about productivity


Syntax highlighting with Solarized theme.

{% highlight ruby %}
class User < ActiveRecord::Base
  attr_accessible :email, :name

  ... tons of other crap ...

end

{% endhighlight %}

{% highlight cpp%}

#include <iostream>
void main()
{
    puts("hello");
}

{% endhighlight %}

``` cpp
#include <iostream>
void main()
{
    puts("hello");
}

//冒泡排序
int *BubbleSort(int *ary, int length)
{
    int i, j, tmp;
    for (i=0; i<length-1; i++)
    {
        tmp = ary[i];
        for (j = length-1; j > i; j--)
        {
            //找到数组中最小的数，并交换
            if (tmp > ary[j])
            {
                ary[i] = ary[j];
                ary[j] = tmp;
                tmp = ary[i];
            }
        }
    }
    return ary;
}
```
* 目录
{:toc}
