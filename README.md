# PIP’S HIDDEN TOWN — A Journal of Little Stories

全20ステージ・100か所の違い。PIPと訪れる景色を、それぞれ独立した描き下ろしの構図で制作しました。

1. The Apricot Bakery / アプリコット・ベーカリー
2. The Glasshouse Florist / 花屋の温室
3. The Stargazer’s Attic / 星見の屋根裏
4. The Lantern Library / ランタン図書館
5. The Tidepool Field Station / 潮だまりの観測所
6. The Cloudtop Airmail / 雲の上の郵便局
7. The Snowglobe Toyshop / スノードーム玩具店
8. The Autumn Cider Mill / 秋のりんご水車小屋
9. The Coral Aquarium / さんごの水族館
10. The Travelling Circus / 旅するサーカス
11. The Mountain Cable Station / 山のケーブル駅
12. The Moonlit Bathhouse / 月あかりの湯屋
13. The Desert Caravan / 砂漠のキャラバン市場
14. The Mushroom Kitchen / きのこの台所
15. The Paper Kite Festival / 紙だこの丘のお祭り
16. The Old Film Studio / 古い映画の撮影所
17. The Honey Orchard / はちみつ果樹園
18. The Rainy Music Arcade / 雨の音楽アーケード
19. The Fossil Conservatory / 化石の博物館
20. The Firefly Boathouse / ほたるの舟小屋

時間制限なし。英語・日本語、楽しい合成BGMと効果音、連動する拡大表示、2段階ヒント、章別の保存記録、思い出カードを備えます。街の案内は5章ずつのページ表示です。

元の3章の保存記録も引き継ぎます。やり直しは選択した章だけを消去します。旧PIP作品と既存9作品は変更しません。

## 起動と追加

必要な追加パッケージはありません。

- 起動: node serve.cjs → http://127.0.0.1:4202/?lang=ja
- 検証: node test.cjs
- 新章追加: chapters.jsonの末尾に追加し、node build-chapters.cjs。詳しくはADDING-STAGES.md。

## iPhone確認手順

Safariで公開URLを開き、案内の1–5/6–10/11–15/16–20から章を選択します。上下どちらの絵でも違いをタップできます。小さい違いは「拡大して見る」から指で移動して探せます。ヒントを2回押すと場所も示します。5つ発見したら思い出のカードと次の章へ。再読込後も発見記録が残ること、音の切替とアプリ切替後の復帰を確認してください。今回の追加章はブラウザで検証済みですが、iPhone実機の最終確認は所有者によるものです。

## Playables

既存のSDKライフサイクル・音声・クラウド保存アダプターを維持し、保存可能な章数を可変にしました。模擬SDKで20章目の保存と読込を検証済みです。公式ホストでの再認証・YouTube承認を示すものではありません。

## 制作資料とバックアップ

ART-DIRECTION.md: 原画・変更画・生成プロンプト。TEST-RESULTS.md: 検証記録。追加前の3章版はローカルのPIPS-HIDDEN-TOWN-before-20-stages.zipに保存し、GitHubの旧コミットにも残ります。
