# htmlstudy  
## 学习来源 [菜鸟教程](https://www.runoob.com/html/html-tutorial.html)
## 学习中遇到的一些小问题  
- vscode如何自动保存[1](https://blog.csdn.net/m0_46374969/article/details/119008644#:~:text=VSCode%20%E7%BC%96%E8%BE%91%20%E4%BB%A3%E7%A0%81%20%E9%BB%98%E8%AE%A4%E4%B8%8D%E4%BC%9A%20%E8%87%AA%E5%8A%A8%E4%BF%9D%E5%AD%98%20%EF%BC%8C%E9%9C%80%E6%89%8B%E5%8A%A8%E6%8C%89%60Ctr%2BS%60%E4%BF%9D%E5%AD%98,%E4%BB%A3%E7%A0%81%20%EF%BC%8C%E9%95%BF%E6%97%B6%E9%97%B4%E7%BC%96%E8%BE%91%20%E4%BB%A3%E7%A0%81%20%E6%B2%A1%E4%BF%9D%E5%AD%98%E5%8F%AF%E8%83%BD%E4%BC%9A%E5%AF%BC%E8%87%B4%20%E4%BB%A3%E7%A0%81%20%E6%84%8F%E5%A4%96%E4%B8%A2%E5%A4%B1%E3%80%82)
- open browser failed [2](https://blog.csdn.net/m0_46374969/article/details/119008644#:~:text=VSCode%20%E7%BC%96%E8%BE%91%20%E4%BB%A3%E7%A0%81%20%E9%BB%98%E8%AE%A4%E4%B8%8D%E4%BC%9A%20%E8%87%AA%E5%8A%A8%E4%BF%9D%E5%AD%98%20%EF%BC%8C%E9%9C%80%E6%89%8B%E5%8A%A8%E6%8C%89%60Ctr%2BS%60%E4%BF%9D%E5%AD%98,%E4%BB%A3%E7%A0%81%20%EF%BC%8C%E9%95%BF%E6%97%B6%E9%97%B4%E7%BC%96%E8%BE%91%20%E4%BB%A3%E7%A0%81%20%E6%B2%A1%E4%BF%9D%E5%AD%98%E5%8F%AF%E8%83%BD%E4%BC%9A%E5%AF%BC%E8%87%B4%20%E4%BB%A3%E7%A0%81%20%E6%84%8F%E5%A4%96%E4%B8%A2%E5%A4%B1%E3%80%82) 原因：版本不兼容 ； 解决办法：安装v1.1.0  
- 怎么添加图片啊？？！哦我会了  
- markdown和html为什么不能混用啊？  
- id,script等标签一些详细的都是些什么啊？看不懂啊QAQ  
## markdown和HTML对比  
- 脚注  
-- 创建脚注格式类似这样 [^RUNOOB]  
[^RUNOOB]: 菜鸟教程 -- 学的不仅是技术，更是梦想！！！  
-- <!-- 这是一个注释，不会显示在页面上 -->  
- 分割线  
-- ***  
-- <hr/>  
- 文本格式化  
-- *斜体*    —斜体—    **粗体**    ***粗斜体***  
-- <b>加粗</b> <i>斜体</i> <strong>加粗</strong> <em>斜体</em>  
-- <big>放大</big> <small>缩小</small> <sub>下标</sub><sup>上标</sup>  
- 删除和下划线  
-- ~~BAIDU.COM~~ <u>下划线</u> (?)    
-- <del>blue</del> <ins>red</ins> 

## 特有  
### <a id="语法">语法</a>
- html中浏览器忽略了源代码中的排版（省略了多余的空格和换行）  
- 换行 <br/>  
- 定义文字方向  
-- <p>该段落文字从左到右显示。</p> <p><bdo dir="rtl">该段落文字从右到左显示。</bdo></p> <!--direction : right to left -->  
- adress  
-- <adress>位于body或者title都表示文档作者或所有者联系信息</adress>  
- abbr  
-- The<abbr title="World Health Organization">WHO</abbr> was founded in 1948.  
- 长引用blockqoute和短引用q  
-- <blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature. The worlds leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally.</blockquote> <br/><q>Build a future where people live in harmony with nature.</q>  
- 链接  
-- <a href="https://www.runoob.com/" target="_blank">访问菜鸟教程!</a><br/><p>如果你将 target 属性设置为 &quot;_blank&quot;, 链接将在新窗口打开。</p><br/><a href="https://www.runoob.com/" target="_blank">访问菜鸟教程!</a>  
<!--后面最好加上：rel="noopener noreferrer" 意思是不会打开其他的网站，因为恶意病毒可能会修改你的浏览器空白页地址-->
- 在当前页面跳到指定位置  
- <a href="#语法">查看语法</a>  
- 图片链接  
-- <p>无边框的图片链接:<a href="http://www.runoob.com/html/html-tutorial.html"><img border="0" src="smiley.gif" alt="HTML 教程" width="20" height="16"></a></p>  
- 电子邮件链接  
-- <p>这是一个电子邮件链接：<a href="mailto:someone@example.com?Subject=Hello%20again" target="_top">发送邮件</a></p> <p><b>注意:</b> 单词之间空格使用 %20 代替，以确保浏览器可以正常显示文本。</p>  
- 头部  
-- base元素，描述了基本的链接地址/链接目标，该标签作为HTML文档中所有的链接标签的默认链接  
-- meta标签提供了 HTML 文档的元数据metadata。元数据不会显示在客户端，但是会被浏览器解析。meta元素通常用于指定网页的描述，关键词，文件的最后修改时间，作者及其他元数据。元数据通常以 名称/值 对出现。  
-- script 标签用于定义客户端脚本，比如 JavaScript。元素既可包含脚本语句，也可以通过 "src" 属性指向外部脚本文件。  
- CSS
-- Cascading Style Sheets 用于渲染HTML元素标签的样式。  
-- CSS修饰标签的样式，有 "内联"（在HTML元素中使用"style" 属性） 和 "外引"（使用外部 CSS 文件） 两种方式。外引较好。当单个文件需要特别样式时，就可以使用内部样式表。可以在<head> 部分通过 <style>标签定义内部样式表  
-- font-family,font-size,color,background-color,text-align...  
- 图像 
-- 图像映像，创建带有可供点击区域的图像地图。其中的每个区域都是一个超级链接。  
-- <a href="https://postimg.cc/vcxkhCKC"><img border="0" src="https://i.postimg.cc/QxfD83JN/2022-12-31-232601.png" alt="map格式" width="700" height="300"></a>
### 类似标准格式？  
- <a href="https://postimg.cc/jWqjKJSP"><img border="0" src="https://i.postimg.cc/QM1KQQL4/I-NM-F-8-KT7-B53-A-WIF.png" alt="标准格式" width="500" height="350"></a>  
  
