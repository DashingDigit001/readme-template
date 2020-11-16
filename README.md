# Vue Hello-World 專案

## 簡介

### 語言 : javascript

### 主旨 :

最小可行的 Vue 專案建立



## 快速開始

### 環境建立

- vue-devtools 瀏覽器開發工具
- Vue.js
  或是

```html
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.11"></script>
```

- Node.js
- Yarn (optional)

```bash
yarn global add @vue/cli
yarn global add @vue/cli-service-global
```



### 專案建立

進入terminal

```bash
vue create test-app //default即可
```



## 觀念(optional)
- 製作的專案若相當輕量化, 無需使用nodejs進行編輯, 可直接寫在網頁js中


## 使用範例

進入terminal

```bash
cd test-app
yarn serve
```



## 佈署

1. 進入terminal

```bash
yarn build //注意 cmd 資料夾的大小寫對於 webpack 是嚴格要求的
```

2. 將 build 資料夾放置 IIS 中的位置
