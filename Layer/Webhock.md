


## what's webhock

<a href="https://sendgrid.com/blog/whats-webhook/">What's a Webhock?</a>

<a href="https://qiita.com/soarflat/items/ed970f6dc59b2ab76169">Webhockとは？</a>

<a href="https://kintone-blog.cybozu.co.jp/developer/000283.html">Webhookって何？を子どもでもわかるように描いてみた</a>



## multipart/from-data　とは？

- [ ] <a href="https://www.yoheim.net/blog.php?q=20171201">multipart/from-dataとは?</a>


#### 翻訳

webhockは近年人気が高まっているAPIの概念です。<br>
Webhockとは、Webアプリケーションでイベントが実行された際、外部サービスにHTTPで通知する仕組みです。<br>


正確にwebhockとはどんなものなの？<br>
webhock(webcallbackやHTTP push APIとも呼ばれています)は、たくさんのアプリにリアルな時間に情報を提供します。<br>
webhockは、様々なアプリケーションに情報を提供します、それはあなたがすぐに情報を得ることを意味しています。<br>
一般的な頻繁にポーリングする必要があるapiと違って、リアルタイムのデータを取得することができます。<br>
これが意味することは、webhockは情報提供者と消費者にとってとても効率的です。<br>


![md](../../img/webhock.jpg)



## Consuming a Webhock

webhockを利用する一番最初のステップは、webhockプロバイダーにurlを運ばせることです。<br>
これはほとんどの場合、バックエンdpパネルかAPIを通して行われます<br>
つまり、あなたはあなたのアプリにパブリックウェブから可能なURLも設定する必要があるということです。<br>

<br>

webhockの大部分は、jsonあるいはxmlとして読み取られるか、またはフォームデータとして(（application / x-www-form-urlencodedまたはmultipart / form-data）の2つの方法でデータをPOSTします。<br>



## Debugging a Webhock


webhockは主に非同期であるため、webhockのデバックは複雑になることがあります。<br>
したがって、どのような原因でデバックの応答を確認する必要があります。<br>
これは面倒でもあり、かなり非効率的です。幸運にも良い方法があります。<br>
webhockのデバックに関するドキュメンデーションページでそれらの多くを調べてみてください。<br>
しかし、結局は以下が原因となります。<br>

1. 





























