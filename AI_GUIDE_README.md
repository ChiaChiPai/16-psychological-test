# 16-psychological-test

## 安裝完 npm install -g create-react-app 後，我要怎麼在資料夾內創建一個 react 專案
create-react-app my-app

## 如何為創建好的 react 新專案加入 tailwind.css 套件
npm install -D tailwindcss
npx tailwindcss init

## 安裝好後 tailwindcss 相關的套件，要怎麼設定，讓react專案可以使用
content: [
  "./src/**/*.{js,jsx,ts,tsx}",
],
theme: {
  extend: {},
},
plugins: [],

## eslint
npm install eslint --save-dev
