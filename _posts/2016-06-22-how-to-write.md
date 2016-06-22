---
layout: post
title: 这只是一个测试，你好
date: 2016-06-22
categories: blog
tags: [test]
description: 我不知道今天忙了些什么如果有人能看到真的是太好了
---

##初心
昨天晚上就有一个念头，希望有一个自己的技术博客，虽然自己以前不怎么喜欢写博客，但是现在发现有一个历史的记录还是很有必要的。所以今天开始了！
{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}