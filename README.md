# @osaxyz/mediaquery

## インストール

`npm install @osaxyz/mediaquery`

## どう動くか

```sass
.hoge
    @include mq(ショートハンド)
        flex-direction: column
```

## ショートハンド一覧

| ショートハンド | 命名由来 | 幅 |
| --- | --- | --- |
| SE | iPhone SE 端末サイズ | 375px以下 |
| XR | iPhone XR 端末サイズ | 414px以下 |
| iPad | iPad 端末サイズ | 768px以下 |
| iPadPro | iPadPro 端末サイズ | 1024px以下 |
| Air | 13インチMacbook 画面サイズ | 1440px以下 |
| Pro | 15インチMacbook 画面サイズ | 1792px以下 |
| HD | フルHD 画面サイズ | 1920px以下 |
| upto4k | フルHD以上 | 1921px以上 |

## px指定

```sass
.hoge
    @include mqpx('300', 'px')
        flex-direction: column
```

ビューポートサイズ300px以下のメディアクエリとなる。