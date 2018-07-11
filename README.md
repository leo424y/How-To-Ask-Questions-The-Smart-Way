# 提問的智慧

#### 艾瑞克.史蒂文.雷蒙德（Eric Steven Raymond）

Thyrsus Enterprises

<esr@thyrsus.com>
#### 瑞克.莫恩（Rick Moen）


<respond-auto@linuxmafia.com>
版權©2001, 2006 Eric S. Raymond, Rick Moen

### 修訂歷史

```
修訂版 3.9	2013年4月23日	esr
修正連結
修訂版 3.8	2012年6月19日	esr
修正連結
修訂版 3.7	2010年12月6日	esr
對於英語為第二語言人士的有益建議
修訂版 3.7	2010年11月2日	esr
幾種翻譯不見了
修訂版 3.6	2008年3月19日	esr
小更新及新連結
修訂版 3.5	2008年1月2日	esr
勘誤及一些翻譯連結
修訂版 3.4	2007年3月24日	esr
新章節：“關於程式碼的問題”
修訂版 3.3	2006年9月29日	esr
增加凱.尼格曼（Kai Niggemann）的一個好建議
修訂版 3.2	2006年1月10日	esr
加入瑞克.莫恩（Rick Moen）編寫的內容
修訂版 3.1	2004年10月28日	esr
文件“谷歌是你的朋友！”
修訂版 3.0	2004年2月2日	esr
主要新增在網頁論壇應有的禮節
```

### [原文：How To Ask Questions The Smart Way](http://www.catb.org/~esr/faqs/smart-questions.html)
翻譯：王剛 <yafrank at 126 dot com >
時間：2013年10月26日
內容

### 目錄

* [棄權申明](#棄權申明)
* [引言](#引言)
* [提問前](#提問前)
* [提問時](#提問時)
  * [仔細挑選論壇](#仔細挑選論壇)
  * [面向新手的論壇和網際網路中繼聊天（IRC）通常響應最快](#面向新手的論壇和網際網路中繼聊天irc通常響應最快)
  * [第二步，使用專案的郵件列表](#第二步使用專案的郵件列表)
  * [使用有意義且明確的主題](#使用有意義且明確的主題)
  * [使問題容易回覆](#使問題容易回覆)
  * [用清晰、語法、拼寫正確的語句書寫](#用清晰語法拼寫正確的語句書寫)
  * [使用易於讀取且標準的檔案格式傳送問題](#使用易於讀取且標準的檔案格式傳送問題)
  * [描述問題應準確且有內容](#描述問題應準確且有內容)
  * [量不在多，精煉則靈](#量不在多精煉則靈)
  * [別急於宣稱找到臭蟲](#別急於宣稱找到臭蟲)
  * [低聲下氣代替不了做自己的家庭作業](#低聲下氣代替不了做自己的家庭作業)
  * [描述問題症狀而不是猜測](#描述問題症狀而不是猜測)
  * [按時間先後羅列問題症狀](#按時間先後羅列問題症狀)
  * [描述目標而不是過程](#描述目標而不是過程)
  * [別要求私下回覆電郵](#別要求私下回覆電郵)
  * [提問應明確](#提問應明確)
  * [關於程式碼的問題](#關於程式碼的問題)
  * [別張貼家庭作業式問題](#別張貼家庭作業式問題)
  * [刪除無意義的要求](#刪除無意義的要求)
  * [不要把問題標記為“緊急”，即使對你而言的確如此](#不要把問題標記為緊急即使對你而言的確如此)
  * [禮貌總是有益的](#禮貌總是有益的)
  * [問題解決後追加一條簡要說明](#禮貌總是有益的)
* [如何解讀回答](#如何解讀回答)
  * [“讀讀該死的手冊”（RTFM）和“搜搜該死的網路”（STFW）：如何明白你已完全搞砸](#讀讀該死的手冊rtfm和搜搜該死的網路stfw如何明白你已完全搞砸)
  * [如果還不明白……](#如果還不明白)
  * [對待無禮](#對待無禮)
* [別象失敗者那樣反應](#別象失敗者那樣反應)
* [提問禁忌](#別象失敗者那樣反應)
* [好問題與壞問題](#好問題與壞問題)
* [如果得不到回答](#如果得不到回答)
* [如何更好地回答](#如何更好地回答)
* [相關資源](#相關資源)
* [鳴謝](#鳴謝)

> 譯文： 印尼語 白俄羅斯語 巴西葡萄牙語 簡體中文 荷蘭語 法語 喬治亞語 德語 希臘語 希伯來語 日語 波蘭語 葡萄牙語 羅馬尼亞語 俄語 西班牙語 泰語 如果你想複製、映象、翻譯或引用本文，請參閱我的 複製協議。

### 棄權申明

許多專案的網站在如何取得幫助的部分連結了本文，這沒有關係，也正是我們想要的。但如果你是該專案生成此連結的網管，請在連結附近顯著位置註明：我們不提供該專案的服務支援！

我們已經領教了沒有此說明帶來的痛苦，我們將不停地被一些白痴糾纏，他們認為既然我們釋出了本文，那麼我們就有責任解決世上所有的技術問題。

如果你是因為需要幫助正在閱讀本文，然後就帶著可以直接從作者那取得幫助的印象離開，那麼 你 就不幸成了我們所說的白痴之一。 別向 我們 提問，我們不會理睬的。 我們只是在這教你如何從那些真正懂得你軟硬體問題的人那裡取得幫助，但 99.9％ 的時間我們不會是那些人。除非你非常地 確定 本文的作者是你遇到問題方面的專家，請不要打攪，這樣大家都更開心一點。

### 引言

在 黑客 的世界裡，你所提技術問題的解答很大程度上取決於你提問的方式與解決此問題的難度，本文將教你如何提問才更有可能得到滿意的答覆。

開源程式的應用已經很廣，你通常可以從其他更有經驗的使用者而不是黑客那裡得到解答。這是好事，他們一般對新手常有的毛病更容忍一點。然爾，使用我們推薦的方法，象對待黑客那樣對待這些有經驗的使用者，通常能最有效地得到問題的解答。

第一件需要明白的事是黑客喜歡難題和激發思考的好問題。假如不是這樣，我們也不會寫本文了。如果你能提出一個有趣的問題讓我們咀嚼玩味，我們會感激你。好問題是種激勵與禮物，幫助我們發展認知，揭示沒有注意或想到的問題。在黑客中，“好問題！” 是非常熱烈而真摯的讚許。

此外，黑客還有遇到簡單問題就表現出敵視或傲慢的名聲。有時，我們看起來還對新手和愚蠢的傢伙有條件反射式的無禮，但事情並不真是這樣。

我們只是毫無歉意地敵視那些提問前不願思考、不做自己家庭作業的人。這種人就象時間無底洞──他們只知道索取，不願意付出，他們浪費了時間，這些時間本可用於其它更有趣的問題或更值得回答的人。我們將這種人叫做 “失敗者（loser）” （由於歷史原因，我們有時將“loser”拼寫為“lusers” 。）

我們意識到許多人只是想使用我們寫的軟體，他們對學習技術細節沒有興趣。對大多數人而言，計算機只是種工具，是種達到目的的手段而已。他們有自己的生活並且有更要緊的事要做，我們承認這點，也從不指望每個人都對這些讓我們著迷的技術問題感興趣。不過，我們回答問題的風格是為了適應那些真正對此有興趣並願意主動參與解決問題的人，這一點不會變，也不該變。如果連這都變了，我們就會在自己能做得最好的事情上不再那麼犀利。

我們（大多數）是自願者， 從自己繁忙的生活中抽時間來回答問題，有時會力不從心。因此，我們會毫不留情地濾除問題，特別是那些看起來象是失敗者提的，以便更有效地把回答問題的時間留給那些勝利者。

如果你認為這種態度令人反感、以施惠者自居或傲慢自大，請檢查你的假設，我們並未要求你屈服──事實上，假如你做了該做的努力，我們中的大多數將非常樂意平等地與你交流，並歡迎你接納我們的文化。試圖去幫助那些不願自救的人對我們簡直沒有效率。不懂沒有關係，但愚蠢地做事不行。

所以，你不必在技術上很在行才能吸引我們的注意，但你 必須 表現出能引導你在行的姿態──機 敏、有想法、善於觀察、樂於主動參與問題的解決。如果你做不到這些使你與眾不同的事情，我們建議你付錢跟別人籤商業服務合同，而不是要求黑客無償幫助。

如果你決定向我們求助，你不會想成為一名失敗者，你也不想被看成一個失敗者。得到快速有效回答的最好方法是使提問者看起來象個聰明、自信和有想法的人，並且暗示只是碰巧在某一特別問題上需要幫助。

（歡迎對本文指正，可以將建議發至 esr@thyrsus.com 或 respond-auto@linuxmafia.com。 請注意，本文不想成為一般性的 網路禮儀 指南，我一般會拒絕那些與引出技術論壇中有用的回答不特別相關的建議。）

### 提問前

在通過電郵、新聞組或論壇提技術問題以前，做以下事情：

* 嘗試在你準備提問論壇的歷史文件中搜尋答案
* 嘗試搜尋網際網路以找到答案
* 嘗試閱讀手冊以找到答案
* 嘗試閱讀“常見問題文件”（FAQ）以找到答案
* 嘗試自己檢查或試驗以找到答案
* 嘗試請教懂行的朋友以找到答案
* 如果你是程式設計師，嘗試閱讀原始碼以找到答案

提問時，請先表明你已做了上述事情，這將有助於建立你不是寄生蟲與浪費別人時間的印象。最好再表述你從中 學到的東西 ，我們喜歡回答那些表現出能從答案中學習的人。

運用某些策略，比如用谷歌（Google）搜尋你遇到的各種錯誤提示（既搜尋 谷歌論壇，也搜尋網頁）， 這樣很可能直接就找到了解決問題的文件或郵件列表線索。 即使沒有結果，在郵件列表或新聞組尋求幫助時提一句“我在谷歌中搜過下列句子但沒有找到什麼有用的東西” 也是件好事，至少它表明了搜尋引擎不能提供哪些幫助。將搜尋關鍵詞與你的問題及可能的解決方案聯絡起來，還有助於引導其他有類似問題的人。

彆著急，不要指望幾秒鐘的谷歌搜尋就能解決一個複雜的問題。讀一下常見問題文件。在向專家提問之前，先向後靠靠放鬆一下，再思考一下問題。相信我們，他們能從你的提問看出你做了多少閱讀與思考，如果你是有備而來，將更有可能得到解答。不要將所有問題一股腦丟擲，只因你的第一次搜尋沒有結果（或者結果太多）。

認真地思考，準備好你的問題。輕率的提問只能得到輕率的回答，或者壓根沒有。在提問時，你越是表現出在此前做過思考與努力去解決自己的問題，你越有可能得到真正的幫助。

注意別提錯問題。如果提問基於錯誤的假設，某黑客多半會一邊想 “愚蠢的問題……”，一邊按將錯就錯的答案回覆你，並且希望這種只是得到你自己“問的問題”而非真正所需的解答，給你一個教訓。

永遠不要假設你 有資格 得到解答。你沒有這種資格，畢竟你沒有為此服務付費。如果你能夠提出有內容、有趣和激勵思考的問題──那種毫無疑問能夠向社羣貢獻經驗，而不僅僅是消極地要求從別人那獲取知識的問題，你將“掙到”答案。

另一方面，表明你有能力也樂意參與問題的解決是個很好的開端。“有沒有人能指個方向？”，我這還差點什麼？”，“我應該查哪個網站？”，通常要比 “請給出我可以用的完整步驟”更容易得到回覆，因為你表明了只要有人能指個方向，你就很樂意完成剩下的過程。

### 提問時

#### 仔細挑選論壇

要對在哪提問留心，如果你做了下述事情，多半會被一筆勾銷或被看成“失敗者”：

* 張貼與論壇主題無關的問題
* 在面向高階技術問題的論壇上張貼膚淺的問題，或者反之。
* 在太多不同的新聞組同時張貼
* 給既非熟人也沒有義務解決你問題的人傳送你私人的電郵

為保護通訊的渠道不被無關的東西淹沒，黑客會除掉那些沒有找對地方的問題，你不會想讓這種事落到自己頭上的。

因此，第一步是找對論壇。谷歌和其它搜尋引擎還是你的朋友，可以用它們搜尋你遇到困難的軟硬體問題最相關的專案網站。那裡通常都有專案的常見問題（FAQ）、郵件列表及文件的連結。如果你的努力（包括 閱讀 FAQ）都沒有結果，這些郵件列表就是最後能取得幫助的地方。專案的網站也許還有報告臭蟲的流程或連結，如果是這樣，去看看。

向陌生的人或論壇傳送郵件極有可能是在冒險。譬如，不要假設一個內容豐富的網頁的作者想充當你的免費顧問，不要對你的問題是否會受到歡迎做太樂觀的估計──如果你不確定，向別處發或者壓根別發。

在選擇論壇、新聞組或郵件列表時，別太相信名字，先看看 FAQ 或者許可書以明確你的問題是否切題。發貼前先翻翻已有的帖子，這樣可以讓你感受一下那裡行事的方式。事實上，張貼前在新聞組或郵件列表的歷史文件中搜尋與你問題相關的關鍵詞是個極好的主意，也許就找到答案了。即使沒有，也能幫助你歸納出更好的問題。

別象機關槍似的一次性“掃射”所有的幫助渠道，這就象大喊大叫一樣會令人不快，溫柔地一個一個來。

弄懂主題！最典型的錯誤之一是在某種致立於跨平臺可移植的語言、庫或工具的論壇中提關於 Unix 或 Windows 作業系統程式介面的問題。如果你不明白為什麼這是大錯，最好在搞清楚概念前什麼也別問。

一般來說，在仔細挑選的公共論壇中提問比在私有論壇中提同樣的問題更容易得到有用的回答。有幾個道理支援這點，一是看潛在的回覆者有多少，二是看論壇的參與者有多少，黑客更願回答能啟發多數人的問題。

可以理解，老練的黑客和一些流行軟體的作者正在承受過多的不當訊息。就象那根最後壓垮駱駝背的稻草一樣，你的加入也有可能使情況走向極端──已經好幾次了，一些流行軟體的作者退出了對自己軟體的支援，因為伴隨而來的湧入其私人郵箱的垃圾郵件變得無法忍受。

#### 面向新手的論壇和網際網路中繼聊天（IRC）通常響應最快

本地的使用者組織或者你所用的 Linux 發行版也許正在宣傳新手取得幫助的論壇或 IRC 通道（在一些非英語國家，新手論壇很可能還是郵件列表），這些地方是開始提問的好去處，特別是當你覺得遇到的也許只是相對簡單或者很普通的問題時。經過宣傳的 IRC 通道是公開邀請提問的地方，通常可以得到實時的回覆。

事實上，如果出問題的程式來自某發行版（這很常見），最好先去該發行版的論壇或郵件列表中提問，再到程式本身的專案論壇或郵件列表，（否則）該專案的黑客可能僅僅回覆“用 我們的 程式碼”。

在任何論壇發貼以前，先看看有沒有搜尋功能。如果有，就試著用問題的幾個關鍵詞搜尋一下，也許就有幫助。如果在此之前你已做過全面的網頁搜尋（你應該這樣去做），還是再搜尋一下論壇，搜尋引擎有可能沒來得及索引此論壇的全部內容。

通過論壇或 IRC 通道提供專案的使用者支援有增長的趨勢，電子郵件交流則更多地為專案開發者保留。所以先在論壇或 IRC 中尋求與該專案相關的幫助。

#### 第二步，使用專案的郵件列表

當某個專案存在開發者郵件列表時，要向列表而不是其中的個別成員提問，即使你確信他能最好地回答你的問題。查一查專案的文件和主頁，找到專案的郵件列表並使用它。採用這種辦法有幾個很好的理由：

* 向個別開發者提的問題（如果）足夠好，也將對整個專案組有益。相反，如果你認為自己的問題對整個專案組來說太愚蠢，這也不能成為騷擾個別開發者的理由。
* 向列表提問可以分散開發者的負擔，個別開發者（尤其是專案領導）也許太忙以至於沒法回答你的問題。
* 大多數郵件列表都要存檔，那些存檔將被搜尋引擎索引，如果你向列表提問並得到解答，將來其它人可以通過網頁搜尋找到你的問題和答案，也就不用再次發問了。
* 如果某些問題經常被問到，開發者可以利用此資訊改進文件或軟體本身，以使其更清楚。如果只是私下提問，就沒有人能看到最常見問題的完整場景。

如果一個專案既有 “使用者” 也有“開發者”（或 “黑客”）郵件列表或論壇，而你又不擺弄那些程式碼，向“使用者”列表或論壇提問。不要假設自己會在開發者列表中受到歡迎，那些人多半會遭受你的噪音干擾。

然爾，如果你 確信 你的問題不一般，而且在“使用者” 列表或論壇中幾天都沒有回覆，可以試試“開發者”列表或論壇。建議你在張貼前最好先暗暗地觀察幾天,至少看看最近幾天儲存的帖子,以瞭解那的行事方式（事實上這是參與任何私有或半私有列表的好主意）

如果你找不到一個專案的郵件列表，而只能查到專案維護者的地址，只管向其發信。即便在這種情況下，也別假設（專案）郵件列表不存在。在你的電子郵件中陳述你已經試過但沒有找到合適的郵件列表，也提及你不反對將自己的郵件轉發給他人（許多人認為，即使沒什麼祕密，私人電子郵件也不應該被公開。通過允許將你的電子郵件轉發他人，你給了相應人員處置你郵件的選擇）。

#### 使用有意義且明確的主題

在郵件列表、新聞組或論壇中，主題是你在五十個或更少的字以內吸引有資格專家注意的黃金機會，不要用諸如 “請幫我” （更別提大寫的 “請幫我！！！！”，這種主題的訊息會被條件反射式地刪掉）之類的嘮叨浪費機會。不要用你痛苦的深度來打動我們，相反，要在這點空間中使用超級簡明扼要的問題描述。

使用主題的好慣例是“物件──偏差”（式的描述），許多技術支援組織就是這樣做的。在“物件”部分指明是哪一個或哪一組東西有問題，在“偏差”部分則描述與期望的行為不一致的地方。

愚蠢：
>救命啊！我的筆記本視訊工作不正常！

明智：
>X.org 6.8.1 扭曲滑鼠游標，MV1005 型號的某顯示卡晶片組

更明智：
>使用 MV1005 型號的某顯示卡晶片組在 X.org 6.8.1 的滑鼠游標被扭曲

編寫 “物件──偏差”式描述的過程有助於你組織對問題的細緻思考。是什麼被影響了？僅僅是滑鼠游標或者還有其它圖形？只在 X.org 中出現？或只是在其 6.8.1 版中？是針對某顯示卡晶片組？或者只是其中的 MV1005 型號？一個黑客只需描一眼就能夠立即明白什麼是你遇到的問題，什麼是你自己的問題。

更一般地，想象一下在一個只顯示主題的文件索引中查詢。讓你的主題更好地反映問題，可以使下一個搜尋類似問題的人能夠在文件中直接就找到答案的線索，而不用再次發貼提問。

如果你想在回覆中提問，確保改變主題以表明你是在問一個問題，一個主題象 `Re: 測試` 或者 `Re: 新臭蟲` 的訊息不太可能引起足夠的注意。同時，將回復中與新主題不甚相關的引用內容儘量刪除。

對於列表訊息，不要直接點選回覆（按鈕）來開始一個全新的線索，這將限制你的觀眾。有些郵件閱讀程式，比如 mutt，允許使用者按線索排序並通過摺疊線索來隱藏訊息，這樣做的人永遠看不到你發的訊息。

僅僅改變主題還不夠。mutt 和其它一些郵件閱讀程式還要檢查郵件頭主題以外的其它資訊，以便為其指定線索，所以寧可發一個全新的郵件。

在論壇，因為訊息與特定的線索緊密結合，並且通常線上索之外不可見，好的提問方式略有不同，通過回覆提問並不要緊。不是所有論壇都允許在回覆中出現分離的主題，而且這樣做了基本上沒有人會去看。不過，通過回覆提問本身就是令人懷疑的做法，因為它們只會被正在檢視該線索的人讀到。所以，除非你 只想 在該線索當前活躍的人群中提問，還是另起爐灶比較好。

#### 使問題容易回覆

以`請向……回覆`來結束問題多半會使你得不到回答。如果你覺得花幾秒鐘在郵件客戶端設定一下回復地址都麻煩，我們也覺得花幾秒鐘考慮你的問題更麻煩。如果你的郵件客戶端程式不支援這樣做，換個好點的；如果是作業系統不支援所有這種郵件客戶端程式，也換個好點的。

在論壇，要求通過電子郵件回覆是完全無禮的，除非你確信回覆的資訊也許是敏感的（而且有人會為了某些未知的原因，只讓你而不是整個論壇知道答案）。如果你只是想在有人回覆線索時得到電子郵件提醒，可以要求論壇傳送。幾乎所有論壇都支援諸如`留意本線索`、`有回覆傳送郵件`等功能。

#### 用清晰、語法、拼寫正確的語句書寫

經驗告訴我們，粗心與草率的作者通常也粗心與草率地思考和程式設計（我敢打賭）。為這些粗心與草率的思考者回答問題沒有什麼好處，我們寧可將時間花在其它地方。

清楚、良好地表達你的問題非常重要。如果你覺得這樣做麻煩，我們也覺得注意（你的問題）麻煩。花點額外的精力斟酌一下字句，用不著太僵硬與正式──事實上，黑客文化很看重能準確地使用非正式、俚語和幽默的語句。但它 必須 很準確，而且有跡象表明你是在思考和關注問題。

正確地拼寫、使用標點和大小寫，不要將 `its` 混淆為 `it's`，`loose` 搞成 `lose` 或者將 “discrete” 弄成 “discreet”。不要全部用大寫，這會被視為無禮的大聲嚷嚷 （全部小寫也好不到哪去，因為不易閱讀。Alan Cox [注：著名黑客，Linux 核心的重要參與者] 也許可以這樣做，但你不行。）

一般而言，如果你寫得象個半文盲似的傻子，多半得不到理睬。也不要使用即時通訊中的簡寫，如將 `you` 簡化為 `u` 會使你看起來象一個為了節約二次擊鍵的半文盲式的傻子。更糟的是，如果象個小孩似地鬼畫桃符那絕對是在找死，可以肯定沒人會理你（或者最多是給你一大堆指責與挖苦）。

如果在非母語論壇提問，你的拼寫與語法錯誤會得到有限的寬容，但懶惰完全不會被容忍（是的，我們通常看得出其中的差別）。同時，除非你知道回覆者使用的語言，請使用英語書寫。繁忙的黑客一般會直接刪除用他們看不懂語言寫的訊息。在網際網路上英語是工作語言，用英語書寫可以將你的問題不被閱讀就被直接刪除的可能性降到最低。

如果你用英語書寫但它是你的第二語言，最好提醒潛在的回覆者語言上可能的困難以便繞過這個問題，比如：

* 英語不是我的母語，請諒解拼寫錯誤。
* 如果您使用某某語言，請電郵/私聊我，也許我需要您的協助翻譯我的問題。
* 對於這個技術術語本身我很熟悉，但對於它的一些俚語或習慣表達方式就不太明白了。
* 我已經同時用某某語及英語提問，如果您使用兩者之一回復，我很樂意翻譯。

#### 使用易於讀取且標準的檔案格式傳送問題

如果你人為地將問題搞得難以閱讀，它多半會被忽略，人們更願讀易懂的問題，所以：

* 使用純文字而不是 HTML（超文字標註語言）（ 關閉HTML 並不難）

* 使用 MIME（多用途網際網路郵件擴充套件）附件通常沒有問題，前提是真正有內容（譬如附帶的原始檔或補丁），而不僅僅是郵件客戶端程式生成的模板（譬如只是訊息內容的拷貝）。
* 不要傳送整段只是單行句子但多次折回的郵件（這使得回覆部分內容非常困難）。設想你的讀者是在80個字元寬的文字終端閱讀郵件，設定你的行折回點小於 80 列。
* 但是，也 不要 用任何固定列折回資料（譬如日誌檔案拷貝或會話記錄）。資料應該原樣包含，使回覆者確信他們看到的是與你看到的一樣的東西。
* 在英語論壇中，不要使用'Quoted-Printable' MIME 編碼傳送訊息。這種編碼對於張貼非 ASCII 語言可能是必須的，但很多郵件程式並不支援。當它們分斷時，那些文字中四處散佈的 “=20”符號既難看也分散注意力，甚至有可能破壞內容的語意。
* 永遠不要 指望黑客們閱讀使用封閉的專用格式編寫的文件，諸如微軟公司的 Word 或 Excel 檔案等。大多數黑客對此的反應就象有人將還在冒熱氣的豬糞倒在你門口時你的反應一樣。即使他們能夠處理，也很厭惡這麼做。
* 如果你從使用視窗的電腦傳送電子郵件，關閉問題頗多的微軟“聰明引用”功能（在“工具” -> “自動糾正選項”的“輸入時自動格式化”下去掉聰明引用的選框），以免在你的郵件中到處散佈垃圾字元。
* 在論壇，勿濫用“表情符號”和“HTML”功能(當它們提供時)。一兩個表情符號通常沒有問題，但花哨的彩色文字傾向於使人認為你是個無能之輩。過濫地使用表情符號、色彩和字型會使你看來象個傻笑的小姑娘。這通常不是個好主意，除非你只是對性而不是有用的回覆更有興趣。
* 如果你使用圖形使用者介面的郵件客戶端程式(如網景公司的 Messenger、微軟公司的 Outlook 或者其它類似的)，注意它們的預設配置不一定滿足這些要求。大多數這類程式有基於選單的`檢視原始碼`命令，用它來檢查傳送資料夾中的訊息，以確保傳送的是沒有多餘雜質的純文字檔案。

#### 描述問題應準確且有內容

* 仔細、清楚地描述問題的症狀
* 描述問題發生的環境(主機、作業系統、應用程式，任何相關的)，提供銷售商的發行版和版本號（如：“Fedora Core 7”、“Slackware 9.1”等）
* 描述提問前做過的研究及其理解。
* 描述提問前為確定問題而採取的診斷步驟。
* 描述最近對計算機或軟體配置的任何相關改變。
* 如果可能，提供在可控環境下重現問題的方法。
* 盡最大努力預測黑客會提到的問題，並提前備好答案。

如果你認為是程式碼有問題，向黑客提供在可控環境下重現問題的方法尤其重要。當你這麼做時，得到有用且及時回覆的可能性將大大增加。

[西蒙.泰瑟姆（Simon Tatham）](http://www.chiark.greenend.org.uk/%7Esgtatham/)寫過一篇《[如何有效報告臭蟲》](http://www.chiark.greenend.org.uk/%7Esgtatham/bugs-tw.html)的文章，我強烈推薦各位閱讀。

#### 量不在多，精煉則靈

你應該（寫得）精煉且有內容，簡單地將一大堆程式碼或資料羅列在求助訊息中達不到目的。如果你有一個很大且複雜的測試樣例讓程式崩潰，嘗試將其裁剪得越小越好。

至少有三個理由支援這點。第一，讓別人看到你在努力簡化問題使你更有可能得到回覆。第二，簡化問題使你更有可能得到 `有用的` 回覆。第三，在提純臭蟲報告的過程中，你可能自己就找到了解決辦法或權宜之計。

#### 別急於宣稱找到臭蟲

當你在一個軟體中遇到問題，除非你 非常、非常 的有根據，不要動輒聲稱找到了臭蟲。提示：除非你能提供解決問題的原始碼補丁，或者對前一版本的迴歸測試表現出不正確的行為，否則你都多半不夠完全確信。對於網頁和文件也如此，如果你（聲稱）發現了文件的“臭蟲”，你應該能提供相應位置的替代文字。

記住，還有許多其它使用者並未經歷你遇到的問題，否則你在閱讀文件或搜尋網頁時就應該發現了（[你在報怨前已經做了這些，是吧 ？](#你在報怨前已經做了這些，是吧 ？)）。這也意味著很有可能是你弄錯了而不是軟體本身有問題。

編寫軟體的人總是非常辛苦地使它儘可能完美。如果你聲稱找到了臭蟲，也就置疑了他們的能力，即使你是對的，也有可能會使其中的部分人感到不快。（此外，）在主題中嚷嚷“臭蟲”也是特別不老練的。

提問時，即使你私下非常確信已經發現一個真正的臭蟲，最好寫得象是 你 做錯了什麼。如果真的有臭蟲，你會在回覆中看到這點。這樣做的話，如果真有蟲子，維護者就會向你道歉，這總比你弄砸了然後欠別人一個道歉要強。

#### 低聲下氣代替不了做自己的家庭作業

有些人明白他們不應該粗魯或傲慢地行事並要求得到答覆，但他們退到相反的低聲下氣的極端：“我知道我只是個可憐的新丁，一個失敗者，但……”。這既使人困擾，也沒有用，當伴隨著對實際問題含糊的描述時還特別令人反感。

別用低階靈長類動物的辦法浪費你我的時間，相反，儘可能清楚地描述背景情況和你的問題，這比低聲下氣更好地擺正了你的位置。

有時，論壇設有單獨的初學者提問版面，如果你真的認為遇到了膚淺的問題，到那去就是了，但一樣別低聲下氣。

#### 描述問題症狀而不是猜測

告訴黑客是什麼導致了問題是沒用的（如果你的診斷理論是了不起的東西，你還會向別人諮詢求助嗎？）。所以，確保只是告訴他們問題的原始症狀，而不是你的解釋和理論，讓他們來解釋和診斷。如果你認為陳述自己的猜測很重要，應清楚地說明這只是你的猜測並描述為什麼它們不起作用。

愚蠢：
>我在編譯核心時接連遇到 SIG11 錯誤，懷疑主機板上的某根電路絲斷了，找到它們的最好辦法是什麼？

明智：
> 我組裝的電腦（K6/233 CPU、FIC-PA2007 主機板[威盛 Apollo VP2 晶片組]、Corsair PC133 SDRAM 256Mb 記憶體）最近在開機 20 分鐘左右、做核心編譯時頻繁地報 SIG11 錯，但在頭 20 分鐘內從不出問題。重啟動不會復位時鐘，但整夜關機會。更換所有記憶體未解決問題，相關的典型編譯會話日誌附後。

由於以上這點許多人似乎難以掌握，這裡有句話可以提醒你：“所有的診斷專家都來自密蘇里州”。美國國務院的官方座右銘則是“讓我看看”（出自國會議員威勒德.D.範迪弗［Willard D. Vandiver］在1899年時的講話：“我來自一個出產玉米、棉花、牛蒡和民主黨人的國家，滔滔雄辯既不能說服我，也不會讓我滿意。我來自密蘇里州，你必須讓我看看。”）針對診斷者而言，這並不是懷疑，而只是一種真實而有用的需求，以便讓他們看到與你看到的原始證據儘可能一致的東西，而不是你的猜測與總結。（所以，）讓我們看看。

#### 按時間先後羅列問題症狀

剛出問題之前發生的事情通常包含有解決問題最有效的線索。所以，記錄中應準確地描述你、電腦和軟體在崩潰前都做了什麼。在命令列處理的情況下，有會話日誌（如執行指令碼工具生成的）並引用相關的若干（如20）行記錄會非常有幫助。

如果崩潰的程式有診斷選項（如-v詳述開關），試著選擇這些能在記錄中增加排錯資訊的選項。記住，“多”不等於“好”。試著選取適當的排錯級別以便提供有用的資訊而不是將閱讀者淹沒在垃圾中。

如果你的記錄很長（如超過四段），在開頭簡述問題隨後按時間先後羅列詳細過程也許更有用。這樣，黑客在讀你的記錄時就知道該注意哪些內容了。

#### 描述目標而不是過程

如果你想弄清楚如何做某事（而不是報告一個臭蟲），在開頭就描述你的目標，然後才陳述遇到問題的特定步驟。

經常出現這種情況，尋求技術幫助的人在腦袋裡有個更高層次的目標，他們在自以為能達到目標的特定道路上被卡住了，然後跑來問該怎麼走，但沒有意識到這條路本身有問題，結果要費很大的勁才能通過。

愚蠢：
> 我怎樣才能讓某圖形程式的顏色拾取器取得十六進位制的 RGB 值？

明智：
> 我正試著用自己選定數值的顏色替換一幅圖片的色表，我現在知道的唯一方法是編輯每個表槽，但卻無法讓某圖形程式的顏色拾取器取得十六進位制的 RGB 值。

第二種提法是明智的，它使得建議採用更合適的工具以完成任務的回覆成為可能。

#### 別要求私下回覆電郵

黑客們認為問題的解決過程應該公開、透明，此過程中如果更有才能的人注意到不完整或者不當之處，最初的回覆才能夠、也應該被糾正。同時，作為回覆者也因為能力和學識被其它同行看到而得到某種回報。

當你要求私下回復時，此過程和回報都被中止。別這樣做，讓 回覆者 來決定是否私下回答──如果他真這麼做了，通常是因為他認為問題編寫太差或者太膚淺，以至於對其它人毫無意義。

對這條規則存在一條有限的例外，如果你確信提問可能會引來大量雷同的回覆時，那麼“向我發電郵，我將為論壇歸納這些回覆”將是神奇的句子。試著將郵件列表或新聞組從洪水般雷同的回覆中解救出來是非常有禮貌的──但你必須信守諾言。

#### 提問應明確

漫無邊際的問題通常也被視為沒有明確限制的時間無底洞。最有可能給你有用答案的人通常也是最忙的人（假如只是因為他們承擔了太多工作的話），這些人對於沒有止境的時間無底洞極其敏感，所以他們也傾向於討厭那些漫無邊際的問題。

如果你明確了想讓回覆者做的事（如指點方向、傳送程式碼、檢查補丁或其它），你更有可能得到有用的回覆。（因為）這樣可以讓他們集中精力並間接地設定了他們為幫助你需要花費的時間和精力上限，這很好。

要想理解專家生活的世界，可以這樣設想：那裡有豐富的專長資源但稀缺的響應時間。你暗中要求他們奉獻的時間越少，你越有可能從這些真正懂行也真正很忙的專家那裡得到解答。

所以限定你的問題以使專家回答時需要付出的時間最少──這通常與簡化問題還不太一樣。舉個例，“請問可否指點一下哪有好一點的 X 解釋？”通常要比“請解釋一下 X”明智。如果你的程式碼不執行了，通常請別人看看哪有問題比叫他們幫你改正更明智。

#### 關於程式碼的問題

別要求他人給你出問題的程式碼排錯而不提及應該從何入手。張貼幾百行的程式碼，然後說一聲“它不能執行”會讓你得不到理睬。只貼幾十行程式碼，然後說一句“在第七行以後，本應該顯示<x>，但實際出現的是<y>”非常有可能讓你得到回覆。

最精確描述程式碼問題的方法是提供一個能展示問題的最小測試樣例。什麼是最小測試樣例？它是對問題的展現，只需要剛好能夠重現非預期行為的程式碼即可。如何生成一個最小測試樣例？如果你知道哪一行或哪一段程式碼會產生問題，將其複製並提供剛好夠用的外圍支撐程式碼以構成一個完整的樣例（夠用是指原始碼剛好能被編譯器、直譯器或任何處理它的程式所接受）。如果你不能將問題縮小到特定的段落，複製原始碼並去除那些與問題無關的程式碼段。你能提供的最小測試樣例越小越好（參見 量不在多，精煉則靈 ）。

生成一個非常小的最小測試樣例並不總是可能，但盡力去做是很好的鍛練，這有可能幫助你找到需要自己解決的問題。即使你找不到，黑客們喜歡看到你努力過，這將使他們更合作。

如果你只是想讓別人幫忙審一下程式碼，在最開頭就要說出來，並且一定要提到你認為哪一部分特別需要關注以及為什麼。

#### 別張貼家庭作業式問題

黑客們善於發現“家庭作業”式的問題。我們中的大多數人已經做了自己的家庭作業，那是該 你 做的，以便從中學到東西。問一下提示沒有關係，但不是要求完整的解決方案。

如果你懷疑自己碰到了一個家庭作業式的問題，但仍然無法解決，試試在使用者組、論壇或（作為最後一招）在專案的“使用者”郵件列表或論壇中提問。儘管黑客們 會 看出來，一些老使用者也許仍會給你提示。

#### 刪除無意義的要求

抵制這種誘惑，即在求助訊息末尾加上諸如“有人能幫我嗎？”或“有沒有答案？”之類在語義上毫無意義的東西。第一，如果問題描述還不完整，這些附加的東西最多也只能是多餘的。第二，因為它們是多餘的，黑客們會認為這些東西煩人──就很有可能用邏輯上無誤但打發人的回覆，諸如“是的，你可以得到幫助”和“不，沒有給你的幫助”。

一般來說，避擴音“是或否”型別的問題，除非你想得到 “是或否”型別的回答。

#### 不要把問題標記為“緊急”，即使對你而言的確如此

這是你的問題，不要我們的。宣稱“緊急”極有可能事與願違：大多數黑客會直接刪除這種訊息，他們認為這是無禮和自私地企圖得到即時與特殊的關照。而且“緊急”或其它有類似含義的主題有可能觸發垃圾過濾規則，潛在的回覆者可能永遠看不到你的問題！

有一點點區域性的例外，如果你是在一些知名度很高、會使黑客們激動的地方使用程式，也許值得這樣去做。在這種情況下，如果你有期限壓力，也很有禮貌地提到這點，人們也許會有足夠的興趣快一點回答。

當然，這是非常冒險的，因為黑客們對什麼是令人激動的標準多半與你的不同。譬如從國際空間站這樣張貼沒有問題，但代表感覺良好的慈善或政治原因這樣做幾乎肯定不行。事實上，張貼諸如“緊急：幫我救救這個毛絨絨的小海豹！”肯定會被黑客迴避或光火，即使他們認為毛絨絨的小海豹很重要。

如果你覺得這不可思議，再把剩下的內容多讀幾遍，直到弄懂了再發貼也不遲。

#### 禮貌總是有益的

禮貌一點，使用 `請` 和 `謝謝你的關注` 或者 `謝謝你的關照`，讓別人明白你感謝他們無償花時間幫助你。

坦率地講，這一點沒有語法正確、文字清晰、準確、有內容和避免使用專用格式重要（同時也不能替代它們）。黑客們一般寧可讀有點唐突但技術鮮明的臭蟲報告，而不是那種有禮但含糊的報告。（如果這點讓你不解，記住我們是按問題能教我們什麼來評價它的）

然爾，如果你已經談清楚了技術問題，客氣一點肯定會增加你得到有用回覆的機會。

（我們必須指出，本文唯一受到一些老黑客認真反對的地方是以前曾經推薦過的“提前謝了”，一些黑客認為這隱含著事後不用再感謝任何人的暗示。我們的建議是要麼先說 `提前謝了`，事後 再 對回覆者表示感謝，要麼換種方式表達，譬如用 `謝謝你的關注` 或 `謝謝你的關照`）。

#### 問題解決後追加一條簡要說明

問題解決後向所有幫助過的人追加一條訊息，讓他們知道問題是如何解決的並再次感謝。如果問題在郵件列表或新聞組中受到廣泛關注，在那裡追加此訊息比較恰當。

最理想的方式是向最初提問的線索回覆此訊息，並在主題中包含 `已解決`、`已搞定` 或其它同等含義的明顯標記。在人來人往的郵件列表裡，一個看見線索 `問題 X` 和 `問題 X-已解決` 的潛在回覆者就明白不用再浪費時間了（除非他個人覺得“問題 X”有趣），因此可以利用此時間去解決其它問題。

追加的訊息用不著太長或太複雜，一句簡單的“你好──是網線壞了！謝謝大家──比爾”就比什麼都沒有要強。事實上，除非解決問題的技術真正高深，一條簡短而親切的總結比長篇大論要好。說明是什麼行動解決了問題，用不著重演整個排錯的故事。

對於有深度的問題，張貼排錯歷史的摘要是恰當的。描述問題的最終狀態，說明是什麼解決了問題，在此之後 才指明可以避免的彎路。應避免的彎路部分應放在正確的解決方案和其它總結材料之後，而不要將此訊息搞成偵探推理小說。列出那些幫助過你的名字，那樣你會交到朋友的。

除了有禮貌、有內容以外，這種型別的追帖將幫助其他人在郵件列表、新聞組或論壇文件中搜尋到真正解決你問題的方案，從而也讓他們受益。

最後，此類追帖還讓每位參與協助的人因問題的解決而產生一種滿足感。如果你自己不是技術專家或黑客，相信我們，這種感覺對於你尋求幫助的老手和專家是非常重要的。問題敘述到最後不知所終總是令人沮喪的，黑客們癢癢地渴望它們被解決。`撓癢癢` 為你掙到的信譽將對你下次再次張貼提問非常非常的有幫助。

考慮一下怎樣才能避免他人將來也遇到類似的問題，問問自己編一份文件或 FAQ 補丁會不會有幫助，如果是的話就將補丁發給維護者。

在黑客中，這種良好的後繼行動實際上比傳統的禮貌更重要，也是你善待他人而贏得聲譽的方式，這是非常有價值的財富。

### 如何解讀回答

#### “讀讀該死的手冊”（RTFM）和“搜搜該死的網路”（STFW）：如何明白你已完全搞砸

有一個古老而神聖的傳統：如果你收到 `讀讀該死的手冊`（RTFM） 的回覆，發信人認為你應該去“讀讀該死的手冊”。他或她多半是對的，去讀一下吧。

“讀讀該死的手冊”（RTFM）有個年輕一點的親戚，如果你收到“搜搜該死的網路”（STFW）的回覆，發信人認為你應該“搜搜該死的網路”。那人多半也是對的，去搜一下吧。(更溫和一點的說法是“[谷歌是你的朋友！](http://lmgtfy.com/)”)

在論壇，你也可能被要求去搜尋論壇的文件。事實上，有人甚至可能熱心地為你提供以前解決此問題的線索。但不要依賴這種關照，提問前應該先搜尋一下文件。

通常，叫你搜尋的人已經開啟了能解決你問題的手冊或網頁，正在一邊看一邊敲鍵盤。這些回覆意味著他認為：

* 第一，你要的資訊很容易找到。
* 第二，自已找要比別人喂到嘴裡能學得更多。

你不應該覺得這樣就被冒犯了，按黑客的標準，回覆者沒有不理你就是在向你表示某種尊敬，你反而應該感謝他熱切地想幫助你。

#### 如果還不明白……

如果你看不懂回答，不要馬上回復一個要求說明的訊息，先試試那些最初提問時用過的相同工具（如手冊、FAQ、網頁、懂行的朋友等）試著搞懂回答。如果還是需要說明，展現你已經明白的。

譬如，假如我告訴你：“看起來象是某輸入項有問題，你需要清除它”，接著是個 不好 的回帖：“什麼是某輸入項？”。而這是一個 很好 的跟帖：“是的，我讀了手冊，某某輸入項只在 -z 和 -p 開關中被提到，但都沒有涉及到如何清除它們，你指的是哪一個還是我弄錯了什麼？”

#### 對待無禮

很多黑客圈子中看似無禮的行為並不是存心冒犯。相反，它是直接了當、一針見血式的交流風格，這種風格對於更關注解決問題而不是使別人感覺舒服而混亂的人是很自然的。

如果你覺得被冒犯了，試著平靜地反應。如果有人真的做了過格的事，郵件列表、新聞組或論壇中的前輩多半會招呼他。如果這 沒有 發生而你卻光火了，那麼你發火物件的言語可能在黑客社羣中看起來是正常的，而 你 將被視為有錯的一方，這將傷害到你獲取資訊或幫助的機會。

另一方面，你會偶而真的碰到無禮和無聊的言行。與上述相反，對真正的冒犯者狠狠地打擊、用犀利的語言將其駁得體無完膚都是可以接受的。然爾，在行事之前一定要非常非常的有根據。糾正無禮的言論與開始一場毫無意義的口水戰僅一線之隔，黑客們自己莽撞地越線的情況並不鮮見。如果你是新手或外來者，避開這種莽撞的機會並不高。如果你想得到的是資訊而不是消磨時光，這時最好不要把手放在鍵盤上以免冒險。

（有些人斷言很多黑客都有輕度的自閉症或阿斯伯格綜合症，缺少用於潤滑人類社會“正常”交往所需的腦電路。這既可能是真也可能是假。如果你自己不是黑客，興許你認為我們腦袋有問題還能幫助你應付我們的古怪行為。只管這麼幹好了，我們不在乎。我們 喜歡 現在這個樣子，並且一般都對病號標記有站得住腳的懷疑。）

在下一節，我們會談到另一個問題，當 你 行為不當時會受到的“冒犯”。

### 別象失敗者那樣反應

在黑客社羣的論壇中有那麼幾次你可能會搞砸──以本文描述或類似的方式。你會被示眾是如何搞砸的，也許言語中還會帶點顏色。

這種事發生以後，你能做的最糟糕的事莫過於哀嚎你的遭遇、宣稱被口頭攻擊、要求道歉、高聲尖叫、憋悶氣、威脅訴諸法律、向其僱主報怨、忘了關馬桶蓋等等。相反，你該這樣去做：

熬過去，這很正常。事實上，它是有益健康與恰當的。

社羣的標準不會自己維持，它們是通過參與者積極而 公開 地執行來維持的。不要哭嚎所有的批評都應該通過私下的郵件傳送，這不是事情運作的方式。當有人評論你的一個說法有誤或者提出不同看法時，堅持聲稱受到個人攻擊也毫無益處，這些都是失敗者的態度。

也有其它的黑客論壇，受過高禮節要求的誤導，禁止參與者張貼任何對別人帖子挑毛病的訊息，並聲稱“如果你不想幫助使用者就閉嘴”。有思路的參與者紛紛離開的結果只會使它們變成了毫無意義的嘮叨與無用的技術論壇。

是誇張的“友誼”（以上述方式）還是有用？挑一個。

記著：當黑客說你搞砸了，並且(無論多麼刺耳地)告訴你別再這樣做時，他正在為關心你和他的社羣而行動。對他而言，不理你並將你從他的生活中濾除要容易得多。如果你無法做到感謝，至少要有點尊嚴，別大聲哀嚎，也別因為自己是個有戲劇性超級敏感的靈魂和自以為有資格的新來者，就指望別人象對待脆弱的洋娃娃那樣對你。

有時候，即使你沒有搞砸（或者只是別人想象你搞砸了）， 有些人也會無緣無故地攻擊你本人。在這種情況下，報怨倒是 真的 會把問題搞砸。

這些找茬者要麼是毫無辦法但自以為是專家的不中用傢伙，要麼就是測試你是否真會搞砸的心理專家。其它讀者要麼不理睬，要麼用自己的方式對付他們。這些找茬者在給自己找麻煩，這點你不用操心。

也別讓自己捲入口水戰，大多數口水戰最好不要理睬──當然，是在你核實它們只是口水戰、沒有指出你搞砸的地方，而且沒有巧妙地將問題真正的答案藏於其中之後（這也是可能的）。

### 提問禁忌

下面是些典型的愚蠢問題和黑客不回答它們時的想法。

問：我到哪可以找到某程式或 X 資源？

問：我怎樣用 X 做 Y？

問：如何配置我的 shell 提示？

問：我可以用 Bass-o-matic 檔案轉換工具將 AcmeCorp 文件轉為 TeX 格式嗎？

問：我的{程式、配置、SQL 語句}不執行了

問：我的視窗電腦出問題了，你能幫忙嗎？

問：我的程式不執行了，我認為系統工具X有問題

問：我安裝 Linux 或 X 遇到困難，你能幫忙嗎？

問：我如何才能破解超級使用者口令/盜取通道操作員的特權/檢視某人的電子郵件？

---

問：
> 我到哪可以找到某程式或 X 資源？

答：
> 在我找到它的同樣地方，笨旦──在網頁搜尋引擎上。上帝啊，難道還有人不知道如何使用 谷歌 嗎？

問：
> 我怎樣用 X 做 Y？

答：
> 如果你想解決的是 Y，提問時別給出可能並不恰當的方法。這種問題說明提問者不但對 X 完全無知，也對要解決的 Y 問題糊塗，還被特定形勢禁錮了思維。等他們把問題弄好再說。

問：
> 如何配置我的 shell 提示？

答：
> 如果你有足夠的智慧提這個問題，你也該有足夠的智慧去 “讀讀該死的手冊”（RTFM），然後自己去找出來。

問：
> 我可以用 Bass-o-matic 檔案轉換工具將 AcmeCorp 文件轉為 TeX 格式嗎？

答：
> 試試就知道了。如果你試過，你既知道了答案，又不用浪費我的時間了。

問：
> 我的{程式、配置、SQL 語句}不執行了

答：
> 這不是一個問題，我也沒有興趣去猜你有什麼問題──我有更要緊的事要做。看到這種東西，我的反應一般如下：

* 你還有什麼補充嗎？
* 噢，太糟了，希望你能搞定。
* 這跟我究竟有什麼關係？

問：
> 我的視窗電腦出問題了，你能幫忙嗎？

答：
> 是的，把視窗垃圾刪了，裝個象 Linux 或 BSD 的開源作業系統吧。

注意：如果程式有官方的視窗版或者與視窗有互動(如 Samba)，你 可以 問與視窗相關的問題，只是別對問題是由視窗作業系統而不是程式本身造成的回覆感到驚訝，因為視窗一般來說太差，這種說法一般都成立。

問：
> 我的程式不執行了，我認為系統工具 X 有問題

答：
> 你完全有可能是第一個注意到被成千上萬使用者反覆使用的系統呼叫與庫檔案有明顯缺陷的人，更有可能的是你完全沒有根據。不同凡響的說法需要不同凡響的證據，當你這樣聲稱時，你必須有清楚而詳盡的缺陷說明文件作後盾。

問：
> 我安裝 Linux 或 X 遇到困難，你能幫忙嗎？

答：
> 不行，我需要親手操作你的電腦才能幫你排錯，去向當地的 Linux 使用者組尋求方便的幫助（你可以在 這裡 找到使用者組列表）

注意：如果安裝問題與某 Linux 發行版有關，在針對 它 的郵件列表、論壇或本地使用者組織中提問也許是恰當的。此時，應描述問題的準確細節。在此之前，先用 “linux”和 所有 被懷疑的硬體 [作關鍵詞] 仔細搜尋。

問：
> 我如何才能破解超級使用者口令/盜取通道操作員的特權/檢視某人的電子郵件？

答：
> 想做這種事情說明你是個卑劣的傢伙，想讓黑客教你做這種事情說明你是個白痴。

#### 好問題與壞問題

最後，我將通過舉例來演示提問的智慧。同樣的問題兩種提法，一種愚蠢，另一種明智。

愚蠢：我在哪能找到關於 Foonly Flurbamatic 裝置的東西？
> 這個問題在乞求得到 “搜搜該死的網路”（STFW） 式的回覆。

明智： 我用谷歌搜尋過“Foonly Flurbamatic 2600”，但沒有找到什麼有用的，有誰知道在哪能找到這種裝置的程式設計資訊？
> 這個人已經搜尋過網路了，而且聽起來他可能真的遇到了問題。

愚蠢： 我不能編譯某專案的原始碼，它為什麼這麼破？
> 提問者假設是別人搞砸了，太自大了。

明智： 某專案的原始碼不能在某 Linux 6.2 版下編譯。我讀了常見問題文件，但其中沒有與某 Linux 相關的內容。這是編譯時的記錄，我做錯了什麼嗎？
> 提問者已經指明瞭執行環境，讀了常見問題文件（FAQ），列出了錯誤，也沒有假設問題是別人的過錯，這傢伙值得注意。

愚蠢： 我的主機板有問題，誰能幫我？
> 某黑客對此的反應可能是：“是的，還需要幫你拍背和換尿布嗎？”，然後是敲下刪除鍵。

明智： 我在 S2464 主機板上試過 X、Y 和 Z，當它們都失敗後，又試了 A、B 和 C。注意我試 C 時的奇怪症狀，顯然某某東西正在做某某事情，這不是期望的行為。通常在 Athlon MP 主機板上導致某某事情的原因是什麼？有誰知道我還能再試點什麼以確定問題？
> 相反地，這個人看來值得回答。他或她展現瞭解決問題的能力而不是坐等天上掉餡餅。

在最後那個問題中，注意“給我一個回答”與“請幫我看看我還能再做點什麼測試以得到啟發”之間細微但重要的差別。

事實上，最後那個問題基本上源於 2001 年 8 月 Linux 核心郵件列表（lkml）上的真實事件，是我（Eric）當時提了那個問題，我發現 Tyan S2462 主機板有神祕的宕機現象，郵件列表成員給我提供瞭解決此問題的關鍵資訊。

通過這種提問方式，我給了別人可以咀嚼玩味的東西。我設法使之對參與者既輕鬆又有吸引力，也表明了對同行能力的尊敬並邀請他們與我一起協商。通過告訴他們我已經走過的彎路，我還表明了對他們寶貴時間的尊重。

事後，當我感謝大家並評論這次良好的經歷時，一個 Linux 核心郵件列表的成員談到，他認為我得到答案並不是因為我的名字掛在列表上，而只是因為我正確的提問方式。

黑客們在某種方面是非常不留情面的精英分子。我想在這事上他是對的，如果我 表現得 象個不勞而獲的寄生蟲，不管我是誰都會被忽略或斥責。他建議將整個事件作為對其它人提問的指導，這直接導致了本文的編寫。

### 如果得不到回答

如果得不到回答，請不要認為我們不想幫你，有時只是因為被問到的小組成員的確不知道答案。沒有回覆不等於不被理睬，當然必須承認從外面很難看出兩者的差別。

一般而言，直接將問題再張貼一次不好，這會被視為毫無意義的騷擾。耐心一點，知道你問題答案的人可能生活在不同的時區，有可能正在睡覺，也有可能你的問題一開始就沒有組織好。

還有其它資源可以尋求幫助，通常是在一些面向新手的資源中。

有許多線上與本地的使用者組織，雖然它們自己不編寫任何軟體，但是對軟體很熱心。這些使用者組通常因互助和幫助新手而形成。

還有眾多大小商業公司提供簽約支援服務，別因為要付點錢才有支援就感到沮喪！畢竟，如果你車子的汽缸墊燒了，你多半還得花錢找個修理店把它弄好。即使軟體沒花你一分錢，你總不能指望服務支援都是免費的。

象 Linux 這樣流行的軟體，每個開發者至少有一萬個以上的使用者，一個人不可能應付這麼多使用者的服務要求。記住，即使你必須付費才能得到支援，也比你還得額外花錢買軟體要少得多（而且對封閉原始碼軟體的服務支援與開源軟體相比通常還要貴一點，也要差一點）。

### 如何更好地回答

態度和善一點。問題帶來的壓力常使人顯得無禮或愚蠢，其實並不是這樣。

對初犯者私下回復。 對那些坦誠犯錯之人沒有必要當眾羞辱，一個真正的新手也許連怎麼搜尋或在哪找 FAQ 都不知道。

如果你不確定，一定要說出來！ 一個聽起來權威的錯誤回覆比沒有還要糟，別因為聽起來象個專家好玩就給別人亂指路。要謙虛和誠實，給提問者與同行都樹個好榜樣。

如果幫不了忙，別妨礙。 不要在具體步驟上開玩笑，那樣也許會毀了使用者的安裝──有些可憐的呆瓜會把它當成真的指令。

探索性的反問以引出更多的細節。 如果你做得好，提問者可以學到點東西──你也可以。試試將很差的問題轉變成好問題，別忘了我們都曾是新手。

儘管對那些懶蟲報怨一聲“讀讀該死的手冊”（RTFM）是正當的，指出文件的位置（即使只是建議做個谷歌關鍵詞搜尋）會更好

如果你決意回答，給出好的答案。 當別人正在用錯誤的工具或方法時別建議笨拙的權宜之計，應推薦更好的工具，重新組織問題。

請回答真正的問題！如果提問者已經做了自己該做的研究，並且說明嘗試過` X，Y，Z，A，B 與 C` 都沒有得到想要的結果，那麼回覆 `試試 A 或 B` 或者給出一個內容為 `試一下 X，Y，Z，A，B 或 C` 的連結將極其無益！

幫助你的社羣從中學習。當回覆一個好問題時，問問自己 `如何修改相關檔案或 FAQ 文件以免再次解答同樣的問題？`，接著再向文件維護者發一份補丁。

如果你是在研究一番後才做出的回答，展現你的技巧而不是直接端出結果。畢竟“授人以魚，不如授人以漁”。

### 相關資源

如果需要個人電腦、Unix 和網際網路如何工作的基礎知識，參閱 [Unix 和網際網路工作的基本原理](http://en.tldp.org/HOWTO/Unix-and-Internet-Fundamentals-HOWTO/)。

當你釋出軟體或補丁時，試著按 [軟體釋出實踐](http://en.tldp.org/HOWTO/Software-Release-Practice-HOWTO/index.html) 操作。

### 鳴謝

伊夫林.米切爾（Evelyn Mitchell）貢獻了一些愚蠢問題例子並啟發了編寫`如何更好地回答問題`這一節，米哈伊爾.羅門迪克（Mikhail Ramendik）貢獻了一些特別有價值的建議和改進。
