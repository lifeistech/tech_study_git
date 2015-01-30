# テクスタ vol.1 Git / GitHub勉強会
Life is Tech ! テクスタ用レポジトリ

## Slides
[教材スライド](https://docs.google.com/a/lifeistech.co.jp/presentation/d/1E_y9UWRnvTSkIcQq1On6K7ZabjcLDawaqcoIPRMNumI/htmlpresent)


## Workshop

このレポジトリを右上のボタンから【Fork】 = 自分のアカウントに複製される

ターミナルを起動し、デスクトップへ移動（Change Directory）
```
$cd ~/Desktop
```

Forkした自分のレポジトリをclone
```
$git clone https://github.com/自分のアカウント/tech_study_git.git
```

ターミナルでcloneしたレポジトリに移動
```
$cd ~/Desktop/tech_study_git
```

テキストエディタなどで変更を加える

変更点（スナップショット）を見る
```
$git diff
```

変更点（スナップショット）をステージング（add）
```
$git add .
```

現在の状態を確認する
```
$git status
```

バージョン管理に記録するためにコミット ※メッセージは変更内容を簡潔に記載
```
$git commit -m "message"
```

変更が登録されたかどうか確認しよう！
```
$git log
```

自分のGitHubに変更を送信する
```
$git push origin master
```

Pull Requestを作成する






