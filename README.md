# skia_vs2008
这里是我编译VS2013、VS2012、VS2010、VS2008版本SKia时用到的第三方库。这里我只提交了比较重要的几个文件。要想完全编译SKia还需要自己检出Skia，并且把第三方库拷贝进去

其中**include、src**目录是Skia原文件。src\core目录中附带了VS2008所需要的stdint.h头文件

**third_party\externals**目录是编译VS2008到VS2012版本Skia所需要的第三方库，把这个目录放到你的Skia的对应目录就可以

**out_2008**是我生成好的VS2008的工程文件，可以用来编译

####by:Redrain  2016.4.28**
####QQ:491646717
####blog:[http://blog.csdn.net/zhuhongshu/article/details/51272050](http://blog.csdn.net/zhuhongshu/article/details/51272050)


