# ページ
[https://84kaoru.github.io/ar_marker.github.io/](https://84kaoru.github.io/ar_marker.github.io/)

# 使い方

## 3Dモデルを変更する(元モデルがFBX形式の場合)
1. FBX2gLTFを使う→[FBX2glTF-darwin-x64をダウンロード](https://github.com/facebookincubator/FBX2glTF/releases)

2. `chmod +x FBX2glTF-darwin-x64`でFBX2glTF-darwin-x64を実行できるようにする(できない場合以下3の"FBX2gLTF"部分に実行ファイルまでのパスを記述)

3. `$ FBX2glTF "fbxファイルまでのパス"`を実行→XXX_outというファイルができるのでそれをzipする

4. [AR.js Studio](https://ar-js-org.github.io/studio/pages/marker/index.html)にマーカーにしたい画像とzipしたXXX_outをアップロード

5. マーカーのimgとmattファイルを保存

6. Download packageでファイルをダウンロード→arというzipができるので解凍

7. コード内の既存のpattファイルとgLTFファイルを差し替える


## オリジナルマーカーと3Dモデルを使ってパズルを作ろう→[https://84kaoru.github.io/pazzle.github.io/](https://84kaoru.github.io/pazzle.github.io/)
1. ダウンロードしたマーカーのimgをアップロード

2. 完成したらwebページで読み取る


## Reference
- [https://note.com/penciljapan/n/nd60297348526](https://note.com/penciljapan/n/nd60297348526)
- [https://qiita.com/dsudo/items/58718e9e3c870e6b92e6](https://qiita.com/dsudo/items/58718e9e3c870e6b92e6)
- [https://qiita.com/tichise/items/c0f331a9eeb5fb8c3763](https://qiita.com/tichise/items/c0f331a9eeb5fb8c3763)
