
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

emotional-support-pets

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

創作（小説特化）

# description

> This is the description of the feed.

日本創作小説作者の声に特化したフィードです。
小説投稿サイトのURLがリンクされている場合も拾います。

創作漫画、二次創作系は除外。
イラストは特に制限せず。
現在の処、エロやBL等の特定ジャンル制限は行ってません。
極力タグを必要としない検索を目指しています。

リンク先検索
なろう、カクヨム、ノベルアップ、ピクシブノベル、アルファポリス、エブリスタ、etc.

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- 創作
- 小説
- 一次創作
- 創作小説
- 創作資料
- 創作論
- #物語
- 公募作
- BL小説
- 創作BL
- 書いた小説
- 書いたお話
- 書いた話
- 話を書
- 小説を書
- 小説書
- 話書
- 物書
- 文字書
- ラノベ書
- ライトノベル書
- 執筆し
- 軽小説
- プロット
- 拙作
- 作劇
- kakuyomu
- syosetu
- novelup
- pixiv.net/novel
- alphapolis
- estar.jp/novels
- novel
- prologue-nola.com
- sutekibungei
- maho.jp
- novel.daysneo.com
- monogatary.com
- novema.jp/book
- novelba.com
- ln-street.com
- nola-novel.com


# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social

- 二次創作
- 2次創作
- ２次創作
- 三次創作
- 3次創作
- 二次作
- 2次作
- 漫画
- 創作漫画
- 二次会
- 2次会
- 一次会
- 1次会
- 二次
- 2次
- 読了
- 感想
- 夢小
- ドリーム小
- 創作ゲーム
- 読み終
- 放送
- 生放送
- 創作料理
- 創作洋菓子
- 漫画
- 書評
- #読書メーター
- コラボ小説
- sketch
- ジャニーズ
- 宝塚
- 買った本
- ファンダム
- 写真集
- louis-c-novel.com
- homto.jp
- chunichi.co.jp
- dengekibunko.jp
- shironeko.net|nhk.or.jp
- .go.jp
- openstreet
- mainichi.jp
- asahi.com
- yahoo
- amazon
- amzn.to
- pixiv.net/artworks
- youtu.be
- audee
- コンサート
- 監督
- 主演
- セーラームーン
- セラムン
- 犬夜叉
- 観て
- 観た
- 映画
- filmarks.com
- youtube
- YouTube
- booth.pm
- blog.bbsakura.net
- BBSakura
- bookmeter.com
- at://did:plc:sdmqrz7luyqtslrege5ozcmw/app.bsky.graph.list/3kgipzs6lzb2l

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

false

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
