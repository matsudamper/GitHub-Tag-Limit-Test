# 概要
> 当社ではタグのプッシュをトリガーに検証環境が構築されたり、デプロイメントのトリガーに使ったりしており、かなりタグの数が多いです。 現在は、いらないタグを自動で消すようにしているのですが、以前はタグが溜まり続けており4000を超えた段階でGitHub APIがエラーを出してリリースできないという事象が発生しました。

https://techblog.openwork.co.jp/entry/github-tips

の検証用。

# 結果
![image](https://github.com/user-attachments/assets/8bb1a5cf-8b30-4187-8704-a5ed2b28b9ac)

タグがいくつあっても特に問題なし。
