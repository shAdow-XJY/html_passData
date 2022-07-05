# html_passData

## website
  [https://shadowplusing.website/html_passData/](https://shadowplusing.website/html_passData/)
## introduction

  练习主要由HTML构成的页面的不同传参方法，写一个demo记录下，方便以后回顾。

## GitHub pages

  记录一下，部署到pages时，第一次只能打开第一个页面，以为是只有纯HTML页面问题，结果发现是部署到访问需要一段时间（不是404到可以打开的时间，而是可以访问index.html了可能也需要一段时间正常跳转）

## content

1. pageOne_1.html + pageOne_2.html : window.location.href + window.location.search
2. pageTwo_1.html + pageTwo_2.html : window.open + window.document.URL
3. pageThree_1.html + pageThree_2.html : jQuery $.cookie
4. pageFour_1.html + pageFour_2.html : window.open + window.opener
5. pageFive_1.html + pageFive_2.html : document.cookie 
6. pageSeven_01_Parent.html + pageFive_01_Child.html : iframe(parent:function(set) + iframe:window.parent.function) 获取iframe参数
7. pageSeven_02_Parent.html + pageFive_02_Child.html : iframe(parent:function(return) + iframe:window.parent.function) 传递iframe参数
8. pageEight.html : iframe跨域( ① src URL ② postMessage(data,origin))
9. 

## reference

1. [HTML页面之间如何传递数据，超简单，一看就会！](https://blog.csdn.net/qq_45850095/article/details/117758342)
2. [通过window.opener在页面之间传递对象参数](https://blog.csdn.net/weixin_34218579/article/details/92464116)
3. [Cookie的设置和获取](https://blog.csdn.net/u010081518/article/details/78800823)
4. [html之间传值之localStorage](https://blog.csdn.net/Leo_01169/article/details/86713654)
5. [关于使用iframe的父子页面进行简单的相互传值](https://www.cnblogs.com/zhongxiaoyou/p/11344939.html)
6. [iframe跨域传值](https://blog.csdn.net/qq_40591925/article/details/125385115)

## some function

1. [document.getElementsByTagName(tagname)](https://www.w3school.com.cn/jsref/met_doc_getelementsbytagname.asp)
2. [getElementsByName()](https://www.w3school.com.cn/jsref/met_doc_getelementsbyname.asp)
3. [getElementById()](https://www.w3school.com.cn/jsref/met_doc_getelementbyid.asp)
4. [stringObject.indexOf(searchvalue,fromindex)](https://www.w3school.com.cn/jsref/jsref_indexOf.asp)
