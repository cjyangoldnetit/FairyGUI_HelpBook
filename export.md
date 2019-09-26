# Publish

* file path &gt;&gt; bin&gt;res

  * 含圖片等

* code sets:

  * file path&gt;&gt; game&gt;src&gt;ui

* ts等

  * 將SKLoader置於ui 資料夾內

  * 將main, binder等ts 置於src即可

![](/assets/codesettings.png)

> 欲將export 該component, 需set exported. 並於code settings指定好位址。即可在publish後在該資料夾查看到相關輸出檔案。



Tips: 若images受控制器控制的情況下會變換圖片\(如下圖按鈕\)，請記得將該按鈕使用到的所有圖片設為set exported，該圖才會被輸出，前端才得以調用。

![](/assets/Screen Shot 2019-09-26 at 09.33.06.png)![](/assets/Screen Shot 2019-09-26 at 09.37.56.png)

