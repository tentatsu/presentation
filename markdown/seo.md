---
marp: true
theme: default
header: "SEO講座"
footer: "**＠tentatsu**"

size: 16:9
paginate: true

style: |
    section.title {
        justify-content: center;
        text-align: left;
    }
    section.title h2 {
      padding-bottom: 100px
    }
    section.title h3 {
      align-self: flex-end;
      margin-top: 0px;
    }
    section {
        justify-content: start;
    }

    section h1 {
        padding-bottom: 0px;
        }

    section.philosophy ol li {
        font-size: 24px;
        }
    section.pan img {
        height: 400px;
        }

---
<!-- _class: title -->
# イマドキSEO講座
## 知識編
### tentatsu
### 2021-05-21

<!--
_color: white
_footer: 'Photo by Earl Lasala on Unsplash'
-->

![bg brightness:0.4](https://images.unsplash.com/photo-1600183309638-bb6dfca7e921?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80)

---

# SEOとは
* SEO（Search Engine Optimization）とは検索エンジンの自然検索結果画面（SERPs）において、狙ったキーワードで上位表示させること

---

# 順位の決まり方（セオリー）
* 他サイトからのリンクなどの「外部要因」と、自サイトのページ構造などの「内部要因」の2つの評価指標がある
* SEOを成功させるにはクローラがどういった基準で評価するかを知る必要がある
    * 正しいHTMLの形式
    * ページスピードの探求
    * 回遊性、使いやすさ
    * 情熱

---

# SEOが必要な理由
* お金を稼ぐため
* お金 ≒ 流入数
  * ECの場合は 売上 = 流入数 * CVR * 平均単価
  * アフィリエイトサイトの場合は 売上 = PV * クリック率 * 単価


---


# Google検索結果のクリック率

### 諸説ありですが、概ね以下の通り
| 順位 | クリック率 | 10,000人来たら |
| --- | --- | --- |
| 1位 | 30〜40% | 3,500クリック |
| 2位 | 15〜30% | 2,000クリック |
| 3〜5位 | 10% | 1,000クリック |
| 6〜10位 | 2% | 200クリック |


<!--
_footer: データ元: https://note.com/putilapan/n/n5905a56fd8f0
-->

---

# こんなサイトはSEOは必要ない
* SNS
* アプリ
* 固定客のみが利用するWEBサイト
* 独占したキーワード、絶対的強者

---

# SEOの手法
* HTMLタグの最適化
* パンくず、構造化データ（厳密にはSEOではない）
* 被リンク
* サイトの構造化
* コンテンツSEO
* ページスピードの改善
* モバイルファースト
* コンテンツの品質、唯一性
* キーワード選定

---

# HTMLタグの最適化（効果小）
* altタグを入れる
* title、descriptionなどの記述の徹底
    * title、descriptionに、ページごとのキーワードをいかに自然に大量に入れるか
    * ページに含まれている情報をや結論を紹介し、完結にまとめながら「共感」を生み出せること
        * つまり情熱。
* hタグ、li、ul等はもう効果薄い
  * けど構造はきちんとして方がいい
    * 最近はsectionが主流

---
<!-- _class: pan -->
# パンくず、構造化データ（効果無）
* https://developers.google.com/search/docs/guides/intro-structured-data?hl=ja
  * 構造化データは、検索結果をリッチにする可能性がある
  * やらないよりはやった方が絶対に良い
![](https://arutega.jp/wp-content/uploads/2017/07/exam-e1530239030952.png)

---

# 被リンク（効果小）
* 無いよりはあった方がいい。不自然な増え方はNG
    * リンクプログラムへの参加などは絶対に行わない
    * アフィリエイトはOK。但し媒体は選ぶ。
        * キーワードが類似していて「ちゃんとした」サイトであること

---

# サイトの構造化（効果中）
* サイトの属性を理解し構成を作っていく
* 関連する商品などの相互リンクをつくりサイト内のメッシュ化を行う
    * 回遊性の高いサイトが高評価となる


---

# コンテンツSEO（効果大〜小）
* 記事を量産してキーワードの関連性を高める
  * ブログ
  * コンテンツのリッチ化
  * 一節には、月100記事以上アップしないと意味がないとの噂も


---

# ページスピードの改善（効果大）
* [page speed insight](https://developers.google.com/speed/pagespeed/insights/?hl=ja&url=https%3A%2F%2Fdrafan.com%2F)
    * TTFB
    * Total Blocking Time (TBT)
    * ファーストビュー
    * レスポンスサイズ
        * CSS、JSの圧縮、画像の軽量化
次回

---

# モバイルファースト（効果大）
* 今は調べ物の7割はスマホ
* モバイル対応ではなく、モバイルファースト
  * 、ECサイトで商品を購入する際に利用するデバイス（重複有）
    * スマホ：81.3％
    * PC：38.2％
    * タブレット：12.0％

---

<!-- _class: "philosophy" -->
# コンテンツの品質、唯一性（効果特大）
* [Google が掲げる 10 の事実](https://www.google.com/about/philosophy.html?hl=ja)
1. ユーザーに焦点を絞れば、他のものはみな後からついてくる。
2. 1 つのことをとことん極めてうまくやるのが一番。
3. 遅いより速いほうがいい。
4. ウェブ上の民主主義は機能する。
5. 情報を探したくなるのはパソコンの前にいるときだけではない。
6. 悪事を働かなくてもお金は稼げる。
7. 世の中にはまだまだ情報があふれている。
8. 情報のニーズはすべての国境を越える。
9. スーツがなくても真剣に仕事はできる。
10. 「すばらしい」では足りない。

---

# キーワード選定（効果大）
* キーワードの選び方１
    * そのキーワードを検索して流入したユーザーからCVは期待できるか（アクセスの質）
        * リスティング広告の検索クエリデータ
        * アクセス解析のCVログデータ
        * 競合が対策しているキーワード
        * 自社サービスに関する知識と勘、自社の顧客のイメージ
    * そのキーワードは実際に検索エンジンで検索されているか（アクセスの量）
        * Google AdWords キーワードプランナー
        * Google Trends

--- 

# キーワード選定（効果大）
* キーワードの選び方２
    * 関連キーワードや複合キーワードで使えるキーワードはないか？（キーワードの幅）
        * Google AdWords キーワードプランナー
          * https://ads.google.com/aw/keywordplanner/home
    * そのキーワードで上位表示させることは現実的に可能か？（競合性)
        * 複合語を狙えないか


---
# 結論

* システム的SEO（HTML最適化、構造化データ）
  * 必ずやるべし。
  * これをやって初めて土俵に立てる
* 構造的SEO（サイトの構造化）
  * 伸び悩んでいるならやるべし
  * そうでなくても回遊性を考えたらSEO関係なくやるべき
* 情熱的SEO（キーワード選定、品質）
  * 常に持ち続ける
    * 情報の更新は検索エンジンは歓迎。一節には更新頻度も見ているとの噂
* 外的SEO（被リンク）
  * 時間、お金に余裕があればやるべし

---
# 次回予告
次回は、情熱的SEOにおけるキーワード選定のやり方とテクニックなどをご紹介！

