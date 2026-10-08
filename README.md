# 森羅道中 街道（Aoi Walk: Kaido）── 関東の街道を歩く（試作）

> 2026-10-05 に名前を改めました（旧名《Qualium in Kaido》）。Qualium は、この作品の考え方の名前として使います。

五街道（東海道・中山道・日光街道・甲州街道・奥州街道）の関東の区間を、一つの地図で歩くアプリ。宿場ごとに「見る → 碧の話 → 見直す」の順で、地形・水・木（自然）／道と人の営み（歴史）／言葉と祈り（文化）を重ねる。案内は碧（あおい）。碧は mitsulab の AI。

公開先：https://mitsulab-soil.github.io/qualium-in-kaido/

## 試作であること（確かめている途中）

- **くわしい札（16 か所）の事実は、いまは Wikipedia の記事（版の番号つきリンク）だけを根拠にしている。** 自治体・文化庁などの公式の資料で確かめ直している途中。△ の印の行は、とくに公式で確かめていないもの。
- ほかの宿（56 か所）は、名簿の事実と計算値（標高・高低差・道のり）を出す。
- 宿の位置のうち ◐ の印のものは町名の代表点で、宿の中心から数百 m ずれることがある。
- 道のりは、いまの旧街道の道（OpenStreetMap の線）に沿って測った値で、江戸時代の里程とは数 % ずれる。線の無い区間は宿と宿を直線でつないでいる（点線）。

## AI であること

碧は AI。確かめた事実だけを話し、土地を診断せず、昔の人の気持ちを代わりに言わない。会話や位置は保存しない（「ここに来た」の日付だけを、この端末の中に残す）。

## 出典・クレジット

- 地図：[国土地理院 地理院タイル（淡色地図）](https://maps.gsi.go.jp/development/ichiran.html)。標高・高低差：国土地理院 標高 API。位置の確かめ：国土地理院の住所検索・逆ジオコーダ。出典：国土地理院
- 道の線・道のり：© [OpenStreetMap contributors](https://www.openstreetmap.org/copyright)（ODbL）。旧東海道・中山道・日光道中・甲州道中の relation をもとに mitsulab が計算した
- 宿場の名簿・順番・くわしい札の事実：Wikipedia 日本語版の各記事（「東海道五十三次」「中山道六十九次」「日光街道」「甲州街道」「奥州街道」ほか。アプリの中に、行ごとに版の番号つきのリンクを付けた）。**CC BY-SA の文章は写さず、事実だけを短く書き直した**
- 里程：東海道＝『東海道宿村大概帳』の値（Wikipedia の表による）
- 碧の 3D：VRoid Studio で作った碧（作者 mitsulab）。表示＝[three.js](https://threejs.org/)・[@pixiv/three-vrm](https://github.com/pixiv/three-vrm)・地図＝[Leaflet](https://leafletjs.com/)

## 利用について

- ページの文・構成は © 2026 mitsulab。リンクは歓迎。
- 碧の 3D モデル（`web/aoi.vrm`）は、このアプリで碧を表示するためにだけ置いている。**作者（mitsulab）のみ利用・再配布しない・改変しない**の条件（VRM のメタ情報）。取り出して使わないでください。

作：mitsulab　https://mitsulab.jp

## 碧の声

碧の声：VOICEVOX:冥鳴ひまり（AI の合成音声。[VOICEVOX](https://voicevox.hiroshiba.jp/)）。宿場の名・人の名・地名は、自治体の公式や辞典で読みを確かめた文だけを声にしています。声は押したときだけ鳴ります。

## 著作権 ／ Copyright

© 2026 mitsulab. All rights reserved. この作品の文章・画像・音声・3D・プログラムの著作権は、別に示した他者の素材を除き mitsulab にあります。無断の複製・転載・改変と、AI の学習・生成への利用はお断りします（テキスト・データマイニングの権利を留保します）。[利用規約](https://mitsulab.jp/terms/#ai)

© 2026 mitsulab. All rights reserved. Copyright in the text, images, audio, 3D and software of this work belongs to mitsulab, except third-party materials credited separately. Copying, reposting or modifying them without permission, and using them for AI training or generation, are not permitted. Text and data mining rights are reserved. [Terms](https://mitsulab.jp/terms/#ai-en)

他者の素材（CC BY・ODbL・CC0・VOICEVOX など）は、それぞれの条件に従います。
