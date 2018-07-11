### [h2o](https://github.com/h2o/h2o)

* "H2O is a new generation HTTP server."
* mrubyが組み込まれており、リクエストハンドラとしてmrubyのコードが実行出来るようになっている
  * mrubyのソースがまるっとh2oのソースに含まれており、h2oビルド時にmrubyもbuildされる
  * [h2o/deps/mruby](https://github.com/h2o/h2o/tree/master/deps/mruby)
