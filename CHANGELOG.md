# CHANGELOG

<details>
<summary>運用方法について</summary>

## リリース

リリースを実施すると判断したら、`main`セクションの`application`の内容を元に[Pride Versioning v0.2.0](https://pridever.org/)を元にタグを発行し、該当バージョンのセクションを`main`直下に差し込む

## 変更内容の定義

変更内容がどこに、どのような影響を与えたかを記載する

### 更新内容のセクション分けについて

以下で変更内容を大別する

- `application`
  - アプリケーションの振る舞いへの影響があるもの
- `development`
  - 開発者の作業内容・開発体験に影響があるもの

### 更新内容について

更新内容は以下の凡例に従って記載する

```md
- [PREFIX] 更新内容
  - @更新者ID
```

PREFIXについては、変更の影響を鑑みて、以下の定義に従って記載する

- CHANGE
  - 下位互換のない変更
- UPDATE
  - 下位互換がある変更
- ADD
  - 下位互換がある追加
- FIX
  - バグ修正

</details>


## main

### application

- [UPDATE] ラベル調整
    - @ivixvi

### development

- [UPDATE] `CHANGELOG`の運用説明を追加
    - @ivixvi
- [UPDATE] `CHANGELOG`の不備を修正
    - @ivixvi

## v0.1.0

### application

- [UPDATE] リリース
    - @ivixvi

### development

- [UPDATE] `LICENSE`を`MIT`で指定
    - @ivixvi
- [UPDATE] `GitHub Pages`を設定
    - @ivixvi