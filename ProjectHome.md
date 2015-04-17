[![](http://pk.aiit.ac.jp/image/vc.gif)](http://pk.aiit.ac.jp/avc)
使い方は[AIIT Video Chat ポータルサイト](http://pk.aiit.ac.jp/avc)へ

## 概要 ##
AIIT Video Chat は、オープンソースソフトウェアを利用して
開発されたビデオチャットアプリケーションです。

サーバサイドにRed5［1］クライアントアプリケーションにFlex［2］を採用し、
ソーシャルアプリケーションプラットフォーム［3］上での動作を前提としています。

  * ［1］ Red5 (Server Side) http://osflash.org/red5 http://www.red5.org/
  * ［2］ Adobe Flex (Client Side) http://opensource.adobe.com/flex/
  * ［3］ 現在はmixiアプリのみに対応 http://developer.mixi.co.jp/appli

このアプリケーションは社会人向け大学院である産業技術大学院大学［4］の
PBL（Project Based Lerning）の一環として開発が行われています。
  * ［4］ 産業技術大学院大学 http://aiit.ac.jp/

## デモ ##
mixiアプリとして開発されているため、mixiアカウントをお持ちの方であれば
下記のページから今すぐ試すことができます。
  * mixiアプリ「ビデオチャット」 http://mixi.jp/view_appli.pl?id=4091

## 特徴 ##
  * 複数人同時によるビデオチャットが可能です
  * ビデオウィンドウのサイズ調整が可能です
  * 音声レベルメータがついているため誰が喋っているのかがすぐにわかります
  * ソーシャルアプリケーションとして開発されているため、参加コミュニティが部屋になります

## アーキテクチャ概要 ##
AIIT Video Chat は主に4つの構成から成り立っています
  1. クライアントアプリケーション（Adobe Flex）
  1. サーバサイドアプリケーション（Red5）
  1. サーバサイドバックエンドアプリケーション（Google App Engine）
  1. ソーシャルアプリケーションガジェット（Open Social）
> > ![![](http://iimp.jp/images/system_arhchitecture_thumb.jpg)](http://iimp.jp/images/system_arhchitecture.jpg)


<a href='Hidden comment: 
== Introduction ==
This porject is based on the activities in the Advanced Institute of Industrial Technology, Tokyo Japan.
All the members are working in the day, and developing from 9 at night till 9 in the morning every day.

== About this tool ==
This software is a Flash communication tool, with which you can talk to your friends video to video, chat with the rich texts, and search new friend somewhere away.
We want to innovate the way to communicate, but now on the way.

== Technology ==
We are developing in Java, ActionScript, Flex and Python.
And we have chosen
* Red5 as a media server.
* Terracotta as a Object-sharing Server

'></a>