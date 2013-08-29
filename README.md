# Online XSLT Service

これはHeroku上で[W3C XSLT Servlet](http://www.w3.org/2005/08/online_xslt/)を動作させるアプリケーションとなっております。W3Cによって配布されているJARをそのまま使用しており、W3C XSLT Servletとの動作差異は存在していないはずです。

## 使い方

```shell
$ git clone https://github.com/ykzts/online-xslt-service.git
$ cd ./online-xslt-service
$ heroku create
$ git push heroku master
$ heroku open
```

## ライセンス

### SaxonSavvyServlet.java

- [W3C XSLT Servlet](http://www.w3.org/2005/08/online_xslt/)
- [W3C Software Notice and License](http://www.w3.org/Consortium/Legal/2002/copyright-software-20021231)
