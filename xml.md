# xml

##### 註解方式

```
<!--"XXXXX"-->
```

##### 關聯設置

以target 為父級，並以頂-頂，中心-中心\(百分比\)

```
<relation target="XXX" sidePair="top-top,center-center%"/>
```

> !需設置於該物件內

```
<component id="n63_finl" name="p2" src="finlrkhfg" fileName="views/card/card_point2.xml" xy="10,15" pivot="0.5,0.5" size="145,39" aspect="true" controller="language,0">
      <gearDisplay controller="msg" pages="2"/>
      <relation target="n62_hw63" sidePair="left-left%"/>
      <relation target="" sidePair="width-width,height-height"/>
</component>
```

##### 動效呈現

按組件名稱\(ex:n55\_hw63\)排序，並按關鍵幀依序設置，參考下例

```
<transition name="point1">
    <item time="0" type="Alpha" target="n55_hw63" value="0"/>
    <item time="0" type="Alpha" target="n92_u298" tween="true" startValue="0" endValue="1" duration="5"/>
    <item time="0" type="Scale" target="n55_hw63" value="1,1"/>
    <item time="0" type="XY" target="n92_u298" tween="true" startValue="-340,-" endValue="0,-" duration="5"/>
    <item time="4" type="Alpha" target="n55_hw63" tween="true" startValue="0" endValue="1" duration="4"/>
    <item time="4" type="Scale" target="n55_hw63" tween="true" startValue="0,0" endValue="1.25,1.25" duration="3"/>
    <item time="4" type="Sound" value="ui://94hasbw3u298rkhgr,100"/>
    <item time="7" type="Scale" target="n55_hw63" tween="true" startValue="1.25,1.25" endValue="1,1" duration="2"/>
</transition>
```

##### 文字呈現\(需注意順序\)

* font 指定字體
* align 對齊方式
* leading 行距
* autoSize 自動縮放
* singleLine 單行
* autoClearText 清除文本

```
<text id="n66_uf0j" name="TF_money_num" xy="223,51" pivot="0,0.5" size="155,30" font="Microsoft YaHei" fontSize="20" color="#cccccc" align="center" vAlign="middle" leading="0" autoSize="shrink" singleLine="true" autoClearText="true" text="999,999,999.99">
      <relation target="n89_nl4m" sidePair="middle-middle"/>
      <relation target="n60_6ylk" sidePair="left-right"/>
</text>
```



