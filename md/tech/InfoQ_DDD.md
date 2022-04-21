# InfoQ DDD

## 通用語言

- 代碼能夠完成正確的功能，但不一定能清楚表達出其所做的事情。將模型直接寫成代碼，這樣做是非常困難的
- 比起一個巨大的 UML 來說說，針對各個組建畫一個小規模的 UML 更加實用

## Model-driven design

- 任何一個負責修改代碼的人都必須學會用代碼來表達模型，並且必須參與到一定級別的 domain 討論和 domain 專家保持溝通
- 行為應該很自然地隸屬於一個服務，而不是被包含在領域對象中
- 不應該為每一個需要的操作創建一個服務，但是當一個操作凸顯為 domain 的一個重要的概念的時候，就需要為它創建一個服務了
- 使用 Repository 的目的是封裝所有獲取對象應用所需要的邏輯。Repo 扮演了一個全局可訪問對象的儲存地點的角色
- Factory vs. Repository: Factory 關注的是對象的創建，Repository 關注的是已經存在的對象

## 保持模型的一致性

- Adapter 可以使你將一個類的接口轉換成為客戶端能夠理解的另一個接口