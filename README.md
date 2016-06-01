** work in progress **

# 開発文化・基本理念

ベーシックのエンジニアとして目指したい姿や、開発チームのあり方、文化・基本理念について明文化しておきます。修正案などあれば随時プルリクを送ってもらえればと思います。

## 開発文化

**楽しくプログラミング**

開発文化を一言で表すなら **楽しくプログラミング** です。楽しくプログラミングができる環境を目指す姿勢ですね。もちろん1つの会社としての業務なので、すべての仕事が無条件で楽しいわけではないですが、何事も **楽しむ工夫** ができるエンジニア集団でありたいと考えています。

後述する基本理念は全てプログラミングを楽しみ、その結果としてユーザ（時には自分）の問題解決をする良いサービスを作れることにつながってくると考えています。

## 基本理念

### HRTの精神でコミュニケーションする

Team Geekより。

- 謙虚(Humility)
- 尊敬(Respect)
- 信頼(Trust)

あらゆる人間関係の衝突は、謙虚・尊敬・信頼の欠如によるものだ。

### プログラマの三大美徳

- 無精（Laziness）
- 短気（Impatience）
- 傲慢（Hubris）

### 良いプログラマ

偉大なプログラマになるのは難しいですが、良いプログラマには努力すればなれます。また、プログラマは良いプログラマと一緒に働きたいはずです。良いプログラマの定義は後述する理想のエンジニア像で説明します。

### 人的単一障害点の排除

いわゆる属人化の排除です。特定の人にしか分からないこと、できないことを極力減らし、ノウハウの共有やスキルの継承を積極的に行っていきます。これは自分自身を楽にするためにも、とても有用な方法です。また、全体のスループットを上げるためには、ボトルネックを解消しなければならないので、誰か1人に業務が集中するような自体を避ける必要があります。

### 許可を求めるな謝罪せよ

ユーザやサービスにとって良いことと信じて、真摯に取り組んでいるのであれば、許可を取るという行為の工数はなるべく減らすべきだと考えています。

## 理想のエンジニア像

全てに当てはまる必要はないです。

- 何事も楽しむ工夫ができる
- インフラからフロントまで幅広い技術に興味関心がある
- 指示待ちをせず、自分駆動で動くとが出来る
- 誰かが決めたことに対して、疑問を持ち自分の考えを持つ
- とにかくプログラミングが好きだ（自分の中での相対的に）
- 新しい技術の上辺だけでなく、実際に体験することで業務の中でどう活かせるかを考えられる

## 備忘録的キーワード

- 適度な非同期コミュニケーション
 - slackやqiita::teamなどのツールを上手く使って、時間を拘束せずに共有ができるようにする
 - 対面でコミュニケーションをした方がいいことは、ちゃんとやる
- レビュー
 - コードを見る文化・見られる文化
  - (強い|分かる)人がレビューするのではなく、互いに見合う
 - コードに対して批判をする
  - コードは君自身じゃない
 - 具体的なコードで示してあげることも必要
- テスト
 - テスト自体はコードの品質を上げない
  - テストは、あくまで品質の見える化
 - 品質を上げるのは、設計とプログラミング
 - あなたが書き始めないと誰も書かない
 - 地道に少しずつテストコードを増やしていく
- メタプロ
 - 黒魔術を必要以上に恐れないが、ダークフォースに取り込まれないように気をつける
- 自動化
 - あらゆる定型化される作業は自動化を検討する
 - 仕様として例外がなるべく内容に落としこむ
- 開発環境改善
 - エンジニアにとって開発環境は、住環境よりも重要。常により良いものを模索する
- 非エンジニアの巻き込み方
 - チームであるならば、非エンジニアもGitHubが使えた方がいい
- リファクタリング
 - リファクタリング自体を別タスクにしない。たいていは実行されないまま埋もれていく
 - ボーイスカウトの原則にのっとって綺麗にする
  - やりすぎないバランス感覚は重要
- SRE
- 高速なアプリケーションを素早く作る
- 適度なマイクロサービス
- 自走  
- オープンソース
- YAGNI
- DRY
- KISSの原則
- 推測するな、計測せよ
- エラーログを放置しない
- ドキュメントを書く
- シェアする
- アウトプットする
- 早めのプロトタイプ
- 質とスピードを両立させる
- (偉い|強い)人の言うことを疑う
- 継続的デリバリーが持続可能な状態
- 隣の芝生は青いが、気にし過ぎない
- 人は自分のスピードでしか成長できない
- リファクタリングを別タスクにしない
- 全ては変化する（仕様・環境・技術）
- すぐ聞ける
- 教えられる人を増やす

## オープンソースソフトウェアポリシー

作りたい。

## 参考

- http://www.buildinsider.net/enterprise/devops/01
- http://techlife.cookpad.com/entry/oss-policy

