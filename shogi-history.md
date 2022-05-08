---
layout: page
title: "コンピュータ将棋大会参加履歴"
permalink: /shogi-history/
---

参加ソフト名は常に「ねね将棋」(NENE Shogi)。

* 2017-11-11 [第5回将棋電王トーナメント](http://denou.jp/tournament2017/)
  * 予選にて3勝5敗で32位（42チーム中）
  * 記事 https://select766.hatenablog.com/entry/2017/12/14/081930
  * Python言語でプログラム部分はほぼすべて自作。評価関数は、やねうら王で生成、配布された学習用棋譜を用いて教師あり学習。探索部は「芝浦将棋Softmax」で提案されたMonte Carlo Softmax Searchを実装。
* 2018-05-03 [第28回世界コンピュータ将棋選手権](http://www2.computer-shogi.org/wcsc28/)
  * 1次予選で5勝3敗（1不戦勝含む）で15位（40チーム中）
  * 記事 https://select766.hatenablog.com/entry/2018/05/07/222547
* 2019-05-03 [第29回世界コンピュータ将棋選手権](http://www2.computer-shogi.org/wcsc29/)
  * 1次予選で5勝3敗で10位（40チーム中）
  * 記事 https://select766.hatenablog.com/entry/2019/05/05/205225
* 2020-05-03 [世界コンピュータ将棋オンライン大会](http://www2.computer-shogi.org/wcso1.html)
  * 第30回世界コンピュータ将棋選手権は新型コロナウイルスの影響で中止
  * オンライン開催
  * 1日目で4勝4敗
  * 2日目で3勝5敗
* 2021-05-03 [第31回世界コンピュータ将棋選手権](http://www2.computer-shogi.org/wcsc31/)
  * オンライン開催
  * 1次予選で5勝3敗で11位（34チーム中）
  * 2次予選で3勝5敗1分で23位（30チーム中）
  * 記事 https://select766.hatenablog.com/entry/2021/05/05/181556
  * dlshogiを改造し、policyに対しKPPT型ソフトの最善手をブレンド。
* 2022-05-03 [第32回世界コンピュータ将棋選手権](http://www2.computer-shogi.org/wcsc32/)
  * オンライン・オフライン混合開催で、オフライン参加した
  * 2次予選（前年順位によるシードとして参加）で1勝7敗1分で27位（28チーム中）
  * 記事 https://select766.hatenablog.com/entry/2022/05/05/230100
  * iPad上で動作するソフトをSwift言語で新規に開発。機械学習専用チップNeural Engineを活用。評価関数は「強い将棋ソフトの作り方」のサンプルコードで学習したdlshogiベース。iPad上で動作するプログラムはすべて自作。
