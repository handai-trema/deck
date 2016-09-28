## 課題 (Hello Trema)

HelloTrema が起動したら次のメッセージを表示するようにしてみよう:

```
HelloTrema started.
```

ただし、次の回答ではダメ (なぜダメか？も考察しよう)

```ruby
class HelloTrema < Trema::Controller
  def start(_args)
    logger.info 'HelloTrema started.'
  end
  ...
```

* ヒント 1: [Object#class メソッド](http://ruby-doc.org/core-2.0.0/Object.html#method-i-class)
* ヒント 2: [Module#name メソッド](http://ruby-doc.org/core-2.0.0/Module.html#method-i-name)

### 提出方法

1. リポジトリ handai-trema/hello-trema-[ユーザ名] のソースコードを改造しコミットする

2. レポートを書き同じリポジトリにコミット

2. 自己紹介リポジトリ (handai-trema/self-intro-[ユーザ名]) にレポートへのリンクを追加
