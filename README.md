## Svelte SCSS 設定範例

1. 執行 `npm install` 安裝套件
2. 到 `rollup.config.js` 參考設定檔
   ```
   svelte({
   		preprocess: preprocess({
   			scss: true,
   		}),
   		compilerOptions: {
   			// enable run-time checks when not in production
   			dev: !production,
   		}
   	}),
   ```
3. 參考 [App.svelte](./src/App.svelte) 檔案查看 scss 使用範例
