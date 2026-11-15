# Shelter-Planner
防災識安所：避難所規劃

An interactive digital project that digitizes the disaster shelter planning course for Disaster Prevention Specialists, designed to serve as supplementary digital learning material for their training courses.

防災士避難所規劃課程數位化的互動作品，目標成為防災士培訓課程中輔助上課的數位教材。

## 製作團隊
大同大學第16屆第11組專題
- 組員：陳彥廷、蔣誠以、蔣誠可、李哲安
- 指導老師：(待填)
- Notion網頁：(待填或暫不公開)

## 技術
- Unity 6（6000.4.10f1）・WebGL ・ Blender/Three.js（場景模型建模）
- Claude程式編寫協助

## 素材與授權
- 人物模型：[Low Poly People](https://assetstore.unity.com/packages/slug/274814) by David Jalbert（Unity Asset Store，Standard Unity Asset Store EULA）
- 字型：[jf open 粉圓](https://github.com/justfont/open-huninn-font)、[注音粉圓（bpmfvs）](https://github.com/ButTaiwan/bpmfvs)，SIL Open Font License 1.1
- 背景音樂：原創生成音樂
- 開場介紹與防災小知識：照片候選清單（下載原圖、確認授權用）
大槌町空拍：https://commons.wikimedia.org/wiki/File:US_Navy_110315-N-5503T-307_An_aerial_view_of_damage_to_Otsuchi,_Japan,_after_a_9.0_magnitude_earthquake_and_subsequent_tsunami_devastated_the_area_in_northern_Japan.jpg
氣仙沼空拍：https://commons.wikimedia.org/wiki/File:An_aerial_view_of_tsunami_damage_in_an_area_north_of_Sendai,_Japan,_taken_from_a_U.S._Navy_helicopter.jpg
鎌倉津波避難標示：https://commons.wikimedia.org/wiki/File:Tsunami_evacuation_route_sign_on_the_road,_Kamakura,_2016.jpg
橫須賀避難路牌：https://commons.wikimedia.org/wiki/File:CFAY_Tsunami_Evacuation_Signs_(9787594).jpg
人龍傳遞物資：https://commons.wikimedia.org/wiki/File:US_Navy_110320-N-OB360-148_Marines_and_Japanese_citizens_form_a_chain_near_an_evacuation_center_in_Northern_Japan_to_move_relief_supplies_from_a_CH.jpg
直升機運送物資：https://commons.wikimedia.org/wiki/File:Helicopter_provides_supplies_for_the_USS_Blue_Ridge%27s_support_of_relief_efforts_in_Japan_following_earthquake.jpg
神戶倒塌建築（1995）：https://commons.wikimedia.org/wiki/File:Hanshin-Awaji_earthquake_1995_336.jpg
倒塌的高速公路（內閣府）：https://commons.wikimedia.org/wiki/File:阪神大震災で倒壊した高速道路.jpg
八島中學體育館：https://commons.wikimedia.org/wiki/File:Yashima_Junior_High_School_small_gym.jpg
車城國小避難處所標示：https://commons.wikimedia.org/wiki/File:Checheng_Taiwan_Checheng-Elementary-School-03.jpg
花蓮中華國小帳篷：https://commons.wikimedia.org/wiki/File:2024年4月4日行政院長陳建仁關心中華國小民眾收容安置情形_4.jpg
印旛明誠高中體育館：https://commons.wikimedia.org/wiki/File:Gymnasium_of_Inba_Meisei_High_School.jpg
平溪市民活動中心標示：https://commons.wikimedia.org/wiki/File:Evacuation_Shelter_sign_on_Pingxi_Civic_Center_20190908.jpg
授權條款連結
CC BY 3.0：https://creativecommons.org/licenses/by/3.0/deed.zh-hant
CC BY-SA 3.0：https://creativecommons.org/licenses/by-sa/3.0/deed.zh-hant
CC BY-SA 4.0：https://creativecommons.org/licenses/by-sa/4.0/deed.zh-hant
台灣政府資料開放授權條款第 1 版：https://data.gov.tw/license
日本政府標準利用規約 2.0（內閣府）：https://www.cao.go.jp/notice/rule.html

## 從1.1.0到2.0的更新與修正項目
- 新手教學變成初次不可跳過
- 修正新手教學裡的帳篷提示問題
- 調整新手教學文字量
- 調整行為機制介面與文字量
- 補上開場介紹與防災小知識圖片

## 從2.0到2.1的更新與修正項目
- 開場介紹前新增使用者身分詢問：國小學童（可開注音）、國中高中大學生、中老年人（可放大字體）、防災士（上課用可跳過並關閉新手教學）
- 選擇場景在完成第一輪體驗前鎖定；重設進度與成就時會一併重設身分詢問
- 進入場景統一為北方朝上的視角，新增指南針與地面東南西北標示
- 新增居民入口標示（位置固定、不可調整），並在新手教學中說明
- 規劃內容改為三頁：時間軸、收容對象（男性與女性單身者圖文說明）、居民特質大圖
- 每位居民的特質數量改為 0～2 個
- 女性居民加上長髮與裙子；介面改用廁所男女符號區分，不再用藍粉顏色
- 字體與介面放大（提示訊息、物件詳細資訊、入住名單等）
- 新手教學：開始擺放物件時對話框會淡出，擺好或完成該步驟後重新出現；新增「點選報到桌」與「查看入住名單」引導；刪除居民特質說明
- 報到桌被擋住時，居民會在避難所外遊蕩，不再站著乾等

- ## 2.1 後續更新
- 新增前置教學路線圖（第 1 章）：1-1 基本操作、1-2 報到桌、1-3 安排工作人員、1-4 帳篷與屏風、1-5 物資箱與垃圾桶、1-6 劃區，最後到 1-7 禮堂
- 路線圖改名「選擇章節」，字體放大、更換關卡圖示，詳細資訊改為該關一開始的預覽畫面（不提示解法）
- 場景改為 40×20 公尺的學校禮堂（講台、男女廁所＋淋浴、親子無障礙廁所），新增小倉庫練習場景、屋頂與室內燈
- 新增劃區：單身男區、單身女區、溫馨關懷區、物資區、報到區、多功能區、工作人員休息＆會議室；居民先走到自己的分區再找帳篷
- 帳篷不再分男女：放在單身男區就給男性住、單身女區就給女性住
- 屏風改為擋住男女帳篷之間的視線（不再以距離判斷）
- 新增工作人員（禮堂 4 人分早晚班）：報到桌要有工作人員顧著才能報到；按住場上的工作人員拖到報到桌安排崗位；其他人待命補位、帶迷路的居民；供餐時協助發放物資；會輪流吃飯、休息並開交接會議
- 避難所管理面板新增【入住名單】【工作人員】按鈕
- 新手教學：對話框不擋介面、可在【畫面設定】隱藏；禮堂改為「操作總複習」，前置教學全部完成後可跳過；前置教學未完成時進禮堂會先詢問，教學不可跳過（防災士上課模式除外）
- 行為紀錄：物件附近擠成一團時，會記錄「某物件在某區造成阻塞」
- 過關畫面改為操作截圖＋簡短說明；規劃內容新增工作人員頁，學童模式文字更簡單、開注音時不超出框
- 新增「行動不便」居民（使用無障礙廁所）、行為紀錄重播
- 物件預設朝向居民入口；畫面設定可隱藏介面與各種場地標示
- 修正：音效音量不再影響背景音樂

  
版本 2.1

更新日期：2026/11/15
