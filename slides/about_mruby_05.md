### mruby

```
rbenv install mruby-1.4.1
```

```
$ mirb
mirb - Embeddable Interactive Ruby Shell

> MRUBY_VERSION
 => "1.4.1"

> nil&.to_s
 => nil

> {"a" => 1}.transform_values {|v| v * 2 }
 => {"a"=>2}
```
