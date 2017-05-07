---
layout: post
title:  "JeKyll安裝在GitHub Pages"
date:   2017-05-07
category: web
tags: [github, jekyll]
---

<p>之前想試很久，今天終於有空來試一下，也還是耗了不少時間</p>
<p>首先，先上Github申請跟自己帳號名一樣的網頁空間
<a href="https://pages.github.com/">GitHub Pages</a>
有基本公版可以套用，不過我們怎麼可以屈就於小小的公板呢。</p>
<p>為了套用別的主題，就要用<a href="https://jekyllrb.com/">Jekyll</a>來套版型。</p>
<p>不過還有比較簡單的方法，就是直接先搜尋Jekyll Theme，用步驟來說明一下</p>
<ol>
  <li>到theme的github網頁去fork回來到自己的帳號</li>
  <li>然後git clone回來自己電腦</li>
  <li>記得要$bundle</li>
  <li>看提示，我之前有遇到錯誤，叫我安裝 jekyll-paginate</li>
  <li>記得在_config.yml 裡面打上這個就好 gems: [jekyll-paginate]</li>
  <li>執行 $jekyll serve啟動伺服器</li>
  <li>試試<a href="http://127.0.0.1:4000/">http://127.0.0.1:4000/</a></li>
</ol>
<img src="{{ '/assets/img/jekyll1.png' | prepend: site.baseurl }}" alt="">
