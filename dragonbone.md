## 觀念

由於fairy無法直接載入DragonBone\(DB\), 故採laya寫loader 指定該DB。

## 

## Steps

1. 新增空物件
2. 自定義數據 \(ex.Dragonbone=dragonbone/three\_cards\_girl.sk,L,B\)
3. 可拉一示意圖\(記得設invisible\)

|<div style="width:500px">property</div> | <div style="width:50px">property</div> |
| :---  | :--- |
| ![my caption](/assets/dbone01_1.jpg)| <div style="width:50px">若拉圖片做reference, 請記得勾選invisible；<tr>以及，設定的size大小要記得。</tr></div> |
| ![](/assets/dbone01_2.jpg) | 在換算過size大小後，以一空container \(scale為1\)去盛取以供後續裝載Dragon Bone之用。並將代碼置於自定義數據。 |



