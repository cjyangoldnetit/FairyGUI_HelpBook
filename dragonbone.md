# DragonBone

## 說明

由於fairy無法直接載入DragonBone\(DB\), 故採laya寫loader 指定該DB。

## 步驟

1. 新增空物件
2. 自定義數據 
3. 調整大小\(勿用縮放Scale\), 縮放值由前端調整
4. 位置在輸出後會不一致，需要來回確認修正

```text
Dragonbone=dragonbone/three_cards_girl.sk,L,B
```

![](.gitbook/assets/dbref.png)

![](.gitbook/assets/dbcode.png)

