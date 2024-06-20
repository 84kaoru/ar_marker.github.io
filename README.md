# ページ
[https://84kaoru.github.io/ar_marker.github.io/](https://84kaoru.github.io/ar_marker.github.io/)

# 使い方

## マーカーを変更する
1. [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)に画像をアップロード
※pattern ratio は変更可能だが、マーカーの読み取り制度に影響が出る(デフォルト0.5が妥当)

2. マーカーのimgとmattファイルを保存

3. コード内の既存のmattファイルと差し替える

4. index.html内の`XXX.matt`を適切な名前に書き直す
   

## 3Dモデルを変更する(元モデルがFBX形式の場合)
1. FBX2gLTFを使う→[FBX2glTF-darwin-x64をダウンロード](https://github.com/facebookincubator/FBX2glTF/releases)

2. `chmod +x FBX2glTF-darwin-x64`でFBX2glTF-darwin-x64を実行できるようにする(できない場合以下3の"FBX2gLTF"部分に実行ファイルまでのパスを記述)

3. `$ FBX2glTF "fbxファイルまでのパス"`を実行→XXX_outというファイルができるのでそれをzipする

4. [AR.js Studio](https://ar-js-org.github.io/studio/pages/marker/index.html)に適当な画像(使用するマーカーの画像で良い)とzipしたXXX_outをアップロード

5. Download packageでファイルをダウンロード

6. ダウンロードしたファイルの中からgLTF形式のファイルをコード内の既存のgLTFファイルと差し替える

7. index.html内の`XXX.gltf`を適切な名前に書き直す


## オリジナルマーカーと3Dモデルを使ってパズルを作ろう→[https://84kaoru.github.io/pazzle.github.io/](https://84kaoru.github.io/pazzle.github.io/)
1. ダウンロードしたマーカーのimgをアップロード

2. 完成したらwebページで読み取る


## Reference
- [https://note.com/penciljapan/n/nd60297348526](https://note.com/penciljapan/n/nd60297348526)
- [https://qiita.com/dsudo/items/58718e9e3c870e6b92e6](https://qiita.com/dsudo/items/58718e9e3c870e6b92e6)
- [https://qiita.com/tichise/items/c0f331a9eeb5fb8c3763](https://qiita.com/tichise/items/c0f331a9eeb5fb8c3763)

