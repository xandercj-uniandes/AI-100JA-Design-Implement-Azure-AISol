﻿# 講師用メモ: ラボ 2.2

**このドキュメントは、これらの資料/ラボの提供に関して、いくつかの (願わくば) 役立つ注意事項とヒントを提供するために用意されています**

## ボットの構築の紹介 [30 分未満]  

*	ボットに関する知識と使用レベルを測定するための簡単な投票/ディスカッション
    *	教室で、誰が実装したか、どのように考えているのか、彼らがどう思うか、どの程度使いやすく、アクセスしやすいか、柔軟性があるのか、カスタマイズの選択肢はあるのかを尋ねてみてください。
*	シンプルな PowerPoint または Web サイトの画面共有を使用したボットの概要
    *	UPS C#、ボット、LUIS https://www.youtube.com/watch?v=M8SIs1GfSz0 
    * https://docs.microsoft.com/ja-jp/bot-framework/bot-service-overview-introduction 
*	いくつかのボット シナリオについて話す - 出発点として Web サイトを使用する
    *	https://docs.microsoft.com/ja-jp/bot-framework/bot-service-scenario-overview
    *	クラスで、他の人のことを考えることができるか、ボットを実装したときやボットを操作したときの例を共有できるかと尋ねてみてください。
    *	Litware 保険会社のボットがその良い例です (約 1～9 分。長すぎるのでスキップしてもかまいません。アイデアを把握するために、事前に視聴してください。
        *	https://www.youtube.com/watch?v=1xgMEkvEppM
*	ラボをセットアップする 
    *	目標
    *	アーキテクチャと使用例
    *	デモを行う
    *	ボット -> 正規表現 -> 検索 -> LUIS
        *	ステップ間の目的やメリットを明確にする必要があります。各ステージのデモと、それが次に追加する内容につながる理由を検討してください
    *	クラスのレベルに応じて、Visual Studio のデモや Bot Emulator の使用を含めます
        * 多くの受講者が Emulator でログ バーを上に引き上げられることを知らないとわかりました
*	ラボの最後にディスカッションのための時間をできるだけ多く確保しましょう
    *	LUIS についてどう思いますか? 第一印象は?
    *	ディスカッションのためのための時間をできるだけ多く確保する
        *	質問/思考/経験/課題


## ラボ 2.2 のヒント
* 受講者がこのラボをスキップする場合もあれば、ゆっくり時間をかけることもあります。必要なだけ時間を与えてください (妥当な範囲内で)。このラボでは、受講者が取り組んでいるすべてのサービスを結び付けています
* 各手順にソリューション ファイルがあることを覚えておいてください
* Newtonsoft.Json に問題がある場合は、パッケージを完全に削除し、NuGet から再インストールすることをお勧めします
* 多くの受講生は、Emulator を公開した後に、指示されなくても、Emulator を使用してボットに接続しようとします。これを行うには、AppId と AppPassword を入力して、ngrok を設定する必要があります (また、2 つのチェック ボックス「Bypass ngrok for local addresses」 (ローカル アドレスの ngrok をバイパス) と「Use version 1.0 authentication tokens」 (バージョン 1.0 認証トークンを使用する) をオンにする必要があります)。




