---
title: 相關資訊
---

# 伺服器相關規則

最終以官網公告和管理員決定為準。

## 遊戲道德條款

* 第 04 條：提供領地系統、箱子私人鎖功能、物品遭竊若非系統錯誤問題管理員將不受理。
  * 如果在沒有領地的情況下，東西被偷搶破壞等，一律由玩家自行負責。
* 第 05 條：玩家互相尊重禮讓，請勿佔領、破壞他人建築、謾罵、攻擊、破壞、偷取等行為。
* 第 07 條：請遠離他人建物建造，避免與其他建物互相碰觸、重疊，以免造成他人困擾。
  * 各自領地建議相隔十格位子以上，使用領地包圍屬於惡意干擾將會解除領地。
  * 若領地所有人已警告三次仍無離開可強制驅離  (ps.如領地結構複雜、所持人須告知出口方位)。
  * 終界門如被佔領請另找終界門 (或者找 OP 協尋下一座終界門)。
* 第 08 條：請勿擅自封鎖公共出入口，嚴重影響他人玩家、放置私人鎖或設置領地進行阻擋行為。

# 伺服器相關設定

* 領地格子數量增加的方式有三種
  * 通過在線遊玩，隨時間增加（掛網時間不會累積格子數量）。
  * 參加偶爾會舉辦的伺服器活動，獎勵數量不限。
  * 使用 `/buyclaims` 購買領地。（10 顆鑽石買 200 格領地數量）
* 目前每一個分流，領地的格子數量是分開獨立的
  * 在 A 分流遊玩，只會增加 A 分流的領地格子數量
  * 在 B 分流話領地，只會消耗在 B 分流的領地格子數量。
  * 使用 `/buyclaims` 購買領地前請先確認自己在哪個分流在進行購買。
* 當玩家 60 天未登入伺服器、領地保護將會消失，其他玩家可回收領地內所有物。
  * 如若玩家事前通知管理人員，管理人員將會代管並保存。

# 領地指令列表

| 命令 Command  | 說明 Description |
| ------------------ | ------------------- |
|`/abandonallclaims`         | 刪除所有屬於自己的領地 |
|`/abandonclaim`            | 刪除自己的所站得那一塊領地 |
|`/accesstrust <玩家 ID>`    | 給與該玩家使用按鈕、拉桿和床 |
|`/buyclaims`                | 購買領地（10 顆鑽石買 200 格領地數量） |
|`/claimexplosion`           | 開啟/關閉領地內爆炸破壞地形（TNT、終界水晶） |
|`/claimlist`                | 查詢自己所有領地數量和位置 |
|`/containertrust <玩家 ID>` | 給與該玩家使用按鈕、拉桿、床、容器（箱子，熔爐等）和動物（裝牛奶等）。 |
|`/goc <玩家 ID>`            | 將該玩家驅除目前所站得領地 |
|`/subdivideclaims`          | 領地細分模式 |
|`/restrictsubclaim`          | 取消子領地繼承主領地權限 |
|`/trust <玩家 ID>`          | 給與該玩家除了管理領地以外的所有權限 |
|`/trustlist`                | 查詢領地權限列表 |
|`/untrust <玩家 ID>`        | 回收該玩家權限所有權限 |
|`/untrust all`         | 回收該領地所有權限 |

# 領地的預設行為

* 防止爆炸破壞地形，可以用指令關閉領地內防爆。
* 不信任（trust）任何玩家，需要領地擁有者給與權限，其他玩家才能夠進行建設或開啟箱子。
* 關閉玩家間對戰傷害（PVP），沒辦法傷害玩家。
  * 包含任意由玩家投擲的藥水（毒、傷害、虛弱...）。
* 終界珍珠可以丟到領地內，但沒有該領地權限的玩家不會傳送。
  * 歌來果尚未確定是否可以藉由隨機傳送進入領地。

# 紅石機關與水流

* 紅石機關和水/岩漿流動無法穿透領地邊界對領地造成影響
  * 活塞（包含粘性活塞和史萊姆方塊）無法從領地外推動或拉動領地內的方塊。
  * 水和岩漿無法流過領地邊界，如果發現水或岩漿不會流動，請檢查有沒有領地阻擋。
