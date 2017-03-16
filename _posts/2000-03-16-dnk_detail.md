---
layout: post
title: "회사 홈페이지"
date: 2011-11-01
categories:
  - Homepage
  - Design
  - FrontEnd
  - Html,Css
image: https://kjuhee0712.github.io/images/pages/20111101_bs.jpg
image-sm: https://kjuhee0712.github.io/images/thumbs/20111101_bs.jpg
---

<ul class="inform">
  <li class="preview__date" itemprop="datePublished" datetime="{{ page.date | date_to_xmlschema }}">- 작업기간 : {{ page.date | date: "%Y년 %-m월부터 약 %-d개월 이내" }}</li>
  <li class="preview__catetory" itemprop="catetory">- 작업 내용 :
    {% for categories in page.categories %}
           <a href="/category/{{ categories }}/">#{{ categories }}</a>     
        {% endfor %}</li>
</ul>

![친절한 스크린샷]({{ site.url }}/images/test/top.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/brandstory.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/01.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/02.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/03.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/04.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/05.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/06.gif)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/07.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/08.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/09.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/10.gif)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/11.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/TSAlock.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/quality_gif.gif)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/quality.jpg)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/quality_img.gif)
![친절한 스크린샷]({{ site.url }}/images/test/newf107/inform.jpg)

