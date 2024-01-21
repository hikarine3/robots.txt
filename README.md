# Purpose of this robots.txt (English Description)
Allowing crawlers to take content freely will lead to

・Increase site load => Increased cost due to higher required specs & Deterioration of user experience due to decreased site speed

・Increase in bandwidth usage => AWS, etc. charges will increase unnecessarily

・Content is taken by generation AI, etc. => User satisfy seeing content generated by your web site outside of your web site, which will leading to a decrease in income.

Robots.txt is limited to bots that follow the rules, but you can control their crawling.
First of all, let's deal with robots.txt, and then proceed by checking the access_log and prohibiting IP ranges (banning IP ranges of cloud infrastructure such as AWS is effective)

This robots.txt is generated with the policy of not blocking crawlers that are significant for SEO, but blocking everything that is not.

# このrobots.txtの目的
クローラーに自由にコンテンツを取らせる事は

・サイトの負荷増加 => 必要スペックが上がることによるコスト増 & サイト速度の低下によるユーザー体験の劣化

・帯域利用増 => AWS等ではそのまま無駄に課金増

・生成AI等にコンテンツを取られる => コンテンツを書いているサイトではなく、その外で完結してしまい、収入減少位繋がる

ことにつながります。


robots.txtはそのルールに従ってくれるBotに限りますが、クロールの制御をすることができます。

まずはrobots.txtで対応して、それ以上はaccess_logを見ながら、IP領域を禁止していく事で対応していきましょう(AWS等クラウドインフラのIPレンジの禁止が有効です)

このrobots.txtでは、SEO的な有意なクローラーはブロックしないけど、そうでないものは全てブロックするという方針で生成されています。
