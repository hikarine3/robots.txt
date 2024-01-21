# Purpose of this robots.txt
Allowing crawlers to take content freely will lead to

・Increasement of site load and cost. User experience will also get worsen.

・Increasement of bandwidth usage will increase cost directly because AWS and so on is charning network usage.

・Generative AI is showing your content outisde of your website, which will lead to decreasement of your income because users will satisfy seeing your content outside of your web site and will not visit your web site.

Robots.txt is for limiting crawler's access to your web sites.

This robots.txt will not block crawlers that are useful for SEO, but block all other bots.

This robots.txt is taking care of English & Japanese web sites for SEO, not caring Korean(Naver) & Russian(Yandex) web sites.

You can check update at 

https://twitter.com/search?q=%23robotstxt%20from%3Ahajimekurita&src=typed_query&f=live

# このrobots.txtの目的
クローラーに自由にコンテンツを取らせる事は

・サイトの負荷増加 => 必要スペックが上がることによるコスト増 & サイト速度の低下によるユーザー体験の劣化

・帯域利用増 => AWS等ではそのまま無駄に課金増

・生成AI等にコンテンツを取られる => コンテンツを書いているサイトではなく、その外で完結してしまい、収入減少位繋がる

ことにつながります。


robots.txtはそのルールに従ってくれるBotに限りますが、クロールの制御をすることができます。

まずはrobots.txtで対応して、それ以上はaccess_logを見ながら、IP領域を禁止していく事で対応していきましょう(AWS等クラウドインフラのIPレンジの禁止が有効です)

このrobots.txtでは、SEO的な有意なクローラーはブロックしないけど、そうでないものは全てブロックするという方針で生成されています。

なお、基本的にこれは、日本語と英語圏を想定したrobots.txtになっています(ロシア・韓国向けには最適化されていません)

更新情報は以下のTwitter検索式で出る形でも流していきます 

https://twitter.com/search?q=%23robotstxt%E6%9B%B4%E6%96%B0%E6%83%85%E5%A0%B1%20from%3Ahikarine3&src=typed_query&f=live
