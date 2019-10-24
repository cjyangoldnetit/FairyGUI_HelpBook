# export

> _資料夾創建方式依情況與前端溝通_

輸出分為兩種資料夾

* 圖、fgui\(..\專案\_laya\bin\package\fgui\)
* code\(應設置為..\專案\_laya\src\ui\)

\(先行預覽\)分別置於

* 圖、fgui置於&gt;&gt;..\專案\_laya\bin\OGTFC\fgui\package
* code置於&gt;&gt;..\專案\_laya\src\ui
* SKLoader等
  * 將SKLoader置於ui 資料夾內
  * 將main, binder等ts 置於src即可

> 前端相關設定，亦可參考[Layabook](https://goldbook.gitbook.io/layabook/)

## 設置發佈方式

於資源庫，選定組件並按右鍵指定輸出，亦可自訂Hotkey快速鍵使用

## 注意

{% hint style="info" %}
確保該輸出的圖片/字體設定「輸出」
{% endhint %}

請將所有前端所需調用的圖片、字體，記得都設為set exported，才不會只導出該\(輸出\)場景有用到的組件而已，前端將調用不到需變更的圖、字體。

![](.gitbook/assets/images_exported.png)

> ex:前端需調用之卡/牌型/圖文字體等

{% hint style="info" %}
上傳至git之前，請確認資料夾內有無錯誤檔案
{% endhint %}

ex: osx 在publish後，會將發佈檔案夾隱藏在專案根目錄之下 ，請將該隱藏檔案刪除乾淨再上傳。

terminal

```text
	defaults write com.apple.finder AppleShowAllFiles TRUE;\killall Finder
```

                                                                                                                                                           _Read_ [_more_](https://0800happy.com/8284/)\_\_

## TA應用

| 頁面 |  |
| :---: | :--- |
| Loading | 全系列遊戲共用，由前端操作，TA無需製作 |

