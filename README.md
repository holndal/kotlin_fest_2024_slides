# kotlin fest 2024 slides


## 今こそ始めたい！Compose Multiplatform
### TAGS
- KMP(Kotlin Multiplatform)
- 初級者

### Presenter
OGI [@ogi2ogi](https://twitter.com/ogi2ogi)

### Description
Jetpack ComposeのMultiplatform対応が安定版でリリースされ、1つのコードベースからAndroid/iOS/デスクトップなど複数のプラットフォームにネイティブUIを提供できるようになりました。
本セッションでは、Compose Multiplatformを用いてAndroid/iOSのアプリケーションを開発する流れを自身の経験を交えて初学者の方にもわかりやすく解説します。
あなたが既にKotlinに興味があったり触れたことがあるなら、Compose Multiplatformフレームワークを用いることで効率的にマルチプラットフォームアプリを構築できます。
マルチプラットフォームに興味はあるものの、何から始めたら良いか不安を感じている方も、本セッションを通してCompose Multiplatformへの第一歩を踏み出して頂けたら幸いです。

### Slides
- [Speaker Deck](https://speakerdeck.com/ogi2ogi/get-started-with-compose-multiplatform)

## Kotlinで愉しむクリエイティブコーディング
### TAGS
- その他
- 初級者

### Presenter
畠山 創太 [@chooblarin](https://twitter.com/chooblarin)

### Description
クリエイティブコーディングを行うソフトウェアにおいてはProcessingが広く知られています。 [OPENRNDR](https://openrndr.org/) はKotlinで書かれたクリエイティブコーディングのライブラリです。
私はこれまでに、中高生や大学生にプログラミングの講義をする機会に恵まれてきましたが、その経験からKotlinとOPENRNDRがたのしくコーディングするために優れたものであると感じています。

本セッションのトークでは、皆さんが今すぐOPENRNDRを使ってクリエイティブコーディングを始めたくなるような紹介を試みたいと思います。

### Slides
- [site](https://chooblarin.com/enjoy-creative-coding-with-kotlin/)
- [PDF](https://chooblarin.com/enjoy-creative-coding-with-kotlin/p.pdf)


## 2024年版 Kotlin サーバーサイドプログラミング実践開発
### TAGS
- Webバックエンド／サーバサイド
- 中級者

### Presenter
竹端 尚人 [@n_takehata](https://twitter.com/n_takehata)

### Description
私は2021年に「Kotlin サーバーサイドプログラミング実践開発」という書籍を出版しました。
その中ではサーバーサイドKotlinで必要なフレームワークの知識、実践的なアプリケーションの作成もしています。
しかしそこから3年が経ち、執筆当時からサーバーサイドKotlinを取り巻く環境は変わってきています。

そこで、今回は書籍の内容からアップデートし、2024年現在のトレンドに則った

・フレームワーク
・アプリケーションアーキテクチャ
・各種ツール

でのKotlinのサーバーサイドアプリケーションの作成方法について紹介していきます。
「サーバーサイドKotlinを導入してみたい」と考えている方にとって、一つの道筋になるかと思います。

### Slides
- [Speaker Deck](https://speakerdeck.com/n_takehata/kotlin-server-side-programming-practice-2024)

## パフォーマンスと可読性を両立：KotlinのCollection関数をマスター
### TAGS
- Kotlin言語・プログラミング
- 初級者

### Presenter
Masayuki Suda [@daasuu](https://twitter.com/daasuu)

### Description
KotlinのCollection関数の有効活用に焦点を当てたこのセッションでは、100を超える豊富な関数を概観し、それぞれの使用時の利点を探ります。
実際のコード例を通じて、どんなCollection関数があるか、どのシナリオでCollection関数を選択するか等学びましょう。

トピック例
・Kotlin Collectionの概要 - Collectionのフレームワーク基本構造と主要なインターフェースの説明
・Collection関数のカテゴリー分け - 変換関数、フィルタリング関数、集約関数、分割関数などに分けて関数を紹介
・高度な関数 - groupBy, partition, fold などの高度な関数の活用方法と例。
・パフォーマンスの最適化 - Collection関数のパフォーマンスに影響を与える要素と、効率的なコードを書くためのテクニック。for文の出番も？

### Slides
- [Speaker Deck](https://speakerdeck.com/masayukisuda/kotlin-collectionguan-shu-womasuta)

## KotlinのLinterまなびなおし2024
### TAGS
- ツール／エコシステム
- 初級者

### Presenter
nyafunta9858 [@nyafunta9858](https://twitter.com/nyafunta9858)

### Description
Linter導入していますか？
Linterはコーディング規約を遵守しているかを検査したり、潜在的なバグのにおいを検知してくれたりと開発をするうえでとても頼りになる存在です。
また非常に多くのルールが標準で用意されているためこれらを利用するだけでも有用ですが、自分たちで適用するルールを選択したりカスタムルールを作成することもでき、柔軟な設定をすることができます。
一方でその柔軟さのあまり、使いこなせていないと感じたり、実は形骸化してしまっていてるといったケースもあるのではないでしょうか。

本セッションでは、ktlintやdetekt、Release1.0間近のKonsistといったKotlin向けのLinterの特徴や活用シーンなどを再履修し、「なんとなく」から「意識的に選択・活用できる」ようになることを目指したいと思います。

### Slides
- [Speaker Deck](https://speakerdeck.com/nyafunta9858/kotlinnolinter-manabinaosi2024)


## Okioに愛を込めて
### TAGS
- KMP(Kotlin Multiplatform)
- 中級者

### Presenter
RyuNen344 [@RyuNen344](https://twitter.com/RyuNen344)

### Description
OkioはSquareが開発しているjava.ioとjava.nioの取り回しを楽にしてくれるラッパーライブラリです。言わずと知れたOkHttpやMoshiのベースにも使用されているライブラリです。
Kotlinで書き直された2.0.0よりMPP（KMP）対応が行われ、3.0.0でファイルシステム周りの機能が追加されました。
KMP（android, iOS)プロジェクトで実際に使用した私がありがたいと感じた部分についてお話しします。

本セッションでは下記のことを取り扱います。

・標準ライブラリが強力なKotlinでなぜOkioを見直すのか
・KMP実装にIO周辺実装での諸課題
・KMP実装においてもOkioがもたらすメリット
・Okioを使用する際の注意するべき前提

### Slides
- [Speaker Deck](https://speakerdeck.com/ryunen344/okioniai-woip-mete)


## Kotlin Coroutinesで共有リソースに正しくアクセスする
### TAGS
- Kotlin言語・プログラミング
- 中級者

### Presenter
Mori Atsushi [@at_sushi_at](https://twitter.com/at_sushi_at)

### Description
Kotlin Coroutinesを使えば非同期処理を比較的簡単に書けますが、それでも複数のコルーチンから共有リソースにアクセスするときには最大限の注意を払う必要があります。

例えば、あるコルーチンで変数を読み込み、その値を元になにか操作を行い、結果をもとにその変数を上書きするとします。
その間に他のコルーチンによって値が書き換わることはないでしょうか？
その結果、予期せぬ不具合を引き起こしたりしないでしょうか？

正しく共有リソースを扱うためには、MutexやStateFlowのupdate関数など、それが考慮されたAPIをうまく組み合わせる必要があります。
また、1スレッドを使い回すディスパッチャと複数スレッドを使うディスパッチャがありますが、気をつけるべき点は異なります。
このセッションではどのようなコードで注意が必要なのか、また期待通りに動作させるための方法について紹介します。　

### Slides
- [Speaker Deck](https://speakerdeck.com/moriatsushi/kotlin-coroutinesdegong-you-risosunizheng-sikuakusesusuru)

## 2024年に公開するに相応しいKotlin Multiplatformライブラリを構築する
### TAGS
- KMP(Kotlin Multiplatform)
- 上級者

### Presenter
Atsushi Eno [atsushieno](https://zenn.dev/atsushieno)

### Description
Kotlin Multiplatform (KMP)は新しいKotlin開発のトレンドとなり、日々AndroidやKotlin/JVM専用だったKotlinライブラリがKMPに移行しています。Kotlin生態系を発展させていくには、われわれがKMPに対応したライブラリを公開していく必要があります。

Kotlin 2.0に向けて、wasmJsターゲットが追加されたKotlin本体も、Gradleプラグインやプロジェクト構成も、大きく変わってきていますが、KMPの本格的なライブラリ生態系には不可欠であろうネイティブライブラリの呼び出しや、それらを踏まえたMavenパッケージのビルドや配布など、未整備の部分も多いです。

このセッションでは、2024年にKMPでライブラリを構築して公開するまで、どんな課題をどうやって乗り越える必要があるのかを、自作ライブラリの経験をもとに皆さんに共有します。

### Slides
- [Speaker Deck](https://speakerdeck.com/atsushieno/building-kotlin-multiplatform-libraries-in-2024-cc23c2ab-bbbd-4e28-bd05-c46985685a23)


## 例外設計について考えて Kotlin（Spring Boot&Arrow）で実践する
### TAGS
- N/A

### Presenter
杉本将来 [@Msksgm](https://twitter.com/Msksgm)

### Description
例外設計の深掘りと、Kotlin による自作エラー型を用いた例外設計の実践方法を発表します。
例外は、ほとんどの言語に搭載される機能のため、あまり考慮せずに実装されがちです。結果、コードの保守や障害原因の特定が難しい状況になります。そこで、例外に関心を持ちチームの方針を決めることで、プロダクト開発（開発・運用・障害復旧）の生産性に好影響を与えると考えています。
Kotlin のリッチな機能に加えて Arrow の Either 型により、例外設計を柔軟に表現可能です。Spring Boot も含めた実装方法を実践します。

一連の内容を下記の項目で発表します。
例外設計を考える
・背景
・ビジネス例外と技術的例外
・モデリング
・監視と O11y
Kotlin で実践
・Arrow の Either 型による自作エラー
・Spring Boot に組み込む

### Slides
- [Speaker Deck](https://speakerdeck.com/msksgm/thinking-exception-design-and-implementation-by-kotlin)

## もっとKotlinを好きになる！K2時代のKotlin Compiler Plugin開発
### TAGS
- Kotlin言語・プログラミング
- 上級者

### Presenter
kitakkun [@kitakkun_pb](https://twitter.com/kitakkun_pb)

### Description
Kotlin Compiler Pluginは、KSPの制限を超えて、コードの生成だけでなく改変まで行える強力なツールです。
K2コンパイラの導入により、さらに柔軟なコンパイラ拡張が行えるようになりました。

私は大学の研究で、変数の監視や巻き戻しによるデバッグ（Time-Travel-Debugging, TTD）を実現するKotlin Compiler Pluginを開発しました。
本セッションでは、研究で得た経験をもとに、Kotlin Compilerの仕組みと、Kotlin Compiler Pluginの実装方法・活用例を紹介します。

アジェンダ

Kotlin Compilerの内部構造
Kotlin Compiler Plugin APIの紹介
Kotlin Compiler Pluginの活用例
奥深いKotlinの世界をコンパイラの視点で探究してみませんか？

### Slides
- [Speaker Deck](https://speakerdeck.com/kitakkun/kotlin-fest-2024-motutokotlinwohao-kininaru-k2shi-dai-nokotlin-compiler-pluginkai-fa)
- [Sample Code](https://github.com/kitakkun/greeting-plugin)

## まだ JUnit を使ってるの？ kotest を使って快適にテストを書こう
### TAGS
- ツール／エコシステム
- 中級者

### Presenter
川田裕貴 [@hktechno](https://twitter.com/hktechno)

### Description
kotest は、 Kotlin ネイティブなテストフレームワークで、Kotlin で書かれたコードをテストするための強力で便利な機能が多く含まれています。
Kotlin/JVM では、テストに JUnit を使っている方が多いと思いますが、アサーションライブラリが Java しか考えていなかったり、coroutines, 非同期処理への対応が弱かったりと、もっと Kotlin の機能を最大限に活用して快適にテストを書きたいと思われる場面も多い事でしょう。
kotest は、アサーションライブラリだけを JUnit と組み合わせて使うこともできるし、テストフレームワーク全体を kotest へ置き換えることも可能です。
このセッションでは、主に今 JUnit を使ってテストを書いている方を対象に、kotest へ移行するとどんな良いことがあるのか、移行のやり方や具体的な実例を紹介します。

### Slides
- [slide share](https://www.slideshare.net/slideshow/kotest-kotlinfest-2024/269819350)
- [Google Slide](https://docs.google.com/presentation/d/19rWucLtSoKGUuw2jRno0lBm3m4MUfONpoLGjRiAAdmA/edit#slide=id.p)

## withContextってスレッド切り替え以外にも使えるって知ってた？
### TAGS
- Kotlin言語・プログラミング
- 中級者

### Presenter
T45K [@getupmax](https://twitter.com/getupmax)

### Description
KotlinではCoroutineを用いることで、非同期処理を手続き的に記述できます。
Coroutineの利用例として「ネットワークアクセスをwithContext(Dispatchers.IO)でラップすることでIOスレッドで行う」という例が紹介されることが多いです。
そのため、「withContextはスレッド切り替え時に使う」という理解をされている方は多いと思います。
しかし、実際にはwithContextはCoroutineContextを切り替えるために利用するものであり、スレッド切り替え以外にもさまざまな活用法があります。
本セッションでは、CoroutineContextについて触れたうえで、筆者のチームがwithContextをどのような場面で活用しているかを紹介したいと思います。

### Slides
- [Speadker Deck](https://speakerdeck.com/t45k/withcontexttutesuretudoqie-riti-eyi-wai-nimoshi-erututezhi-tuteta)

## Jetpack Compose: 効果的なComposable関数のAPI設計
### TAGS
- 

### Presenter
haru067 [@haru067](https://twitter.com/haru067)

### Description
Jetpack Compose（以下、Compose）の登場により、AndroidにおけるUIの記述はView/XMLの時代から大きく変化しました。
Composeのような宣言的UIでは、与えられた入力値を元にUIの全てが決定するため、コンポーネントが何のパラメーターをどのように持つのか、といったAPI設計が品質に大きく影響します。
また、Composeは関数をベースにした記述方法であり、Kotlinの言語機能も上手く活用したAPI設計が必要になってきます。

本セッションでは、State hoistsingやState holder class、Slot API、Relaxed APIといったComposable関数のAPI設計にまつわるベストプラクティスについて軽く触れたのち、
それを、いつ、どのように適用していくべきか、是非を含めて実例を元に実践的な議論をしていきます。

### Slides
- [Speaker Deck](https://speakerdeck.com/haru067/jetpack-compose-xiao-guo-de-nacomposableguan-shu-noapishe-ji)


## Kotlin sealed classを用いた、ユーザーターゲティングDSL（専用言語）と実環境で秒間1,000万評価を行う処理系の事例紹介
### TAGS
- Kotlin言語・プログラミング
- 中級者

### Presenter
松田一樹, LDF [@kazuki_matsuda](https://twitter.com/kazuki_matsuda)

### Description
サービスの体験をパーソナライズし、興味のあるコンテンツを楽しんで貰うためには、
各種クリエイティブ（バナー・ポップアップ等）のターゲティング（by 年代、性別、OS、etc）が欠かせません。

最初は個別に実装する事が多いですが、露出面nとターゲティング条件mが増えた場合、O(n x m) の実装・メンテナンスコストがかかってしまい、共通化が必要となります。

今回の発表は、新規作成された共通化Platform上における課題：『マーケターを初めとする全社員が、ユーザーの条件やその AND/OR/NOT の任意の組み合わせによるターゲティングを可能とする』を、
Kotlin で実装した YAML ベースのユーザーターゲティングDSL（独自言語）とその処理系によって解決した事例の紹介となります。

安定的な拡張を行うためにKotlinの型が果たす役割についても取り上げます。

### Slides
- [Speadker Deck](https://speakerdeck.com/kazukima/number-kotlinfest-2024-kotlin-sealed-classwoyong-ita-yuzatageteingudsl-zhuan-yong-yan-yu-toshi-huan-jing-demiao-jian-1000mo-ping-jia-woxing-uchu-li-xi-noshi-li-shao-jie)

## あらゆるアプリをCompose Multiplatformで書きたい！ -ネイティブアプリの「あの機能」を私たちはどう作るか-
### TAGS
- KMP(Kotlin Multiplatform)
- 上級者

### Presenter
Subroh Nishikori [@subroh_0508](https://twitter.com/subroh_0508)

### Description
本セッションでは、現在発表者が本番リリースに向けて開発中である、Mastodon用クライアントアプリの実装を通して得た経験から、Compose Multiplatformによるモダンかつ実用的なネイティブアプリを実装するための知見を紹介します。

「画像の表示」「動画の再生」「ファイルピッカー」のような、直接ユーザーが触れる機能はもちろんのこと、「ディープリンクの実装」「ローカルなデータストレージへの認証情報の保持」等の表から見えづらい部分まで、実用的なネイティブアプリの開発における頻出要素をどうすれば共通のKotlinコードで表現し、複数のプラットフォームに向けて実装できるのか、解説します。現時点でのCompose Multiplatformの実力を多くの方に知っていただき、"真のマルチプラットフォーム開発"への挑戦者を1人でも増やせるような発表にできればと思います。

### Slides
- [Speaker Deck](https://speakerdeck.com/subroh0508/arayuruapuriwocompose-multiplatformdeshu-kitai-neiteibuapurino-anoji-neng-wosi-tatihadouzuo-ruka)


## K2のKotlin IDEプラグインの中を覗いてみよう♪
### TAGS
- その他
- 中級者

### Presenter
Yan Zhulanow [@yanewm](https://twitter.com/yanewm)

### Description
この春、K2コンパイラを使った、IntelliJ IDEAのKotlinプラグインのアルファ版が発表されました。見慣れたIDEが軽くなり、さらに、スイスイとコードを書ける感覚を目指したプラグインの開発がどんどん進んでいます。
K2の洗練された仕組みによって、コードの解析がかなり早くなりました。しかも、プラグインに新しいコンパイラが入っただけではありません。早くて安定するために、それぞれの部分をゼロから作り直したり、大幅に改善されたりしています。

Kotlinチームのメンバーとして、その変化について具体的にお話しさせていただきます。
難しそうだと感じる人もいるかもしれませんが、コンパイラやIDEの内部に触れたことがない人でもわかりやすい内容になっています。皆さんがよく知っているKotlinに、違う角度から触れてみましょう！

### Slides
- [Speaker Deck](https://speakerdeck.com/yanex/k2nokotlin-idepuraguinnozhong-wosi-itemiyou)

## Kotlinの歴史を可視化する
### TAGS
- Kotlin言語・プログラミング
- 初級者

### Presenter
Ayana Murakami [@Ayana_moomin](https://twitter.com/Ayana_moomin)

### Description
現代では広く使われているKotlin言語ですが、2011年に公開されて以降、さまざまな発展を遂げてきました。

ソフトウェアは、利用者のニーズや開発環境の変化により日に日に「進化」します。ソフトウェア工学の研究分野においても、特に1990年代後半からソフトウェア進化は活発に議論され始め、今では研究手法、研究対象物、目的はさまざまです。中でも、SEV(Software Evolution Visualization)は、可視化を用いて対象とするソフトウェアの進化を分析するアプローチです。

このセッションでは、SEVの手法を用いてKotlinの進化を紐解きます。Kotlin開発当初の思想や目的、他の言語との関係についても触れつつ、可視化結果とその解釈を発表します。

### Slides
- [Speaker Deck](https://speakerdeck.com/moomin/kotlinnoli-shi-woke-shi-hua-suru)
