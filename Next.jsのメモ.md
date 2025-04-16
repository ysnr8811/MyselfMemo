- [画面遷移](#画面遷移)
- [フォルダ構成について](#フォルダ構成について)
- [作り方に関して](#作り方に関して)
  - [layout.js](#layoutjs)
  - [/app/components フォルダ](#appcomponents-フォルダ)
  - ["use client";　について](#use-clientについて)
  - [layout.tsxでのタブの表示編集](#layouttsxでのタブの表示編集)


# 画面遷移
[画面遷移の方法](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating)

# フォルダ構成について
[フォルダ構成](https://nextjs.org/docs/app/getting-started/layouts-and-pages)

# 作り方に関して

## layout.js
共通するUIを記述するためのファイル

## /app/components フォルダ
アプリケーション内で再利用可能なUI部品（Reactコンポーネント）をまとめて管理するためのフォルダ

とにかくコンポーネントはここに入れること

## "use client";　について
クライアントサイドで実行されるファイルであることを明示的に記述する

何も書かれていなければサーバーサイドで処理が実行される

## layout.tsxでのタブの表示編集

```tsx
export const metadata: Metadata = {
  title: "Book-Major",
  description: "Book-Major"
};
```


