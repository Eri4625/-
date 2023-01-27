# 教えて統計先生
このアプリは大学内の課題で1ヶ月間で作成したアプリです。<br>
私自身統計学を勉強していますが, 公式などをたまに忘れてしまい, その度に多くの時間を割いて検索する時間を割くのはとても非効率的であると感じ, この統計アプリを作成しました.<br>
まだ初歩的な段階であり, 私が思い描く完全なものにはなっていませんが, 形にすることはできたので提出させていただきます.

## 使用機器, アプリとバージョン
- MacBook Air Retina, 13-inch, 2020 Ventua 13.1
- Xcode 14.2
- iOS 16.3 iPhone 11 Pro

## 使用方法
本zipファイルをダウンロードし, Xcodeで「教えて統計先生.xcodeproj」を開くことで使用することできます.

## 学習コンテンツの追加方法
学習リスト(Learn_contents)の「.init(text: "coming soon", file: AnyView(Coming_soon()))」のtextはドキュメント名, fileは遷移先となっています.<br>
そのため, 最初は「Coming_soon()」の中身を自身で書いてみることをお勧めします. 多くの遷移先を導入する場合は, 「LearnContents.swift」内に記入していくのが良いでしょう.<br>
また, 「Library.swift」の中身には様々なライブラリを導入していますので, ぜひご確認の上使用して見てください.(そこにライブラリを追加するのも良しです)<br>
遷移先のViewの設定の後, 学習名を出力する配列(chapter)にディレクトリ名を記入しましょう.

## 問題コンテンツの追加方法
「ProblemBank.json」に問題を入力していくのみで, 問題が追加されます. 但し, 注意点として選択問題であれば選択問題, 記入問題であれば記入問題のみの問題群にしなければ所望の問題群を作成することができません.<br>
そのため, 「ProblemBank.json」にどのように問題が記入されているかを確認してから, 入れたい問題を入力していくのが良いでしょう.

## 参考文献
- Rambling and Delving , 「[[SwiftUI] JSONファイルをSwiftUIでDecodeし、Viewで活用する方法 (ObservableObject)](https://www.harubears.com/ja/tech-ja/swiftui-ja/how-to-decode-json-display-view-observableobject/)」, (最終閲覧日: 2023年1月26日)
- ちょげぶろぐ, 「[[SwiftUI]Buttonの押している間のスタイルを設定](https://www.choge-blog.com/programming/swiftuibuttonispressedstyle/)」, (最終閲覧日: 2023年1月26日)
- Qiita「[SwiftUI NavigationLink 配列で他のContentViewへ遷移する話 ? その2
sell
](https://qiita.com/papassan/items/2ea7d8c0f1b73ab851dc)」, (最終閲覧日: 2023年1月26日)
- stack overflow, 「[How Can I create a math formula text view with LaTeX in SwiftUI](https://stackoverflow.com/questions/65090289/how-can-i-create-a-math-formula-text-view-with-latex-in-swiftui)」, (最終閲覧日: 2023年1月26日)
- Developer, 「[Remove the scroll in WebKit View](https://developer.apple.com/forums/thread/134112)」, (最終閲覧日: 2023年1月26日)
- note, 「[[SwiftUI] Viewをスライドさせて入れ替える](https://note.com/yogox/n/n3893b8f8cecc)」, (最終閲覧日: 2023年1月26日)
- Sarunw, 「[How to render text with a color gradient in SwiftUI
](https://sarunw.com/posts/how-to-render-text-with-color-gradient-in-swiftui/)」, (最終閲覧日: 2023年1月26日)
- カピ通信, 「[【SwiftUI】アラートの使い方（alert）](https://capibara1969.com/3757/)」, (最終閲覧日: 2023年1月26日)
- .NET ゆる〜りワーク, 「[【SwiftUI】角丸ボタンの作り方](https://www.yururiwork.net/archives/1200)」, (最終閲覧日: 2023年1月26日)
- Tomato Develop, 「[【SwiftUI】バイブレーション(Vibration)の実装【12種類のパターンを紹介】
](https://tomato-develop.com/swiftui-vibration-how-to-complement/)」, (最終閲覧日: 2023年1月26日)
- カピ通信, 「[【SwiftUI】ScrollViewの使い方](https://capibara1969.com/2664/)」, (最終閲覧日: 2023年1月26日)
- ちょげぶろぐ, 「[[SwiftUI]Picker(ピッカー)のスタイル一覧](https://www.choge-blog.com/programming/swiftuipickerstylelist/)」, (最終閲覧日: 2023年1月26日)
- ちょげぶろぐ, 「[[SwiftUI]Picker(ピッカー)の値の変更を検知するには？](https://www.choge-blog.com/programming/swiftuipickervalueonchanged/)」, (最終閲覧日: 2023年1月26日)
- Swift Life, 「[[SwiftUI] Picker の使用方法](http://swift.hiros-dot.net/?p=1535)」, (最終閲覧日: 2023年1月26日)
- カピ通信, 「[【SwiftUI】Pickerの使い方](https://capibara1969.com/1684/)」, (最終閲覧日: 2023年1月26日)
- SerialCorder.dev, 「[Presenting Sheets Of Various Heights In SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/presenting-sheets-of-various-heights-in-swiftui/)」, (最終閲覧日: 2023年1月26日)
- Qiita, 「[SwiftUIアプリに検索機能を追加して、検索候補を提供（.searchable）（iOS 15）](https://qiita.com/MaShunzhe/items/0ad7a3e1c15d2a996c9e)」, (最終閲覧日: 2023年1月26日)
