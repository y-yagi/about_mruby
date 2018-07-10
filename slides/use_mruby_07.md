### [haconiwa](https://github.com/haconiwa/haconiwa)

* Dockerが独自のDSL(Dockerfile)でコンテナを作成するのに対して、haconiwaではコンテナを作成するのにmruby(RubyのDSL)を使える
* それにより、プログラマブルに作成出来る
* mrubyでフック機能も定義出来る
  * コンテナ終了後にメールを投げたい、特定のシグナルをうけた際に処理を実行したい、等々
