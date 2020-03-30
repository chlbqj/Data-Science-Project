# Data Science Project

### Project Name
TED Talks文本分析關鍵字與流量之關係

### 資料內容
  * __name__: The official name of the TED Talk. Includes the title and the speaker.
  * __title__: The title of the talk
  * __description__: A blurb of what the talk is about.
  * __main_speaker__: The first named speaker of the talk.
  * __speaker_occupation__: 主講者的職業。
  * __num_speaker__: The number of speakers in the talk.
  * __duration__: 演講時長(seconds)
  * __event__: The TED/TEDx event where the talk took place.
  * __film_date__: 演講日期為Unix timestamp格式。</br>*Python語法：先 import time 然後 time.time()*
  * __published_date__: The Unix timestamp for the publication of the talk on TED.com
  * __comments__: The number of first level comments made on the talk.
  * __tags__: The themes associated with the talk.
  * __languages__: The number of languages in which the talk is available.
  * __ratings__: A stringified dictionary of the various ratings given to the talk (inspiring, fascinating, jaw dropping, etc.)
  * __related_talks__: A list of dictionaries of recommended talks to watch next.
  * __url__: The URL of the talk.
  * __views__: The number of views on the talk.

### 可分析方向
  1. 利用word count看那些關鍵字(title、tag、description)特別常出現或觀看率較高
  2. __語言種類__跟觀看率關係
  3. __演講者職業__跟觀看率關係
  4. 各場次(event)的觀看次數比較
  5. ~~*與相關演講使用word vector進行cosine_simliarity*~~
  6. 留言與觀看次數關係
  7. 依各年度分析演講場次數、觀看次數
  8. 看那些主講者觀看次數一定很高
  9. ...

#### 3/30 討論
  * 分工
    - 有有、彥穎：資料視覺化
    - 嘉輝、河翰：做__可分析方向__第一點
  * 4/6 開會
    - 報告進度
  * 看進度是否做機器學習推薦影片
