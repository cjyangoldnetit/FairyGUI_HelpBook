# errors

## ※切記在GUI排版必須確認場景的控制狀態都回到「初始值」再存檔，避免發生流程或控制上的錯誤※

**無預警變動XML**

![&#x7D44;&#x4EF6;&#x9078;&#x64C7;&#x7684;&#x60C5;&#x6CC1;&#x4E0B;\(1\)&#xFF0C;&#x5207;&#x63DB;&#x6309;&#x9215;&#x529F;&#x80FD;\(2\)&#xFF0C;&#x5373;&#x6642;&#x9801;&#x9762;&#x66F4;&#x65B0;\(3\)&#xFF0C;&#x6B64;&#x6642;component\(4\)&#x5DF2;&#x7522;&#x751F;&#x8B8A;&#x52D5;&#xFF1B;&#x4F46;&#x5728;Tab\(5\)&#x6C92;&#x6709;&#x986F;&#x793A;&#x8B8A;&#x66F4;&#x63D0;&#x793A;\(\*\)](.gitbook/assets/bug01.jpg)

**解決方式**

由於fairy會預設將控制器裝載到此場景，每次更動一律需要手動選定某一項目，否則預設會以目前狀態裝載，最終導致悄悄存檔而無所知。

## 待解

閃爍問題: \(未解決\) 可能由laya 或 fairy造成

文字輸出至平台漏字問題\(未解決\): ios 變新明體等



