FFmpeg Tutorial CN
===========

如何用FFmpeg编写一个简单播放器

An ffmpeg and SDL Tutorial

or

How to Write a Video Player in Less Than 1000 Lines

----------

教程英文原文由[Stephen Dranger](dranger@gmail.com)写成，并发布在 http://dranger.com/ffmpeg/ffmpeg.html  ，中文版原始翻译出处不详，本文档参考百度文库中的[翻译版本](http://wenku.baidu.com/view/2a30ffef0975f46527d3e1ac.html)及部分其它译本进行校正和重排。正如原文作者在教程开始部分指出的，教程中有些内容已经过时了，教程提供的代码中使用的API 有些已经被FFmpeg 废弃了。不过好在有开发者[更新教程的代码](https://github.com/chelyaev/ffmpeg-tutorial)到比较新的FFmpeg版本（ffmpeg version N-50314-gf6fff8e），因此文章作为开发者的入门教程还是很有参考价值。

本文档LaTeX源码和PDF文档发布在Github：https://github.com/huwan/FFmpeg-Tutorial-CN ，你可以在这里获取最新更新，如果有发现文字或翻译错误，请提交到[FFmpeg-Tutorial-CN/issues](https://github.com/huwan/FFmpeg-Tutorial-CN/issues) 。


原文的版权声明：

> This work is licensed under the Creative Commons Attribution-Share Alike 2.5 License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/2.5/ or send a letter to Creative Commons, 543 Howard Street, 5th Floor, San Francisco, California, 94105, USA.

> Code examples are based off of FFplay, Copyright (c) 2003 Fabrice Bellard, and a tutorial by Martin Bohme.
