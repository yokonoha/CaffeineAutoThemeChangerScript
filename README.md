# CaffeineAutoThemeChangerScript
自動でCaffeineCSS/FSLinearを昼夜で切り替えるスクリプトです。自動ライト/ダークモード化をこれ一つで実現できます。  

このスクリプトとCaffeineCSS,FSLinearをWebページと同じディレクトリへコピー後、以下の条件を確認してください。  
1.bodyタグ下に  
```sample.html
<script src="./themeac.js"></script>
```  
が入力されていること  
**********************
2.外部CSSのリンクタグが  
```sample.html
<link href="fslinear.css" rel="stylesheet" id="caffeinetheme"/>
```  
または  
``` sample.html
<link href="caffeine.css" rel="stylesheet" id="caffeinetheme"/>
```
となっていること  
**********************
3.footerに以下のテキストが存在すること  
```sample.html
<p><small>このページでは<a href="https://github.com/yokonoha/FSLinear" id="interchangeablecssprofiles">FSLinear</a>を使用しています。</small></p>
```
または  
```sample.html
<p><small>このページでは<a href="https://github.com/yokonoha/Caffeine_CSS" id="interchangeablecssprofiles">CaffeineCSS</a>を使用しています。</small></p>
```  


入力できていれば、エラーなく動作します!  
ご不明な点等ございましたらお気軽にお問い合わせください!  
ご利用いただきありがとうございます!  
製作者 横茶横葉  
## ライセンスに関して  
このスクリプトはCaffeineCSSとFSLinearのバンドルスクリプトです。  
従ってCaffeineCSS,FSLinear同様MITライセンスまたは横茶横葉Aライセンスの内、お好きな方1つのライセンスが適用されます。  
しかし、CaffeineCSSやFSLinearと一緒に使用する場合は明記は一切不要です。そのまま一緒にご利用ください!  
