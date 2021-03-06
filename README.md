### 使用方式

    此為NextJS+TailwindCSS專案範本，內含常用模組，持續增加中
    使用方法

    ```
    npm ci


    npm run  dev
    ```

### Tailwindcss

[官方文件](https://tailwindcss.tw/docs)

-   TailwindCSS 引入於 `global.css` ，自訂新增 className 和新增元件務必依照`@layer`規範寫於`global.css`
    <br>
    **勿任意增加 inlinestyle**

-   `postcss.config.js` 內 `'tailwindcss/nesting': {}` 預設註解<br>
    開啟可使`global.css`支持 nesting，無必要勿開啟，會影響 dev 開發時 compiling 效能

-   `tailwind.config.js` 撰寫 TailwindCSS 自訂設定 <br>
    [設定](https://tailwindcss.tw/docs/configuration)

-   另加入 `tailwindcss-named-groups`插件，做多組 group 命名<br>
    [插件](https://www.npmjs.com/package/tailwindcss-named-groups)
-   `tailwindcss/aspect-ratio` 插件為提供照片顯示比例功能之插件 <br>
    [插件](https://www.npmjs.com/package/@tailwindcss/aspect-ratio)

## Components

-   `CarouselBanner` <br>
    輪播功能，可設定電腦版寬高比和手機版寬高比 <br>
    可選是否傳入連結 or 僅圖片輪播

-   `TimeBox` <br>
    顯示時間用

-   `ImageBox` <br>
    傳入相片連結 可動態更改長寬比
