python中的编码问题：
===
  1.python程序文件的编码
  2.python程序IDE的编码
  3.python读取外部文件，网页的编码
 
 1.程序文件开头第二行一般会嵌入 ‘#-*-conding：utf-8-*-’,python解释器按utf8读取源码。[参考廖大博客](https://www.liaoxuefeng.com/wiki/001374738125095c955c1e6d8bb493182103fac9270762a000/001386819196283586a37629844456ca7e5a7faa9b94ee8000)
 python2支持Unicode字符串通过u'...'表示。一个中文字符通过encode('utf-8')后转换成三个utf-8字符，例如：
