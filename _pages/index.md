---
title: "HUIT 北大IT研究会"
classes: wide
permalink: /
---

<!-- ![image]({{ "/assets/images/huit_logo_white.png" | relative_url }}) -->

<!-- {{site.baseurl}}はレポジトリの設定によっては/sample...で上手く出来ない時があるので必要 -->

<!-- # HUIT 北大 IT 研究会 -->

<!-- [English Page](/en.index) -->

<!-- English Page is [here](/en.index).-->

<!-- 日本語わからん人が来たとして、どうするん？ -->
<!-- かっこいい -->

# HUIT ウェブサイトへようこそ!

### HUIT とは?

HUIT は、北海道大学の学生を中心とした IT 系学生サークルです。

北海道のエンジニア学生の交流の場になるようなコミュニティを目指して 2017 年から活動しています。

毎週金曜日午後 8 時からの定期的な活動の他、勉強会やハッカソン、LT 大会を開催しています。

<!-- 24時間表記が好き -->

Twitter: [@huitgroup](https://twitter.com/huitgroup)

### 🎉 2022 新歓

HUIT は、新歓を 4 月の金曜日(4/1、4/8、4/15、4/22、4/29)にオンラインで行います!
時間は 19:00 ~ 21:00 を予定しています。内容は追って更新します。

### 新規入会

HUIT では、いつでも入部を受け付けています。2 ヵ月の体験入部期間でぜひ雰囲気を掴んでください。興味があれば [Twitter の DM](https://twitter.com/huitgroup) まで！

勉強会の飛び入り参加もお待ちしています。

## 👨‍💻 これまでの活動

### 2021 年

<ul> <!-- 2021年の記事一覧 -->
{% for post in site.posts reversed %}
    {% capture year %}{{ post.date | date: "%Y" }}{% endcapture %}
    {% assign currentYear = 'now' | date: "%Y" %}
    {% if currentYear == year %}
      <li>{{ post.date | date: "%m 月 "}}<a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>

<!-- - 5 月 新入生向け勉強会
  - 5/21 ネットワーク勉強会（予定）
  - 5/28 機械学習勉強会（予定）
  - 6/4 Web エンジニアになろう（予定）
  - 6/11 開発と Docker（予定） -->

---

～終了した活動～

- 03 月 HUIT ハッカソン開催
- 04 月 部の discord の管理に bot を作ってみた
- 06 月 集中講義「プログラミング教室」の TA を派遣しました
- 07 月 夏だ！花火だ！LT だ！ HUIT × ビズリーチコラボ LT 大会
- 12 月 [2021 年 HUIT アドベントカレンダー](https://qiita.com/advent-calendar/2021/huit)

～今後の予定～

<br/>

#### [これまでの活動記事](/activities)

<br/>

---

### 🛠️ 部員の技術スタック

- Web 制作
  - フロントエンド： `Next.js` `React` `Vue` `Jekyll`
  - バックエンド： `FastAPI` `Django` `Docker` `Node.js` `Go` `PHP` `Firebase`
- 競技プログラミング： `C++` `Python`
- アプリ: `flutter` `Android` `iOS`
- Windows アプリケーション制作 `C#`
- ゲーム制作： `Unity`
- ネットワーク・OS： `C` `Rust`
- マイコン・組み込み・IoT： `Raspberry Pi` `Arduino` `ESP` `PIC` `IchigoJam`
- バージョン管理 `Git` `Github`
- BOT 制作： `Discord` `Twitter`
- 機械学習・AI： `自然言語処理` `画像処理` `音声処理`
- ブロックチェーン: `NFT`
- blender
- Latex

### 🎈 部員のイベント参加

- ハッカソン
  - [技育展](https://talent.supporterz.jp/geekten/2021/)
  - [JPHacks](https://jphacks.com/)（全国大会出場）
  - てくのこ
  - [SAPPORO CITY HACK](https://mikan-hchp.connpass.com/event/240964/)
- セキュリティ
  - [SecHack365](https://sechack365.nict.go.jp/course/index.html)
  - [セキュリティ・キャンプ](https://www.ipa.go.jp/jinzai/camp/index.html)
  - [セキュリテイミニキャンプ](https://www.security-camp.or.jp/minicamp/online2021.html)
  - [Micro Hardening v2](https://microhardening.connpass.com/event/211463/)
  - Global Cybersecurity Camp ([gcc.ac](https://gcc.ac/))
- 競プロ
  - [ICPC アジア地区予選](https://icpc.iisf.or.jp/2020-yokohama/)
  - [ICPC](https://icpc.iisf.or.jp/)
  - [Google Code Jam](https://codingcompetitions.withgoogle.com/codejam)
  - [AtCoder](https://atcoder.jp/?lang=ja)
- CGコンテスト
  - Fusion 360 学生デザインコンテスト
  - Fusion 360 Virtual Academic Design League
  -  [Generative Design Award](https://www.myautodesk.jp/f360-gd-contest-2021/)
- LT会
  - 技育祭2022春 学生LT
  - 北海道未完×デルタ新潟合同LT会
  - 未完LT会
- CTF
  - WaniCTF2021
  - nitic_ctf_2
  - [SECCON CTF 2021](https://www.seccon.jp/2021/)
- その他
  - [ISUCON10](https://isucon.net/)
  - [N-PTC](https://nttcom.connpass.com/event/201413/)
  - [バーチャル雪まつり2021 主催](https://www.value-press.com/pressrelease/264864)
  - [Kaggle](https://www.kaggle.com/)
  - [ICTSC](https://icttoracon.net/)
  - [北大DXフェローシップロゴデザイン](https://sites.google.com/eis.hokudai.ac.jp/dxphd-fellow/logo)

---

## ✉️ お問い合わせ

見学希望・イベント共催・その他、Twitter ([@huitgroup](https://twitter.com/huitgroup)) まで DM お願いします！

<div style="width: 80%;margin: auto;">
<a class="twitter-timeline" data-height="600" data-theme="light" href="https://twitter.com/huitgroup?ref_src=twsrc%5Etfw">Tweets by huitgroup</a>
</div>
 <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
