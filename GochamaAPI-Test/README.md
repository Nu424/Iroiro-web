# GochamaAPI-Test
ごちゃまぜAPIのテストサイトで ~~す。~~ した。
以下は過去の情報です。
```
# GochamaAPI-Test
ごちゃまぜAPIのテストサイトです。
https://nu424.github.io/GochamaAPI-Test/
## ごちゃまぜAPIとは
文章をごちゃまぜにするWebAPIです。  
MeCabで単語に区切っていろいろやります。  
もとの文章と同じ順番に品詞が並ぶように、ごちゃまぜにします。  

例)「文章をごちゃまぜにするAPIです」→「文章 を ごちゃまぜ に する API です」→「[名詞][助詞][名詞][助詞][動詞][名詞][助動詞]」→「API に 文章 を する ごちゃまぜ です」
## ごちゃまぜAPIの使い方
`https://gochama-api.herokuapp.com/?text=[ごちゃまぜにするテキスト]&mode=[ごちゃまぜにする方法]`
### ごちゃまぜにする方法の違い
- `normal` 単純に単語の品詞だけを見ます。
- `subclass` 単語の品詞の細かい分類も意識してごちゃまぜにします。
- `bunsetsu` 文節ごとに区切って、後はランダムにごちゃまぜします。
```
