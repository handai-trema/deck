## 課題

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
