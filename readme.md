# AHNSツールバーとは？
アドオン制作者が主催しているNetSimutrans「AHNS」において使用されているツールバーです。

# 導入方法
1. AHNSツールバーをダウンロードする
1. zipを解凍する
1. pakフォルダの名前を導入するpakの名前に合わせ、そのフォルダを実行ファイルのあるフォルダにコピペする
1. (本体バージョンがOTRPv30以前の場合のみ)(pakset)/menuconf.tabを(pakset)/menuconf/forOTRPv29.tabに置き換える

# 使用条件
ahakuoku simutrans addon license version 3.2 (ASAL 3.2)を適用します。

## ASAL 3.２全文
利用者は、次の条件を守ることでこのアドオン・ツール等（以下、本作品）を自由にご利用いただけます。

### していいこと
- ソースがある場合の本作品の改変
- 改変をした場合の本作品の再配布

### しなければならないこと
- 本作品を再配布する際の本作品作者名表記
- 本作品を上書きするアドオンの配布時に、その旨を周知する事（Pakset配布の必要がある場合を除く）
- 本作品が改造品だった場合は、原作品のライセンスに従う事

### してはいけないこと
- 本作品の自作宣言
- 本作品の無改造再配布（Pakset配布の必要がある場合を除く）
- 本作品の営利目的での利用
- ソースがない場合の本作品の改変や再配布

### その他細則
- Pakset配布の必要がある場合とは、NSやセーブデータ配布などのことを指します。
- 本作品を利用したことによる損害は一切責任を負いません。
- 本作品の作者は、本規約に違反したユーザーを除き、特定のユーザーに対して不利に差別的な取り扱いを行ってはならないものとします。

# 内容
AHNS仕様のツールバーpak
menuconf 2種類(OTRP最新版向けとOTRPv30系以前向け)

## menuconfの変更方法
(pakset)/menuconfにある任意のtabファイルで(pakset)/configにあるmenuconf.tabを置き換えてください。

# ショートカットキー
ゲーム内のヘルプをご確認ください。

# 謝辞
本アドオンの制作にあたり、次のアドオンを参考・改変させていただきました。
- [ぼくのかんがえたさいきょうのメニューアイコン](https://ux.getuploader.com/Twitrans_Forge/download/49)（くるり様）
- [Pak256のメニューバー](http://www.pak256.simutrans.info/)（ふぃすたむ様　ソースは特別に提供いただいたものです）
- [らくらくクリックくん](https://simutrans.sakura.ne.jp/portal/articles/rakuraku_menuicon_ver2_1)（Ayura様）
- [KPI_menubars](https://simutrans.sakura.ne.jp/portal/articles/kpi_menubars_versions3)（かみやん様）

その他、多数の方からアドバイスをいただきました。  
感謝申し上げます。

# 更新履歴
現在の最新バージョンは、Version 1.2.1です。

## Version 1.2.1(2023/7/7)
- 箱積みツールを専用のダイアログに分離しました。

## Version 1.2.0(2022/03/25)
- インフラ系ツールにて、クリック回数を削減しました。
  - これに伴い、通常版とシンプル版を統合しました。
- 鉄道ツールと市電ツールを分離しました。
- スクリプトツールなど一部ツールについて、「いろいろツール」などへの隔離をしました。
- 「いろいろツール」のアイコンを変更しました。
- 常時表示の上部ツールバーに、ライバル会社一覧を追加しました。
- 船舶架線の撤去ツールを追加しました。
- 鉄道駅舎のうち、建物系をすべて特殊建築物に分離しました。
- 人口増加ツールに、+1000人と+10000人を追加しました。
- マップに重大な影響を及ぼすおそれのある操作に対して、警告画面を表示するようにしました。
- 線路占有解除ツールと線路占有確認ツールを統合しました。
- KUTAとOTRP v32で追加・変更された一部機能に対応しました。
  - これに伴い、OTRP v30系までの本体で使用するにはmenuconf.tabをmenuconf/forOTRPv29.tabで置き換える必要があります。

## Version 1.1.0(2020/02/27)
- 複数のショートカットキーを追加しました。
- マップ編集ツールを公共事業以外でも使用できるようにしました。
- (シンプル版のみ)マップ閲覧に関する便利機能をタブの中にまとめました。
- 飛行機ツールの一部機能が使用できない問題を修正しました。
- 軽便鉄道の一部機能が使用できない問題を修正しました。

## Version 1.0.0(2021/01/06)
- 公開バージョンでは初のバージョンです。
