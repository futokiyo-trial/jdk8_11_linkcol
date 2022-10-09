# jdk8_11_linkcol


## Java8からJava11へ変更点に関する参考文献

[Java11による変更点](https://twitter.com/sugarlife/status/1073854073764376576)

[Java SE 8から11で何が起きたか](https://speakerdeck.com/miyakawataku/java-se-8-to-11)

[Java 8 から Java 11 への移行](https://docs.microsoft.com/ja-jp/azure/developer/java/fundamentals/transition-from-java-8-to-java-11)

[Java8からJava11への変更点](https://qiita.com/nowokay/items/1ce24079f4daafc73b4a)

[Java11へのマイグレーションガイド ~Apache Hadoopの事例~](https://www.slideshare.net/techblogyahoo/java11-apache-hadoop-146834504/)

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

[JDK 17の内部JDK要素の強力なカプセル化（JEP 403 Strongly Encapsulate JDK Internals,JEP 396 Strongly Encapsulate JDK Internals by Default） ](https://www.infoq.com/jp/news/2021/07/internals-encapsulated-jdk17/)

[Java17(Java13以降)でgraphemeをカウントする - abcdefg.....](https://pppurple.hatenablog.com/entry/2022/04/17/031646)

[Java17(Java13以降)でgraphemeをカウントするのJava SampleCode](https://github.com/pppurple/java_examples/blob/master/count-string-example/src/main/java/Main.java)

[文字列の長さを取得する方法：lengthとcodePointCountの使い分け｜Scalapedia](https://scalapedia.com/articles/8/%E6%96%87%E5%AD%97%E5%88%97%E3%81%AE%E9%95%B7%E3%81%95%E3%82%92%E5%8F%96%E5%BE%97%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95%EF%BC%9Alength%E3%81%A8codePointCount%E3%81%AE%E4%BD%BF%E3%81%84%E5%88%86%E3%81%91#%E3%82%B5%E3%83%AD%E3%82%B2%E3%83%BC%E3%83%88%E3%83%9A%E3%82%A2%E3%82%92%E5%90%AB%E3%82%80%E6%96%87%E5%AD%97%E5%88%97%E3%81%AE%E9%95%B7%E3%81%95%E3%82%92%E5%8F%96%E5%BE%97%E3%81%97%E3%81%A6%E3%81%BF%E3%82%8B)

[length／codePointCountメソッド | Javaコード入門](https://java-code.jp/189)

[nablarch core util StringUtil.java](https://github.com/nablarch/nablarch-core/blob/master/src/main/java/nablarch/core/util/StringUtil.java)

[Red Hat JBoss Enterprise Application Platform (EAP) 7 Supported Configurations](https://access.redhat.com/articles/2026253)

[Docker HubのOpenJDKイメージの利用を更新するためのアドバイス](https://rheb.hatenablog.com/entry/updating-docker-hubs-openjdk-image)

[Red Hat は Eclipse TemurinでJavaのサポートを拡大](https://rheb.hatenablog.com/entry/red-hat-expands-support-java-eclipse-temurin)

## Java18

[Java 18正式リリース。デフォルトのCharsetが「UTF-8」に、シンプルWebサーバ搭載など新機能](https://www.publickey1.jp/blog/22/java_18charsetutf-8web.html)

[JJUGナイトセミナー「Java 18 リリース記念イベント」](https://www.youtube.com/watch?app=desktop&v=fhIaKjfY5Bc&feature=youtu.be)

[Java 18新機能まとめ](https://qiita.com/nowokay/items/17d990aa8a5b1c5223c8)

[Java 18とAmberとValhallaとLoomの話の資料です。　Project Loomはコルーチンの実装ということになる](https://speakerdeck.com/kishida/java-18-new-feature-and-future)



