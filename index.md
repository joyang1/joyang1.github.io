## 前言

Tommy 的 Blog 就这么开通了。

[跳过废话，直接看技术实现 ](#build) 



2015 年，Tommy 总算有个地方可以好好写点东西了。


作为一个程序员， Blog 这种轮子要是挂在大众博客程序上就太没意思了。一是觉得大部分 Blog 服务都太丑，二是觉得不能随便定制不好玩。之前因为太懒没有折腾，结果就一直连个写 Blog 的地儿都没有。

在玩了一段时间知乎之后，答题的快感又激起了我开博客的冲动。之前的博客(http://www.cnblogs.com/joyang)是在博客园，感觉这个总好像不是自己的一样。于是，一不做二不休，花一天搞一个吧！


<p id = "build"></p>
---

## 正文

接下来说说搭建这个博客的技术细节。  

正好之前就有关注过 [GitHub Pages](https://pages.github.com/) + [Jekyll](http://jekyllrb.com/) 快速 Building Blog 的技术方案，非常轻松时尚。

其优点非常明显：

* **Markdown** 带来的优雅写作体验
* 非常熟悉的 Git workflow ，**Git Commit 即 Blog Post**
* 利用 GitHub Pages 的域名和免费无限空间，不用自己折腾主机
	* 如果需要自定义域名，也只需要简单改改 DNS 加个 CNAME 就好了 
* Jekyll 的自定制非常容易，基本就是个模版引擎



---

配置的过程中也没遇到什么坑，基本就是 Git 的流程，相当顺手

大的 Jekyll 主题上直接 fork 了 Clean Blog（这个主题也相当有名，就不多赘述了。唯一的缺点大概就是没有标签支持，于是fork了huxpro.github.io这个项目。）

结合这两个项目搭建好了自己的博客。


## 后记

回顾这个博客的诞生，纯粹是出于个人兴趣。然后希望能有一个自己的博客，于是就在利用GitHub Pages和Jekyll自制了自己博客。这个博客的诞生还是需要感谢
GitHub提供这么好的平台以及上面开源项目:Clean Blog和huxpro.github.io。



—— Tommy 后记于 2015.10