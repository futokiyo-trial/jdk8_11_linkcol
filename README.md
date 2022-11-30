# jdk8_11_linkcol


## Java8からJava11へ変更点に関する参考文献

[Java11による変更点](https://twitter.com/sugarlife/status/1073854073764376576)

[Java SE 8から11で何が起きたか](https://speakerdeck.com/miyakawataku/java-se-8-to-11)

[Java 8 から Java 11 への移行](https://docs.microsoft.com/ja-jp/azure/developer/java/fundamentals/transition-from-java-8-to-java-11)

[Java8からJava11への変更点](https://qiita.com/nowokay/items/1ce24079f4daafc73b4a)

[InaccessibleObjectException の発生原因とその対処方（Java 9以降JavaPlatform Module Systemによりリフレクションの挙動がJava8とは異なる） - A Memorandum 2020-12-28](https://blog1.mammb.com/entry/2020/12/28/090000)

[【Modern Java】Java Platform Module System （JPMS） - A Memorandum 2020-07-13](https://blog1.mammb.com/entry/2020/07/13/090000)

[Java11へのマイグレーションガイド ～Apache Hadoopの事例～](https://www.slideshare.net/techblogyahoo/java11-apache-hadoop-146834504/)

[JenkinsがJava 8の対応を終了し、Java 11が必須に。Java 17の対応も開始 - Publickey 2022年7月7日](https://www.publickey1.jp/blog/22/jenkinsjava_8java_11java_17.html)

[巨大OSSプロジェクトにおいてJavaの最新バージョン(Java 17)に追従するための課題 #yjtc / YJTC21 C-8(2021/01/15)](https://www.slideshare.net/techblogyahoo/ossjava-yjtc-yjtc21-c8)

[Migration Guide from Java 8 to Java 11 #jjug](https://www.slideshare.net/YujiKubota/migration-guide-from-java-8-to-java-11-jjug)

[Java 10: 利用や動作に影響を与える変更点](https://gist.github.com/ykubota/3afcfdac5b252bd31ae8c14b54b5d32f)

[Java 11: 利用や動作に影響を与える変更点](https://gist.github.com/ykubota/b37a62de579dc92d02c9483974160c67)

[JshellでJDK11の動きを確認](https://qiita.com/nowokay/items/80e8ccd50f6749846dd6)

[最適なOpenJDKディストリビューションの選び方](https://www.slideshare.net/TakahiroYamada3/how-to-choose-the-best-openjdk-distribution-201905)

[JDKの選択肢とサーバーサイドでの選び方](https://www.slideshare.net/TakahiroYamada3/how-to-choose-jdk-for-server-side-20191004-gugj)

[Oracle JDK 8にあってOpenJDKにない機能](https://qiita.com/yamadamn/items/bb813dccaa1dc5585c9b)

[JDKの長期商用サポート(LTS)の提供ベンダー比較（無償利用についても言及あり）](https://qiita.com/u-tanick/items/bb166929a58a4c20bb88)

[OpenJDKと各種JDKディストリビューションの情報源まとめ #minjava](https://qiita.com/yamadamn/items/2dd26a014791b9557199)

[【OBSOLETE】Oracle Java SEの有償化に伴うOpenJDKへの切り替えの案内 | 京都教育大学 情報処理センター](https://www.kyokyo-u.ac.jp/c_ipc/openjdk.html)

[Oracle JDK 17 - （Oracle JDK 17から）再び商用利用が無料に（ただしOracle JDK 8/11は商用利用や組織内利用で有償ライセンスのまま）](https://www.infoq.com/jp/news/2021/11/oracle-jdk-free-again/)

[オラクル、Oracle JDKを再び無料提供へ、本番環境でも利用可。昨日リリースのJava 17から - Publickey 2021年9月15日](https://www.publickey1.jp/blog/21/oracle_jdkjava_17.html)

[Oracle JDK 17からの（再）ライセンス変更やLTS2年サイクル変更提案に関する雑感 - togetter 2021/09/22](https://togetter.com/li/1778216)

### JREという用語について。
https://twitter.com/kis/status/1551683885993689088

Java 8まで

JRE(Java SE Runtime Environment) = Java VM + API + Applet/Java Web Start

JDK = Java VM + API + JRE + 開発ツール(javac等)

(JavaVM, APIは二重に含まれていた)




Java 11以降

JRE = Java VM + API

JDK = JRE + 開発ツール



## Java17

[2022年のJavaまるわかり！最新バージョンからJavaを取り巻く環境まで 2022-07-14](https://gihyo.jp/article/2022/07/java2022-0701)

[Hashtag Jakarta EE #25](https://www.agilejava.eu/2020/06/21/hashtag-jakarta-ee-25/)

[Java17の新機能をざっくり紹介](https://qiita.com/ReiTsukikazu/items/407d61cb66fa4f562bf9)

[JJUGナイトセミナー「Java 17 リリース記念イベント with Foojay」](https://www.youtube.com/watch?app=desktop&v=eKKv39xni6Y)

[ローカルクラスとしてrecordを使う](https://irof.hateblo.jp/entry/2021/10/23/144337)

[Bootiful SQL Template 2.1.0でRecord対応をしました（Java 16以降のAPIをJava 8でビルドする）。](https://cero-t.hatenadiary.jp/entry/2021/10/23/121806)

[2022/03/16 Card Table Card Size Shenanigans](https://logico-jp.io/2022/03/16/card-table-card-size-shenanigans/)

[Java17雑感 2021-09-16](https://irof.hateblo.jp/entry/2021/09/16/151702)

[Java17にBump upしてみた - 使った/使わなかった新機能(前編) - 豆蔵デベロッパーサイト 2022-06-06](https://developer.mamezou-tech.com/blogs/2022/06/06/bumpup-java17-part1/)

[Java17にBump upしてみた - 使った/使わなかった新機能(後編) - 豆蔵デベロッパーサイト 2022-06-13](https://developer.mamezou-tech.com/blogs/2022/06/13/bumpup-java17-part2/)

[JDK 17の内部JDK要素の強力なカプセル化（JEP 403 Strongly Encapsulate JDK Internals,JEP 396 Strongly Encapsulate JDK Internals by Default） ](https://www.infoq.com/jp/news/2021/07/internals-encapsulated-jdk17/)

[Improve filtering for classes with security sensitive fields（JDK12以降リフレクションAPIのクラスのフィールやメソッドなどへのリフレクションAPI経由アクセスが禁止された）](https://bugs.openjdk.org/browse/JDK-8210522)

[Get declared fields of java.lang.reflect.Fields in jdk12（JDK12以降リフレクションAPIのクラスのフィールやメソッドなどへのリフレクションAPI経由アクセスが禁止された）](https://stackoverflow.com/questions/56039341/get-declared-fields-of-java-lang-reflect-fields-in-jdk12)

[Error with JDK12+ "java.lang.NoSuchFieldException: modifiers" #15239（JDK12以降リフレクションAPIのクラスのフィールやメソッドなどへのリフレクションAPI経由アクセスが禁止された）](https://github.com/prestodb/presto/issues/15239)

[Java17(Java13以降)でgraphemeをカウントする - abcdefg.....](https://pppurple.hatenablog.com/entry/2022/04/17/031646)

[Java17(Java13以降)でgraphemeをカウントするのJava SampleCode](https://github.com/pppurple/java_examples/blob/master/count-string-example/src/main/java/Main.java)

[文字列の長さを取得する方法：lengthとcodePointCountの使い分け｜Scalapedia](https://scalapedia.com/articles/8/%E6%96%87%E5%AD%97%E5%88%97%E3%81%AE%E9%95%B7%E3%81%95%E3%82%92%E5%8F%96%E5%BE%97%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95%EF%BC%9Alength%E3%81%A8codePointCount%E3%81%AE%E4%BD%BF%E3%81%84%E5%88%86%E3%81%91#%E3%82%B5%E3%83%AD%E3%82%B2%E3%83%BC%E3%83%88%E3%83%9A%E3%82%A2%E3%82%92%E5%90%AB%E3%82%80%E6%96%87%E5%AD%97%E5%88%97%E3%81%AE%E9%95%B7%E3%81%95%E3%82%92%E5%8F%96%E5%BE%97%E3%81%97%E3%81%A6%E3%81%BF%E3%82%8B)

[length／codePointCountメソッド | Javaコード入門](https://java-code.jp/189)

[nablarch core util StringUtil.java](https://github.com/nablarch/nablarch-core/blob/master/src/main/java/nablarch/core/util/StringUtil.java)

[Red Hat JBoss Enterprise Application Platform (EAP) 7 Supported Configurations](https://access.redhat.com/articles/2026253)

[Docker HubのOpenJDKイメージの利用を更新するためのアドバイス](https://rheb.hatenablog.com/entry/updating-docker-hubs-openjdk-image)

[Red Hat は Eclipse TemurinでJavaのサポートを拡大](https://rheb.hatenablog.com/entry/red-hat-expands-support-java-eclipse-temurin)

[【オンライン】 JJUG CCC 2021 Fall 発表資料・動画まとめ - 分かりやすい技術ブログ 2021/11/21](https://sun0range.com/event-report/jjug-ccc-2021-fall/)

[JJUG CCC 2021 Fall ( #jjug_ccc ) - セッション資料の一覧 - 地平線に行く 2021-11-21](https://yujisoftware.hatenablog.com/entry/jjug_ccc_2021_fall)

## Java18

[Java 18正式リリース。デフォルトのCharsetが「UTF-8」に、シンプルWebサーバ搭載など新機能](https://www.publickey1.jp/blog/22/java_18charsetutf-8web.html)

[JJUGナイトセミナー「Java 18 リリース記念イベント」](https://www.youtube.com/watch?app=desktop&v=fhIaKjfY5Bc&feature=youtu.be)

[Java 18新機能まとめ](https://qiita.com/nowokay/items/17d990aa8a5b1c5223c8)

[Java 18とAmberとValhallaとLoomの話の資料です。　Project Loomはコルーチンの実装ということになる](https://speakerdeck.com/kishida/java-18-new-feature-and-future)

## Java19

[JJUGナイトセミナー「Java 19 リリース記念イベント」：Head toward Java 19、JEP 424 Foreign Function & Memory API を試しに使ってみました！ by YujiSoftware、JDK17以降のOracle JDKライセンスモデルを再復習しよう by 伊藤 敬](https://www.youtube.com/watch?v=SrwIBVBz1Po)

[Head toward Java 19 KUBOTA Yuji LINE Corporation / IMF Team JJUG Night Seminar 2022/Sep/30](https://www.docswell.com/s/ykubota/5QWYY5-2022-09-30-211424)

[JEP 424 Foreign Function & Memory API を試しに使ってみました！](https://speakerdeck.com/yujisoftware/jep-424-foreign-function-and-memory-api-woshi-sinishi-tutemimasita)

[Java 19新機能まとめ](https://qiita.com/nowokay/items/b903c10502f9ffe50c3a)

[Java 19新機能まとめ - YouTube](https://www.youtube.com/watch?v=-5zlmBnxmCU)

[Java 19の注目新機能Virtual Threadについて～TechFeed Conference 2022講演より](https://gihyo.jp/article/2022/08/tfc003-java19)

[Java 19リリース――7つのJEPsを提供、開発者の生産性向上、パフォーマンスや安定性、セキュリティの強化も](https://gihyo.jp/article/2022/09/java19)

[Java 19が正式リリース。より軽量な仮想スレッド、RISC-Vへの移植など新機能。1年後のJava 21が次のLTS版に 2022年9月21日](https://www.publickey1.jp/blog/22/java_19risc-v1java_21lts.html)

[「Java19」は何が新しいのか？ 注目すべき新機能とJava17以降の変更点を解説 Java19での新しいAPI、変更点とJava17からのおさらい 第1回](https://codezine.jp/article/detail/16512)

[5 分でかんたんに学ぶ Java 19 の Virtual Thread](https://www.youtube.com/watch?v=gijkW4b3v8g)

[JEP 425: Java Virtual Threads to Deliver Improved Throughput](https://www.infoq.com/news/2022/05/virtual-threads-for-jdk19/?utm_campaign=infoq_content&utm_source=infoq&utm_medium=feed&utm_term=global)

[Quality Outreach Heads-up – JEP 425 Virtual Threads (preview) Testing 2022/05/19 : JDK 19 Early-Access builds 22でJEP 425 (Virtual Threads) がOpenJDKのメインラインに統合されたので、仮想スレッドを利用してのテストや、プレビュー機能を有効にして既存のコードのテストを実施し、フィードバックしてね、というお話。](https://logico-jp.io/2022/05/19/quality-outreach-heads-up-jep-425-virtual-threads-preview-testing/)

[VirtualThread の状態遷移図を作ったのでご査収ください](https://twitter.com/mike_neck/status/1537794055887032321)

[日本語訳：JEP 425 : Virtual Threads (Preview) https://openjdk.java.net/jeps/425 1](https://b.chiroito.dev/entry/virtualthreads1)

[日本語訳：JEP 425 : Virtual Threads (Preview) https://openjdk.java.net/jeps/425 2](https://b.chiroito.dev/entry/virtualthreads2)

[日本語訳：JEP 425 : Virtual Threads (Preview) https://openjdk.java.net/jeps/425 3](https://b.chiroito.dev/entry/virtualthreads3)

[日本語訳：JEP 425 : Virtual Threads (Preview) https://openjdk.java.net/jeps/425 4](https://b.chiroito.dev/entry/virtualthreads4)

[日本語訳：JEP 425 : Virtual Threads (Preview) https://openjdk.java.net/jeps/425 5](https://b.chiroito.dev/entry/virtualthreads5)

[Launching 10 millions virtual threads with Loom](https://www.youtube.com/watch?app=desktop&v=UVoGE0GZZPI)

[Java 19の注目新機能Virtual Threadについて ～TechFeed Conference 2022講演より 2022-08-25](https://gihyo.jp/article/2022/08/tfc003-java19)

[Java 19 has a convenient ThreadBuilder for both native and virtual threads](https://twitter.com/mariofusco/status/1579379935441195008)

[Java 19 がリリース (LTSではない)2022-09-26 今回の注目はやっぱり仮想スレッド](https://devlights.hatenablog.com/entry/2022/09/26/073000)

[C 1000 もちだ バーチャルスレッド詳細](https://www.youtube.com/watch?v=MawoXHB40NA)

[JJUG CCC 2022 Fallのバーチャルスレッドの発表、デモ](https://github.com/mike-neck/jjug-ccc-2022-fall-web)

[JJUG CCC 2019 Fall C+D 11:00 〜 11:45 『入門 例外』 発表資料](https://github.com/mike-neck/practical-exception)

[【オフライン&配信】 JavaOne & Devoxx報告会 2022（JDK12以降特記すべき仕様変更）](https://www.youtube.com/watch?v=9Pyxv2Eyl-c)

[JavaOne 2022 報告会（パターンマッチングとString Templatesの話）](https://speakerdeck.com/takasyou/javaone-2022-bao-gao-hui-patanmatutingutostring-templatesnohua)

[Devoxx Belgium 2022 Report - Akihiro Nishikawa November 11, 2022 ](https://speakerdeck.com/logico/devoxx-belgium-2022-report)

[コレクションフレームワーク関連セッション（JavaOne & Devoxx報告会 2022 発表資料） - 2022年11月11日（金）](https://www.slideshare.net/nttdata-tech/collections-framework-jjug-javaone-devoxx-2022-nttdata)


[Loom is Blooming by José Paumard & Remi Forax](https://www.youtube.com/watch?v=eU9mUmnhjb4)

[ぼくたちは Java アプリケーションの起動速度をどこまで縮められるか  - November 10, 2022](https://speakerdeck.com/bulbulpaul/bokutatiha-java-apurikesiyonnoqi-dong-su-du-wodokomadesuo-merareruka)

[Java Language: Project CRaC Coordinated Restore at Checkpoint - JDConf 2022](https://www.youtube.com/watch?v=GZ-uxWoFr6w)

[Java on CRaC: Superfast JVM Application Startup by Simon Ritter](https://www.youtube.com/watch?v=0evEs_3yaEI)

[Quality Outreach Heads-up – JDK 20: Thread.stop(), Thread.suspend() and Thread.resume() degradation JDK 20 (EAb22以後) でThread.stop()、Thread.suspend()、Thread.resume() はそれぞれの機能が削除され､UnsupportedOperationExceptionが出るように変更されているよ、というお話。- Logico Inside 2022/11/17](https://logico-jp.io/2022/11/17/quality-outreach-heads-up-jdk-20-thread-stop-thread-suspend-and-thread-resume-degradation/)

[Quality Outreach Heads-up – JDK 20: Disable the Legacy Parallel Class Loading Workaround … JDK 6で導入された並列クラスロードを許可する回避策がJDK 20で削除されたよ、というお話。- Logico Inside 2022/11/17](https://logico-jp.io/2022/11/17/quality-outreach-heads-up-jdk-20-disable-the-legacy-parallel-class-loading-workaround/)

[Native Image Quick Reference v2 GraalVM Native Image Quick Referenceの第2版ができたよ、というお話。- Logico Inside 2022/11/18](https://logico-jp.io/2022/11/18/native-image-quick-reference-v2/)

[JJUG CCC の Microsoft Build OpenJDK のコンテナ活用のベストプラクティスで説明時に利用しているサンプルとスクリプト](https://github.com/yoshioterada/MS-Build-OpenJDK-Container-Best-Practice)

[JJUG CCC 2022 Fall 視聴ページ](https://ccc2022fall-viewer.java-users.jp/)

[JJUG CCC 2022 Fall【Track A】](https://www.youtube.com/watch?v=5Hu3SBNIJSI)

[JJUG CCC 2022 Fall【Track B】](https://www.youtube.com/watch?v=l9Hf0VBu4RE)

[JJUG CCC 2022 Fall【Track C】](https://www.youtube.com/watch?v=DWzF3nxI9Ok)

[JJUG CCC 2022 Fall【Track D】](https://www.youtube.com/watch?v=cRkyUK2RDfE)

[2022-11-27 JJUG CCC 2022 Fall](https://www.youtube.com/playlist?list=PLy44EKO1L0eIl0VIYmGXk9635j6QQ7cF0)

[ 日本Javaユーザーグループ 最近アップロードされた動画](https://www.youtube.com/@java6566/videos)


[FizzBuzzで学ぶJavaの進化 - JJUG CCC 2022 Fall](https://www.slideshare.net/toranoana-lab/fizzbuzzjava)

[C 1500 河野裕隆 FizzBuzzで学ぶJava 7以降のJavaの進化](https://www.youtube.com/watch?v=aVxwcB652fc)

[Javaの入門が終わったら何の勉強をすればいいの？](https://speakerdeck.com/kishida/what-should-we-study-after-language)

[プログラミング言語の入門が終わったら何の勉強をすればいいの？  2022-11-27](https://nowokay.hatenablog.com/entry/2022/11/27/195003)

[JJUG CCC 2022 Fall ( #jjug_ccc ) - セッション資料の一覧 2022/11/27](https://yujisoftware.hatenablog.com/entry/jjug_ccc_2022_fall)

[A 1000 白栁隆司 非Javaエンジニアが「プロになるJava」で再勉強した話](https://www.youtube.com/watch?v=r1r6VEgfVb4)



[A 1100 森藤賢司LINE LINE NEWSにおけるJava移行の5年間の歩みとこれから](https://www.youtube.com/watch?v=XTvxIIyrNM4)

[LINE NEWSにおけるJava移行の5年間の歩みとこれから](https://speakerdeck.com/line_developers/five-years-of-java-migration-and-the-future-of-line-news)


[A 1025 浅野正貴 Git 未経験者が GitHub Actions で CI CD できるようになるまで](https://www.youtube.com/watch?v=TuQcYJwQ3Q4)

[Git 未経験者 が GitHub Actions で CICD できるようになるまで](https://speakerdeck.com/mackey0225/20221127-jjugccc-2022-fall-git-beginner-built-cicd-pipeline-with-githubactions)



[A 1230 多田真敏 入門：テスト技法とJUnit](https://www.youtube.com/watch?v=_7nkOxyO4fU)

[入門: テスト技法とJUnit](https://www.docswell.com/s/MasatoshiTada/K6R995-junit-intro)


[A 1330 野中翔太カサレアル 未来を見据えた CI CD ～ 10年後も使える ビルド・テスト パイプライン ～](https://www.youtube.com/watch?v=msC04lnwKXA)



[A 1600 濵田 健サイボウズ 組織と技術の両輪で開発を加速させるkintoneチームの取り組み](https://www.youtube.com/watch?v=9-XGMnYbDt4)

[JJUG CCC 2022 Fall Cybozu kintone / 組織と技術の両輪で開発を加速させるkintoneチームの取り組み](https://speakerdeck.com/itchyny/zu-zhi-toji-shu-noliang-lun-dekai-fa-wojia-su-saserukintonetimunoqu-rizu-mi)

[B 1330 清家蒼一朗シンプレックス gaugeで学ぶ実行可能ドキュメントの価値](https://www.youtube.com/watch?v=ykIj8IKBgns)

[Gaugeで学ぶ実行可能ドキュメントの価値](https://www.docswell.com/s/Simplex/K1DX45-2022-11-25-134839)
 
[C 1330 菊池信太郎ビズリーチ ユーザー数100万人規模の事業成長を止めずに、レガシーコードと戦う](https://www.youtube.com/watch?v=QCluKNE6th0)



[C 1525 orekyuu Fargate上のJVMからCPUを認識するまで 〜正しく認識されないCPUの謎を追え〜](https://www.youtube.com/watch?v=d2eNNMgIwL0)



[D 1330 大城夏樹テクマトリックス Java開発ツールのあれこれ ～便利そうなツールを色々集めてみた～](https://www.youtube.com/watch?v=nXR-wF8WKxQ)



[D 1500 梶紳之介 脆弱性対応を支える技術](https://www.youtube.com/watch?v=75hjH9Bnv_I)

[脆弱性対応を支える技術/20221127_JJUG-CCC-2022-Fall](https://speakerdeck.com/skaji18/20221127-jjug-ccc-2022-fall)

[D 1525 平井 一史 非同期メッセージングサービスを使ったLINEメッセージ配信の改善](https://www.youtube.com/watch?v=LzdYXODvKYw)

[非同期メッセージングサービスを使ったLINEメッセージ配信の改善](https://speakerdeck.com/policemankh/improve-oa-messaging-with-asynchronous-architecture)



[D 1600 疋田圭介CData クラウド時代のデータアクセス仮想化のススメ](https://www.youtube.com/watch?v=kQFocfI2kZs)

[ユーザー数100万人規模の事業成長を止めずに、レガシーコードと戦う / JJUG CCC 2022 Fall](https://speakerdeck.com/visional_engineering_and_design/jjug-ccc-2022-fall)

[D 1700 Christoph Engelbert PostgreSQL, The Time Series Database You Want](https://www.youtube.com/watch?v=tI9XzfGJOTY&list=PLy44EKO1L0eIl0VIYmGXk9635j6QQ7cF0&index=30)

[PostgreSQL: The Time-Series Database You (Actually) Want](https://www.slideshare.net/ChristophEngelbert/postgresql-the-timeseries-database-you-actually-wantpdf)
