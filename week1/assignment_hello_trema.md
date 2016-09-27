## 課題 (Hello Trema)

HelloTrema が起動したら次のメッセージを表示するようにしてみよう:

```
HelloTrema started.
```

ただし、次の回答ではダメ (なぜダメか？も考えよう)

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

1. 提出用リポジトリの作成。[こちらのリンク](https://classroom.github.com/assignment-invitations/1432105c8d4577dee37a0e001de48830)
   をクリックすると、自動的に handai-trema/hello-world-[ユーザ名] というリポジトリが作成できます。

2. ソースコードを改造しコミットする

3. レポートを書き提出
