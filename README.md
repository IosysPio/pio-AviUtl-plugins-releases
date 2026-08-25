# Effekseer Object Plugin for AviUtl ExEdit2

AviUtl ExEdit2の拡張編集タイムライン上に、[Effekseer](https://effekseer.github.io/)で
制作したパーティクルエフェクト(`.efk`ファイル)をオブジェクトとして配置し、
再生・合成できるようにするプラグインです。

**このリポジトリは、配布物(バイナリ)の公開専用です。ソースコードは含まれていません。**

## ダウンロード

最新版は [Releases](../../releases) から `EffekseerObject.au2pkg.zip` をダウンロードしてください。

## インストール方法

1. ダウンロードした `EffekseerObject.au2pkg.zip` を、AviUtl ExEdit2のプレビュー画面に
   ドラッグ&ドロップしてください。
2. インストール前に、本ソフトウェアのライセンス条件(無保証・再配布禁止など)が
   確認ダイアログに表示されます。内容にご同意いただける場合のみ、インストールを
   進めてください。

詳しい使い方・動作環境・既知の制限事項は、zip内の `README.txt` をご覧ください。

## Effekseerとは

Effekseerは、ゲーム等で使われる無料のパーティクルエフェクト制作ツールです。
専用のエディタで炎・爆発・魔法陣・光の粒子などの視覚エフェクトを作成し、`.efk`
ファイルとして出力できます。Unity/Unreal Engine/Godotなど主要なゲームエンジン向けに
ランタイムが提供されており、VRプラットフォームではVirtualCastが採用しています。

公式サイト: https://effekseer.github.io/

## 対応するEffekseerバージョンについて

本プラグインが内部で使用しているEffekseerランタイムは1.8系列(最新版)ですが、
動作確認はEffekseer 1.7系列で作成された`.efk`ファイル(VirtualCastが対応する範囲と
同じ)に限定しています。1.8系列以降で追加された新機能を使用したエフェクトでの
動作は未検証です。

## ライセンス

本ソフトウェアはバイナリ形式でのみ配布されます(ソースコード非公開)。
作者の許可のない再配布・改変配布は禁止です。本ソフトウェアは現状有姿(AS IS)で
提供され、一切保証されません。利用は自己責任でお願いします。

詳細は [LICENSE.txt](./LICENSE.txt) をご確認ください。

本ソフトウェアが内部で利用しているオープンソースソフトウェア(Effekseer、
AviUtl ExEdit2 Plugin SDK、いずれもMIT License)の著作権表示は
[THIRD_PARTY_NOTICES.txt](./THIRD_PARTY_NOTICES.txt) に記載しています。

## 作者

Iosys Pio

- https://piolabopages.pages.dev/tools/
- X: [@iosysandpio](https://x.com/iosysandpio)
- Bluesky: [@iospio.bsky.social](https://bsky.app/profile/iospio.bsky.social)
- Misskey: [@pio@vcasskey.net](https://vcasskey.net/@pio)
