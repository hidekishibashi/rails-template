# Ruby on Rails チュートリアル用リポジトリ

- Ruby on Railsチュートリアルやる
- 目的：Rails（Ruby含む）知識の穴埋め
- [第6版](https://railstutorial.jp/chapters/beginning?version=6.0)しか出てない（2022.10.25現在）からそれで進める
- Rails7はリリースされているのでそれ使う（ついでにRuby3.1.2）
- Version差異などは吸収しながらよしなに進める
- Herokuデプロイなどあるっぽいが、そこは目的から外れるのでSKIP予定

## Versions

| name  | version |
|:------|:-------:|
| Ruby  | 3.1.2   |
| Rails | 7.0.4   | 
| mysql | 8.0.21  |

## How to Start

#### Build Docker

```
docker compose build
```

#### Create Database

```
docker compose rub web rails db:create
```

#### Start Rails Application

```
docker compose up
```