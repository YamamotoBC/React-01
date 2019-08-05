このプロジェクトは [Create React App](https://github.com/facebook/create-react-app) で生成されました

## 利用可能なスクリプト

このプロジェクトディレクトリでは以下のコマンドが実行できます

### `npm start`

開発モードでアプリを実行します<br>
ブラウザで表示するには [http://localhost:3000](http://localhost:3000) を開いてください

コードを編集すると、ページがリロードします（Watchしている）
コンソールには yarn のエラーも表示されます

### `npm test`

インタラクティブウォッチモード（interactive watch mode）でテストランナーを起動します。<br>
詳しくは [running tests](https://facebook.github.io/create-react-app/docs/running-tests) をごらんください

### `npm run build`

`build` フォルダに本番（production）アプリをビルドします。 <br>
Reactを本番モードで正しくバンドルし、パフォーマンスを発揮するよう最適化してビルドします。

ビルド結果はミニマイズされ、ファイル名はハッシュを含みます。<br>
アプリをデプロイする準備が整いました！

詳しくは [deployment](https://facebook.github.io/create-react-app/docs/deployment) をご覧ください

### `npm run eject`

**Note: このプロジェクトでは既に実行済みです**

create-react-app で生成したコードは、定番構成をパックしたもので、ブラックボックス化されていて壊しにくくなっています。

`eject` を実行するとブラックボックスは分解され、ライブラリの依存関係なども展開されます。
実行したコマンドは以下のようなものです

```
yarn run eject
yarn run start
```

この時点でライブラリが見つからない、というエラーが発生した場合は `yarn add ...` で追加します。

展開されたライブラリが古いケースもあります。その場合はライブラリの読み込みを削除し、やりなおしてみると良いでしょう。


```
rm -r node_modules
rm -r yarn.lock
yarn
```

以下、eject についてのドキュメント

**Note: このコマンドは実行したら戻せません。 一度 `eject` を実行すると、create-react-app で生成した直後の状態には戻せません**

ビルドツールと設定をカスタマイズしたいとき, あなたは `eject` を実行することができます。このコマンドはあなたのプロジェクトからシングルビルドの依存関係を取り除きます。

かわりに、全ての設定ファイルと関連する依存関（Webpack, Babel, ESLintなど）をプロジェクトに取り組み、カスタムすることが可能になります。
この時点では eject 以外のコマンドは利用可能ですし、微調整も可能です。

かならす `eject` を実行する必要はありません。オススメパックである(ejectする前の機能パック)は、中小規模に向いていますから、カスタマイズが不要なら実行する必要がありません。

## さらに学ぶ

[Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started) でさらに学習を進めることができます。

Reactを学ぶには [React documentation](https://reactjs.org/)をご覧ください
