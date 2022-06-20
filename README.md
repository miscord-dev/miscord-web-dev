# miscord-web-dev

## 使い方
hugo を利用しています。

hugo をインストール
```
brew install hugo
```

ローカルでのテスト
```
hugo server
```

```-D ```オプションを付けることで、下書きの記事も表示できるようになります。
```
hugo server -D
```


## リポジトリの更新の仕方
mainブランチが更新されると、自動的に [miscord-dev/miscord-dev.github.io](https://github.com/miscord-dev/miscord-dev.github.io) へとデプロイされるようになっています。

- contentの追加・修正  
mainブランチでそのまま作業しても大丈夫です。

- デザインの改修など、contentの追加・修正以外  
変更内容に関する Issue を立てて、ブランチを切ります。作業が完了したら Pull Request を作って main ブランチにマージします。
わからない場合は @0V などのわかりそうな人に聞いてください。
