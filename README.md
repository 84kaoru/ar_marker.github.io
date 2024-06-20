https://84kaoru.github.io/ar_pazzle.github.io/


1.FBX→gtlfは実行パスを記載　＄FBX2glTF-darwin-x64までのパス fbxまでのパス

2.マーカーは認識できる黒線の幅を調整

3.変換したgltfをbinファイルと共にzip→ar.js studioに適当な写真と共にアップロード
新たなgltfファイルをゲット　それをフォルダに入れる

# 使い方

## マーカーを変更したい場合
1. [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)に画像をアップロード
※pattern ratio は変更可能だが、マーカーの読み取り制度に影響が出る(デフォルト0.5が妥当)

2. マーカーのimgとmattファイルを保存

3. コード内の既存のmattファイルと差し替える

4. index.html内の`XXX.matt`を適切な名前に書き直す

## 3Dモデルを変更したい場合(元モデルがFBX形式の場合)
1. FBX2gLTFを使う→[FBX2glTF-darwin-x64をダウンロード](https://github.com/facebookincubator/FBX2glTF/releases)

2. `$ FBX2glTF (fbxファイルまでのパス)`を実行→XXX_outというファイルができるのでそれをzipする

3. [AR.js Studio](https://ar-js-org.github.io/studio/pages/marker/index.html)に適当な画像(使用するマーカーの画像で良い)とzipしたXXX_outをアップロード

4. Download packageでファイルをダウンロード

5. ダウンロードしたファイルの中からgLTF形式のファイルをコード内の既存のgLTFファイルと差し替える

6. index.html内の`XXX.gltf`を適切な名前に書き直す

