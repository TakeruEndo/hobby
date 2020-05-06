## jekyll + Github Pages

```
# 2.5.0だとうまくローカルサーバーを立ち上げられなかった
$ rbenv install 2.4.0
# ver確認
$ rbenv versions
$ rvenv global 2.4.0
$ mkdir ~/.rbenv/versions/paper-survey
$ ruby-build 2.4.0 ~/.rbenv/versions/paper-survey

$ bundle install
$ gem install gekyll
$ jekyll serve

```

## 変更の適用
```
$ gulp sass
$ gulp js
```

## 参考にしたjekyllテンプレート
http://jekyllthemes.org/themes/sleek/  

`package.json`
```
# gulp-responsive
```
画像のサイズ変換に使うが、別途必要なツールがあるので省略した  
https://dev.classmethod.jp/articles/gulp-solo-adv-cal-15/


