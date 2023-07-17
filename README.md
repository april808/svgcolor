# svg icon 路徑檔案 換色
img 連結 svg檔後，fetch路徑和class名稱，使svg檔style.fill 可以抓 currentColor。

用法:
`
<script>
  svg_icon('.custom-svg', 'currentColor');
</script>`
.custom-svg 是class名稱，記得要兩者對應
範例
`<img class="custom-svg" src="..圖檔路徑/settings.svg" alt="settings-icon">`
