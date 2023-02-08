## マッキベン型人工筋肉　

[こちらのサイト](https://ishikawa-lab.sakura.ne.jp/yoichi/muscle_recipe)で公開しているマッキベン型人工筋肉のレシピと３Dプリントファイルを公開しています．
径のラインナップは3種類あり，上記サイト内や動画で説明しているのは，外径が9mmの一番大きいものについてです．

7mmと5mmの動画はありませんが，おおよその作り方は変わりません．
収縮率は9mmが30％なのに対して，少し控えめの15％と10％なので注意してください．
これで物足りない方には、さらに高性能なs-muscle社の細径人工筋肉をオススメします！ https://s-muscle.com

<font color="red"> NEW!! Coro @corone422 さんの改良版5mmレシピを追加しました．収縮率は20％ほど，0.8MPaを入れられるそうです．（2022/12/03） </font>

全ての径に対して金属かしめが必要ですが，かしめ用の工具は
- [アポロホースカシメ工具](https://www.monotaro.com/p/8848/9344/)　2290円

が共通で使用可能です．

### 【人工筋の材料】外径9mm（収縮率30％ほど）

- デンカエレクトロン　ほつれにくい編組チューブ　[NFL-9](https://www.monotaro.com/p/3506/8223/)　1m 648円
- モノタロウ　シリコンチューブ　[MGJG-8×10（内径8mm，外形10mm）](https://www.monotaro.com/p/2225/2536/?t.q=%22MGJG-8%81~10%22)　1m 279円
- エスコ　9-11mm ホースクランプ(ツーイヤー型/10個)　 [EA463AE-11](https://www.monotaro.com/p/4993/6617/)　506円
- SMC　ストレート KQ2H ミリサイズ　[KQ2H04-00A](https://www.monotaro.com/p/4138/4786/)　318円
- タミヤ　タミヤセメント（ABS用）　ITEM 87137　278円　…※３Dプリント品の積層痕を消すため
- ３Dプリント品　ABS製の栓：[リンク](https://github.com/Yoichi-Masuda/Art_muscles/blob/master/air_stopper.stl)
    - 一般的な熱積層方式の３Dプリンタで造形可能
    空気圧の漏れを防ぐため，インフィルは100％が理想
    - 「ピスコ(PISCO)　プラグ　PP4」と「SMC　ストレート KQ2H ミリサイズ　KQ2H04-00A」の組み合わせでも代用可能

### 【人工筋の材料】外径7mm（収縮率15％ほど）

- デンカエレクトロン　ほつれにくい編組チューブ　[NFL-6](https://www.monotaro.com/p/3506/8187/)　1m 439円
- タイガースポリマー　シリコンチューブ　[SR1554（内径5mm，外形7mm）](https://www.monotaro.com/p/3278/8402/) 1m　249円
- エスコ　7-9mm ホースクランプ(ツーイヤー型/10個入り)　 [EA463AE-9](https://www.monotaro.com/p/4993/6748/)　395円 
- コガネイ　クイック継手ミニタイプ TSシリーズ ストレート [TS4-M5M](https://jp.misumi-ec.com/vona2/detail/221000065534/?PNSearch=TS4-M5M&HissuCode=TS4-M5M&searchFlow=suggest2products&Keyword=TS4-M5M&list=SuggestPreview) 単価188円

- 3Dプリント品
    - UV硬化レジン製の継手：[リンク](https://github.com/Yoichi-Masuda/open_artificial_muscles/blob/master/thin_muscle/coupler_M5.stl)
    - UV硬化レジン製の栓：[リンク](https://github.com/Yoichi-Masuda/open_artificial_muscles/blob/master/thin_muscle/cap_M5.stl)
        - 3Dプリント品の継手にはネジがモデリングされていますが，造形後にM5タップでネジをさらった方が簡単かつ，空気の漏れなく組み立てが可能です．
        - 7mmと5mmの人工筋のパーツのみ，光硬化式プリンタで造形する必要があります．レジンは[こちら](https://www.amazon.co.jp/dp/B09H2XZTSK)を推奨します．


### 【人工筋の材料】外径5mm（収縮率10％ほど）

- デンカエレクトロン　ほつれにくい編組チューブ　[NFL-3](https://www.monotaro.com/p/3506/8144/)　1m 359円
- タイガースポリマー　シリコンチューブ　[SR1554（内径3mm，外形5mm）](https://www.monotaro.com/p/3278/8244/) 1m　179円
- エスコ　5-7mm ホースクランプ(ツーイヤー型/10個入り)　 [EA463AE-7](https://www.monotaro.com/p/4993/6732/)　395円 
- コガネイ　クイック継手ミニタイプ TSシリーズ ストレート [TS3-M3M](https://jp.misumi-ec.com/vona2/detail/221000065534/?PNSearch=TS3-M3M&HissuCode=TS3-M3M&searchFlow=suggest2products&Keyword=TS3-M3M&list=SuggestPreview) 単価195円

- 3Dプリント品
    - UV硬化レジン製の継手：[リンク](https://github.com/Yoichi-Masuda/open_artificial_muscles/blob/master/thin_muscle/coupler_M3.stl)
    - UV硬化レジン製の栓：[リンク](https://github.com/Yoichi-Masuda/open_artificial_muscles/blob/master/thin_muscle/cap_M3.stl)
        - 3Dプリント品の継手にはネジがモデリングされていますが，造形後にM3タップでネジをさらった方が簡単かつ，空気の漏れなく組み立てが可能です．造形時に空気穴が塞がってしまうことがありますが，Φ1mmのドリルで追加工して使用することが可能です．
        - 7mmと5mmの人工筋のパーツのみ，光硬化式プリンタで造形する必要があります．レジンは[こちら](https://www.amazon.co.jp/dp/B09H2XZTSK)を推奨します．

外径5mmの人工筋は，接続するエアチューブ（ポリウレタンチューブ）の外径が3mmであることに注意してください（[外径3mmのポリウレタンチューブの例](https://www.monotaro.com/p/5815/5517/) 1mあたり約40円程度）

### 3Dプリント品とクイック継手の接続

外径7mm,外径5mmの人工筋は，製作前に3Dプリント品のネジにクイック継手をあらかじめ接続しておきます（写真参照）．このことに加え，栓にABS用の接着剤が不要であること以外は，動画でも説明されている外径9mmの人工筋の製法と同様です．

<img src="https://user-images.githubusercontent.com/98135132/205851925-890debe0-d741-4478-b136-ea0e033ab6d4.JPG" width="320px"><img src="https://user-images.githubusercontent.com/98135132/205851935-14de6e83-9328-44b9-b2f0-9a00e548cae0.JPG" width="320px">

### 径ごとの性能差

上記のラインナップのうち，外径が5mmの最小のものについては，他の人工筋に比べて収縮率が低くなっています．編組チューブの編み方やシリコンチューブの厚みによって，収縮率は変化するため，異なる製品や厚みでの細径人工筋の検討を我々も行っています．是非良い改善，検討案などがあればアドバイスいただけると幸いです．

## みなさんの改良版レシピ
### [@corone422](https://twitter.com/corone422/status/1598710760959782912?s=20&t=0VL1ZC6_-5MBRaOd5uCATQ)さんの細径マッキベン（外形5mm）
[@corone422](https://twitter.com/corone422/status/1598710760959782912?s=20&t=0VL1ZC6_-5MBRaOd5uCATQ)さんが5mmマッキベンのレシピを改良してくださいました．収縮率は20％ほどだそうです．
動作中の様子は[こちら](https://twitter.com/corone422/status/1587334103325880320?s=20&t=0VL1ZC6_-5MBRaOd5uCATQ)．

<img src="https://user-images.githubusercontent.com/98135132/205417713-2e496da9-1768-4219-a373-cf938346c8f0.png" width="640px"><img src="https://user-images.githubusercontent.com/98135132/205418053-0f69b856-b75e-481e-9a24-5adf3a202efd.png" width="320px">

> Coro @corone422 [午前1:56 · 2022年12月3日](https://twitter.com/corone422/status/1598722900210900992?s=20&t=0VL1ZC6_-5MBRaOd5uCATQ)
> - スリーブは https://monotaro.com/p/3506/8205/
> - シリコンチューブは https://monotaro.com/p/3473/9336/
> - カシメは https://monotaro.com/g/02398866/
> 
> それで従来のレシピですとストレートをジョイントに使っていますが、改良した方はシリコンホースそのものを埋め込みました。止栓は光造形で直径4mmの棒を作りました。【続く】

> Coro @corone422 [午前10:45 · 2022年12月3日](https://twitter.com/corone422/status/1598855958742306816?s=20&t=0VL1ZC6_-5MBRaOd5uCATQ)
> シリコンチューブとポリウレタンチューブの摩擦を利用してうまく止まっているような感じになりますね。なのでカシメの時にひらべったく潰れちゃうので、耳と耳を工具で挟み、チューブを丸く戻し> > てあげる作業だけ必要になってきます。

チューブがつぶれないように、[インサートリング](https://www.monotaro.com/p/3531/4526/?t.q=%83C%83%93%83T%81%5B%83g%83%8A%83%93%83O)を入れればいいかもしれません．
締結力も上がるはず．
