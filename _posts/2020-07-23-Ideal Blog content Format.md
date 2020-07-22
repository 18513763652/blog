---
layout:     post                    
title:      Ideal Blog content Format
date:       2020-07-23             
author:     Glenn                     
header-img: img/post-bg-2015.jpg  
catalog: true                      
tags:                              
    博客
---
# Ideal Blog content Format 

## 1. a BGM Music to accmopany you to finish the blog content reading;


<br>1.Code Format:

```
<iframe width="20%" height="100" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/363580526&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/dyallas" title="dyalla" target="_blank" style="color: #cccccc; text-decoration: none;">dyalla</a> · <a href="https://soundcloud.com/dyallas/oh-my-life" title="Oh, My Life" target="_blank" style="color: #cccccc; text-decoration: none;">Oh, My Life</a></div>
```

<br>2. Code exmple:
```
<iframe width="20%" height="100" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/363580526&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
```
<br>3. Look like in the browser:

<iframe width="20%" height="100" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/363580526&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>

<br>4.Reference Link:
<br>Embedding a track or playlist on WordPress
https://help.soundcloud.com/hc/en-us/articles/115003565128-Embedding-a-track-or-playlist-on-WordPress

## 2. Video insert in the middle of the blog content; 

<br>1.Format:
```
<iframe width="1280" height="720" src="https://www.youtube.com/embed/Youtube video key" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```
Youtube video key is the last few digits of the Youtube video link address.
<br>2.Exmple:
```
<iframe width="1280" height="720" src="https://www.youtube.com/embed/_3Jy1wc8pOg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```
<br>3. Looks like in the browser:
<iframe width="1280" height="720" src="https://www.youtube.com/embed/_3Jy1wc8pOg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>4. reference Link:
<br>How to embed a Youtube Video in Markdown presentation
<br>https://www.slideas.app/blog/how-to-embed-a-vimeo-or-youtube-video-in-markdown/

## 3. have certain picture and flow map to help the reader to comprehsion the content.

Location right and left
<img style="float: right;" src="https://avatars2.githubusercontent.com/u/3265208?v=3&s=100">

```
![GitHub](https://avatars2.githubusercontent.com/u/3265208?v=3&s=100 "GitHub,Social Coding")
```

size change
Location Center

image
http://xianbai.me/learn-md/article/syntax/images.html
## 4. add the refrence link at the end of the blog.

## 5. Other issue fix.
The reason why you can not utilize the markdown previw is that you need to set chrome as default browser.
<br>Change Chrome to the Default Web Browser in Mac OS X
<br>https://osxdaily.com/2011/02/23/change-chrome-to-the-default-web-browser/ 

## 6.Put the content into Github blog repositories
1. add the backgroud information into your file.
```
---
layout:     post                    
title:      博客的搭建与搜索框
date:       2017-09-09             
author:     Glen                     
header-img: img/post-bg-2015.jpg  
catalog: true                      
tags:                              
    博客
---
```
2. Rename your title:

```
2017-09-08-博客的搭建与搜索框：.md
```
3. References:
<br>怎样写个人博客
http://glennou.cn/2017/09/08/%E6%80%8E%E6%A0%B7%E5%86%99%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/