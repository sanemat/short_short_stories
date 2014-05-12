---
layout: post
title: "Rails 5.days.ago"
date: 2014-05-13T02:10:38+09:00
---

自分自身を返すのではない、メソッドチェーン、(自分のjavascriptコードではよくやってしまう) e.g. `messages.map(function(message) { return message.id })` みたいなのよく書けた気がしてついやっちゃうんだけどやっぱり気持ち悪い。

```ruby
> 5 #=> 5 # ふつう
> 5.class #=> Fixnum
> 5.days #=> 432000 # わかる
> 5.days.class #=> Fixnum
> 5.days.ago #=> Thu, 08 May 2014 02:16:41 JST +09:00 # ??!!??
> 5.days.ago.class #=> ActiveSupport::TimeWithZone
```

はい。
