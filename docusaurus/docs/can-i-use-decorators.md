---
id: can-i-use-decorators
title: Can I Use Decorators?
---

一些流行的库使用[装饰器](https://medium.com/google-developers/exploring-es7-decorators-76ecb65fb841)在他们的文档中。



Create React App目前故意不支持decorator语法，因为：



-这是一个实验性的提议，可能会改变（事实上，它已经改变过一次，而且还会再次改变）。

-大多数图书馆目前只支持旧版本的提案，这将永远不会成为标准。



然而，在许多情况下，您可以在没有装饰器的情况下重写基于装饰器的代码，并获得相同的结果。



请参考这两个线程以供参考：



- [#214](https://github.com/facebook/create-react-app/issues/214)

- [#411](https://github.com/facebook/create-react-app/issues/411)



当规范进入稳定阶段时，Create React App将添加装饰器支持。
