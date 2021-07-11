---
title: "PETAL"
date: 2018-11-28T15:15:34+10:00
featured: true
draft: false
weight: 1
---
![Accounting Services](/images/post/LiveView-dockyard.png)

## **PETAL –エンドツーエンドのWebスタック**  
  
ウェブアプリケーションを構築を強力にサポートします。
最初に、以下の二つのサイトを紹介します。
1. [任天堂 NPNS における Erlang/OTP](https://voluntas.medium.com/npns-%E3%81%AB%E3%81%8A%E3%81%91%E3%82%8B-erlang-otp-548d91cb6deb)
2. [Nervesが開拓する「ElixirでIoT」の新世界](https://www.slideshare.net/takasehideki/nerveselixiriot?qid=47e59a65-c24f-4674-a79f-d6a82b4320d2&v=&b=&from_search=6)

- Phoenix
- Elixir
- Tailwind
- Alpine
- LiveView

**「P」**  
Railsの考えを取り入れたWebフレームワークである**Phoenix**を取り上げます。Phoenixは、開発者のエクスペリエンスと生産性に同じように焦点を当てており、Djangoよりも強力で明確だと思います。

**「E」**  
Elixirを開発したジョゼ・バリム（José Valim）は、Ruby on Railsのコミッタだったこともあり、Rubyに似た構文でErlangの長所を備えた言語として、Elixirを開発したと言われています。

ジョゼはさらに、パイプ演算子、メタプログラミングのためのマクロなど、主にWebアプリケーションの開発で生産性に寄与するさまざまな機能を、Elixirに取り入れました。その結果、Erlangの堅牢性や並行性に魅力を感じながらも採用に踏み切れないでいた開発の現場でも、Elixirは広く受け入れられるようになります。

ErlangのVM上で動作することから、Elixirには次のような特徴が備わっています。

- 耐障害性
- 高可用性
- 分散アプリケーションの構築のしやすさ

**「T」**  

Tailwind CSSは、人気のあるCSSフレームワークです。Phoenix、Elixir、Tailwind CSS、Alpine.js、LiveViewの組み合わせは、素晴らしいです。  

**「A」**  

Alpine.jsは、厳密にクライアント側の対話性が必要な場合にうまく機能するように構築されています。ほとんど邪魔にならないようにしながら、バニラJavaScriptよりも便利な機能を提供します。LiveView + Alpine.jsについて取り上げている[DockYard](https://dockyard.com/blog/2020/12/21/optimizing-user-experience-with-liveview)の記事を紹介します。

**「L」**  

LiveView。これがこのstackショーのスターです。PhoenixWebフレームワークのますます重要でありながらオプションの部分です。

ほとんどのユースケースでフロントエンドJSを作成しなくても、非常に効率的なリアルタイムの対話性とUIが可能になります。このアイデアは完全に新しいものではありませんが、Elixir / ErlangとBEAMはアクターモデルに基づいており、メモリ内の状態、イベント、メッセージパッシングを管理するための強力な機能を備えているため、実際の実装は非常に優れています。これは、双方向性を構築するための非常に満足のいく生産的な方法です。

つまり、基本的にはサーバー側のレンダリング（SSR）と、更新されたパーツをWebSocket接続を介して出荷することです。
SPAを構築することは、多くのユースケースにとって非常に手間がかかりますが、このstackを使うと生産性がとてもあがります。

### Technologyでもリンクを表示してます。  
わくわくする内容ですね。

1. [PETAL stack](https://changelog.com/posts/petal-the-end-to-end-web-stack)  
2. [TAPE stack](http://tapestack.party/)  
3. [Phoenix 高速Webアプリ](https://www.slideshare.net/piacere_ex/elixir3phoenixweb-rest-api-75571536)  
4. [Elixir + Phoenix FrameworkでWebアプリケーション](https://www.casleyconsulting.co.jp/blog/engineer/241/)  
5. [Phoenix入門](https://qiita.com/tmaeda/items/e609a7c5aac91913cb7c)
6. [Alpine Toolbox](https://www.alpinetoolbox.com/)  
7. [Nginx](https://blog.mosuke.tech/entry/2016/06/04/180122/)  
8. [ElixirでIoT](https://www.slideshare.net/takasehideki/elixiriot-2)  
9. [Phoenix Liveview chartjs setup](https://elixirthanosmango.substack.com/p/phoenix-liveview-chartjs-setup)  
10. [テールウィンドCSS](https://tailwindcss.com/)  
11. [Alpine.js](https://github.com/alpinejs/alpine)  
12. [フェニックスフレームワーク](https://phoenixframework.org/)  
13. [エリクサー](https://elixir-lang.org/)  