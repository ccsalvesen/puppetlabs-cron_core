
# cron_core

#### 目次

1. [説明](#description)
2. [リファレンス](#reference)
3. [制約 - OS互換性など](#limitations)
4. [開発 - モジュール貢献についてのガイド](#development)

<a id="description"></a>
## 説明

`cron`リソースをインストールして管理します。

<a id="reference"></a>
## リファレンス

リファレンス文書については、REFERENCE.mdを参照してください。

このモジュールは、Puppet Stringsを用いて文書化されています。

Stringsの仕組みの簡単な概要については、Puppet Stringsに関する[こちらのブログ記事](https://puppet.com/blog/using-puppet-strings-generate-great-documentation-puppet-modules)または[README.md](https://github.com/puppetlabs/puppet-strings/blob/master/README.md)を参照してください。

文書をローカルで作成するには、以下のコマンドを実行します。

```
bundle install
bundle exec puppet strings generate ./lib/**/*.rb
```

このコマンドにより、閲覧可能な \_index.htmlファイルがdocディレクトリに作成されます。ここで利用可能なリファレンスはすべて、コードベースに埋め込まれたYARD形式のコメントから生成されます。このモジュールに関して何らかの開発をする場合は、影響を受ける文書も更新する必要があります。

<a id="limitations"></a>
## 制約

`cron`はWindowsまたはFedora 28には対応していません。

<a id="development"></a>
## 開発

Puppet ForgeのPuppet Labsモジュールは、オープンプロジェクトです。プロジェクトをさらに発展させるには、コミュニティへの貢献が不可欠です。Puppetが役立つ可能性のある膨大な数のプラットフォーム、無数のハードウェア、ソフトウェア、デプロイメント構成に我々がアクセスすることはできません。

弊社は、できるだけ変更に貢献しやすくして、弊社のモジュールがユーザの環境で機能する状態を維持したいと考えています。弊社では、状況を把握できるよう、貢献者に従っていただくべきいくつかのガイドラインを設けています。

詳細については、[モジュール貢献ガイド](https://docs.puppetlabs.com/forge/contributing.html)を参照してください。
