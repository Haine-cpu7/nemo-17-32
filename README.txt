NEMO : 17:32  COMPLETE v0.5.9

■ 起動方法
1. ZIPを展開
2. index.html をダブルクリック
3. ブラウザでそのまま遊べます

■ 必要環境
・Windows 11 などの一般的なPC
・Chrome / Edge / Firefox 推奨
・インストール不要 / Python不要 / ネット接続不要

■ 操作
クリック / Enter / Space / → : 次へ
SAVE : 進行をブラウザ保存
LOAD : 保存位置から再開
LOG : バックログ
SOUND : システム音ON/OFF
TITLE : タイトルへ
17:32 ARCHIVE : 回収済みスチル／記録断片を閲覧

■ v0.3 収録
PROLOGUE「観測者」
CHAPTER 01「接触」
CHAPTER 02「介入」
CHAPTER 03「名前」
CHAPTER 04「観測外」
CHAPTER 05「二重記録」
CHAPTER 06「17:32」
CHAPTER 07「欠損」
CHAPTER 08「記録者」
CHAPTER 09「処分」
CHAPTER 10「亡霊」
CHAPTER 11「選択」

■ v0.3の核
榊消失後、ねも視点へ移行。
榊の個人記録と公式監査記録を発見し、
STATUS : TERMINATED の意味に到達します。
その後、榊は「実在する人物」ではなく、
ねもの記憶・判断・罪悪感の中で喋り続ける存在になります。

※v0.2のセーブデータが同じブラウザに残っている場合、CONTINUEから読み込めるよう互換処理を入れています。


■ v0.3.1 修正
v0.3に残っていた旧v0.2の終了フラグを削除。
CHAPTER 06終了後、そのままCHAPTER 07「欠損」へ進むよう修正しました。
v0.3 / v0.2 のセーブデータも読み込み対象です。


■ v0.3.2 追加
タイトル画面に「EXTRA / 非正史」を追加。

EXTRA END：
『観測するものがいなければ、観測されない』

榊を消されたねもが、半獣の身体能力で観測施設へ物理的に殴り込み、
N.E.M.O. OBSERVATION NETWORKそのものを停止させます。

完全な非正史・おもしろENDです。
本編の正史には一切影響しません。
EXTRAルートではSAVE不可です。


■ v0.3.3 追加
英語のSYSTEM表示を「英語＋日本語訳」の二段表記に変更しました。

・英語の演出はそのまま残します
・直下に小さめの日本語訳を表示します
・SYSTEM話者の英語メッセージにも日本語訳を追加します
・本編、EXTRA / 非正史の両方に適用

雰囲気を崩さず、意味を追えるようにしたUI改善版です。


■ v0.3.4 UI調整
SYSTEM表示の日本語補助文から「日本語訳」「【日本語】」という見出しを削除。
英語の下に、日本語訳だけが自然に続く表示へ変更しました。


■ v0.4.0 正史本編 完結
CHAPTER 12「観測拒否」
CHAPTER 13「榊なら」
CHAPTER 14「それは榊じゃない」
CHAPTER 15「17:32」
CHAPTER 16「記録終了」
FINAL「誰にも渡さない」

ねもは、死んだ榊を忘れるのではなく、
「榊を抱えたまま、自分で決める」地点へ到達します。

榊が残した17分32秒の観測欠損技術を、
ねも自身が最後に一度だけ使い、
NEMO本人ではなく“NEMOの記録”だけを終了させます。

正史本編はFINALで完結。
EXTRA / 非正史ルートも引き続き収録されています。

v0.3.4以前のセーブデータを同じブラウザから読み込み可能です。


■ v0.4.1 追加
・URL共有用 OGP画像（ogp.png）を追加
・ねもちゃんの顔ファビコン（favicon.ico / favicon-32.png / favicon-192.png / favicon-512.png / apple-touch-icon.png）を追加
・index.html に OGP / Twitter Card / favicon 設定を追加
・公開URL想定： https://haine-cpu7.github.io/nemo-17-32/


■ v0.4.2 追加
タイトル画面に
・EXTRA I / 非正史
・EXTRA II / 王女魔法
を表示。

EXTRA II「落ちろ、記録の星」
榊を消されたことで、王女としての記憶と魔法を取り戻したねもが、
観測者たちの観測網そのものへ神話的な裁きを下す非正史ルートです。

観測の要塞「THRONE EYE（玉座の眼）」を空から落とし、
最終的に
N.E.M.O. OBSERVATION NETWORK / STATUS : OFFLINE / CAUSE : NEMO
で終了します。

本編・公開用OGP/ファビコンを含んだ公開素材版です。


■ v0.4.3 スマホUI改善
・タイトル画面をスマホ専用レイアウト化
・NEMO : 17:32を一行表示
・NEW RECORD / CONTINUE / EXTRA I / EXTRA II を2×2グリッド配置
・ゲーム中の上部操作メニューを2段化
・SYSTEM表示、会話ボックス、選択肢、バックログをスマホ幅に最適化
・iPhone等のSafe Areaに対応
・PCレイアウトは従来のまま維持


■ v0.4.4 スマホUI修正
・スマホ版で会話ボックスの話者名（ねも / 榊など）が上端で切れる問題を修正
・話者名ラベルをスマホ時のみ会話枠内へ収納
・長文スクロール時にもラベルがクリップされないよう調整
・本文の上余白を増やし、話者名と本文が重ならないよう修正
・PC版レイアウトは変更なし


■ v0.4.5 EXTRA解禁仕様
・EXTRA I / EXTRA II は初回起動時 LOCKED
・正史本編 FINAL「誰にも渡さない」の END 到達で両EXTRAを解禁
・クリア状態はブラウザのlocalStorageに保存され、再訪後も解禁状態を維持
・旧版の手動SAVEがFINAL地点にある場合はクリア済みとして移行
・EXTRA側から本編クリア扱いになることはありません


■ v0.4.6 EXTRA RECORD化
「非正史」というUI表記を廃止し、世界観に合わせて EXTRA RECORD に統一。

本編クリア後に解禁：
EXTRA RECORD I
NEMO : UNCHAINED
「獣は、もう眠らない。」

EXTRA RECORD II
FALL, STAR OF RECORDS
「王女は、観測を許さない。」

EXTRA RECORD I の冒頭を改稿。
榊透の死によって怒りで突然獣化するのではなく、
人の世界で生きるためにねも自身が抑えていた「本来の獣の力」の鎖が外れる設定へ変更。
BEAST INSTINCT SUPPRESSION / SELF-RESTRAINT / ORIGINAL BEAST AUTHORITY 演出を追加。

本編正史への影響はありません。


■ v0.4.7 EXTRA RECORD III 追加

本編クリア後に、EXTRA RECORD I / II / III の3本が解禁されます。

EXTRA RECORD III
NEMO : STILL I CHOOSE THIS WORLD
「それでも、ねもはこの世界を選ぶ。」

榊を取り戻すために WORLD-0000 を復元できる「PROJECT N.E.M.O. / LAST RESORT」を発見。
しかし実行すれば現在の世界線と、そこにいる生命・関係・記憶は保証されません。

「榊に会いたい」という願いと、
「知らない誰かの今日まで消していいのか」という選択の間で、
ねも自身が世界を残すことを決めるIFストーリーです。

クライマックスでは王女の力を「世界を壊すため」ではなく
「世界を作り直す装置を止めるため」に使用します。

EXTRA RECORD III END:
NEMO : STILL I CHOOSE THIS WORLD

世界は、正しくない。
それでも、なくしていいものではない。

※正史には影響しません。
※EXTRA RECORDはSAVE不可。
※スマホでは5つ目のEXTRA RECORD IIIボタンを独立した横一列に配置し、見切れを防止。


■ v0.4.8 EXTRA RECORD IV 追加

EXTRA RECORD IV
NEMO : BROKEN SIGNAL
「誰も、無傷では帰れない。」

PROJECT ECHO（プロジェクト・エコー）：
榊透が残したNEMO観測記録を用いて、ねもの次の行動を予測する計画。
ECHO適合観測者・久世 朔（OBSERVER 0909）は、過去の観測事故で自分自身の記憶の一部を失っており、
欠けた記憶を他者の観測記録で補うシステムに依存しています。

ねもの強さの根源：
榊の死を契機に、王女としての魔法よりも、人としての理性よりも古い
「PRIMAL NEMO / 原始NEMO」の力が覚醒。
これは王家由来ではなく、観測記録以前からNEMOの奥に存在していた原始的な力です。

PROJECT ECHOは榊が知る「ねも」を高精度で予測できますが、
原始NEMOが覚醒するにつれ予測一致率は
98.7% → 91.2% → 73.4% → 41.8% → 18.3% → 8.6% → 0.0%
へ崩壊します。

ただし覚醒は勝利演出ではありません。
ねもは原始NEMOに侵食され、人間らしい言語・自己抑制を失いかけます。
一方、久世はECHO同期を深めるほど榊透の記録に侵食され、自分自身との境界を失います。

ねもは獣へ。
久世は死者の残響へ。
双方が「自分ではないもの」に近づきながら戦う、泥沼のIFです。

最終的に勝敗は判定不能。
二人で榊透モデルを消去し、PROJECT ECHOを終わらせます。

END:
「誰かを失ったことに、勝敗で意味を与えることはできない。」

※正史には影響しません。
※EXTRA RECORDは本編クリア後に解禁。
※SAVE不可。
※スマホタイトル画面は NEW / CONTINUE / EXTRA I〜IV の2列×3段配置。


■ v0.4.9 スマホ会話画面バランス調整
・スマホ版で上部ナビ〜会話ボックス間の空白が広すぎる問題を調整
・会話ボックスを下端固定のまま縦方向へ拡張
・高さを clamp(260px, 31dvh, 390px) に変更
・中央の無意味な空白を大きく削減
・話者名の枠内表示、スクロール、Safe Area対応は維持
・選択肢表示位置を少し上へ調整
・PC版レイアウトは変更なし


■ v0.5.0 スマホタイトル画面整理
・スマホタイトル画面の6ボタンを2列×3段に統一
・NEW RECORD / CONTINUE
・EXTRA RECORD I / EXTRA RECORD II
・EXTRA RECORD III / EXTRA RECORD IV
・すべて同じ幅・同じ高さ
・EXTRA IIIの横2列ぶち抜き表示を廃止
・長いLOCKED表示も中央揃えで収まるよう調整
・PC版レイアウトは変更なし


■ v0.5.1 タイトル画面キャッシュ対策
・iPhone / Safari で古い style.css が残り、EXTRA RECORD III が横長のまま表示されるケースに対応
・style.css / script.js に ?v=0.5.1 のクエリを付与して強制再取得
・さらに index.html にスマホタイトル画面の 2列×3段グリッドを inline style で明示
・6ボタンの位置を nth-child で固定
  1段目 NEW RECORD / CONTINUE
  2段目 EXTRA RECORD I / EXTRA RECORD II
  3段目 EXTRA RECORD III / EXTRA RECORD IV
・PC版レイアウトは変更なし


■ v0.5.2 エピソード終了後の自動タイトル復帰
・本編 / EXTRA の end シーン到達後、約5秒で自動的にタイトルへ戻る
・終了シーン表示直後に「5秒後にタイトルへ戻ります」トースト表示
・途中でタップ / Enter した場合は即タイトルへ戻る
・タイトルへ戻る／別ルート開始／ロード時にはタイマーを自動解除
・本編クリア判定と EXTRA RECORD 解禁は従来どおり維持


■ v0.5.3 EXTRA RECORD IV 幻覚ENDへ改稿

EXTRA RECORD IV「NEMO : BROKEN SIGNAL」の終盤を全面改稿。

・PROJECT ECHOの接続が切れたあとも、ねもには榊の声が聞こえ続ける
・久世が「そこには誰もいない」と現実を指摘
・ねもは榊の幻覚と会話しながら久世との戦闘を継続
・久世の最期の言葉は「榊は、そんなこと言わない」
・ねもの攻撃により久世朔は死亡
・その後も榊の声は消えず、SYSTEM上は外部話者／外部音声源なし
・REALITY DISCRIMINATION : FAILED
・エピローグでは、ねもは幻覚の榊と一緒に肉まんを二つ買う
・現実にはねも一人だが、本人の中には「榊と生きる世界」が完成している

正史の
「いて。でも、決めるのはねも。」
「あなたは榊じゃない。」
という現実回帰の逆方向にあたるIF。

EXTRA RECORD IV END:
「ねもの中には、榊と生きる世界が完成していた。」

※本編・他EXTRA RECORDには影響しません。
※end到達後5秒で自動タイトル復帰するv0.5.2仕様を維持。


■ v0.5.4 EXTRA RECORD V 追加

EXTRA RECORD V
NEMO : GIVE HIM BACK
「榊を、返して。」

復讐ではなく「榊を返してほしい」という願いそのものが世界より強くなり、
NEMOの世界起源／因果権限が覚醒するIF。

観測システムに榊の復元を拒否され続けたねもが
「なんのために全部記録してたの」
「榊を返してよぉぉぉぉぉぉ！！」
と限界を迎え、WORLD-0000に由来する因果中心として覚醒。

世界は「榊が生きている世界」へ再構築され始めるが、
現在の世界線とは両立できないため完全消去が必要となる。

ねもは「榊がいないところには、戻らない」と選び、
街・人・観測記録・現在の世界線そのものが消失。

最終的に白い世界で榊と再会したように見えるが、
SYSTEM上は
POPULATION : 1
EXTERNAL HUMAN LIFE : 0
SAKAKI TORU : NOT VERIFIED
であり、榊が本当に復元されたかは確認できない。

END:
「世界は終わった。
ねもの願いだけが、残った。」

※正史には影響しません。
※本編クリア後に EXTRA RECORD I〜V が解禁。
※SAVE不可。
※end到達後5秒で自動タイトル復帰する仕様を維持。
※スマホでは7個目の EXTRA RECORD V を最下段横いっぱいに配置。


■ v0.5.5 PC記録パネル表示修正
・PC版で左上の記録／システムパネル下端が会話ボックスに隠れる問題を修正
・記録パネルに下端制約を追加し、会話ボックスの上までで表示を停止
・はみ出す分はパネル内スクロールに変更
・z-indexを調整し、記録パネルが会話ボックスに埋もれないよう修正
・スマホ版のレイアウトは変更なし


■ v0.5.6 選択肢話者修正
・PROLOGUE p150「昨日もいたよね？」の選択肢は榊の言葉として扱う
・選択後の収束台詞「……たぶん、人違い。」の話者を「ねも」から「榊」へ修正
・choiceSpeaker を追加し、選択肢ごと／シーンごとに返答話者を明示できる仕組みに変更
・他の本編／EXTRA RECORDの内容は変更なし


■ v0.5.8 17:32 ARCHIVE 追加
恋愛ADVのCGギャラリーのような「スチル収集」機能を追加。

・タイトル画面に「17:32 ARCHIVE」を追加
・全17枠（17分に対応）
・物語中の特定シーン到達で自動回収
・未回収は LOCKED 表示
・回収済みはサムネイル＋記録名を表示
・クリック／タップで全画面表示
・全画面表示では前後の回収済みスチルへ移動可能
・回収状態は localStorage に保存
・旧セーブデータから、本編の到達地点までのスチルを自動復元
・本編クリア済みユーザーは、本編分12枚を自動復元
・EXTRA RECORD I〜Vは各END到達時に1枚ずつ回収
・SAVE / LOAD、EXTRA解禁、END後5秒復帰、Safariキャッシュ対策等は維持
・SAVE_KEYを v0.5.8 へ更新し、v0.5.6以前をLEGACY_SAVE_KEYSで互換読み込み
・style.css / script.js のキャッシュバスターを ?v=0.5.7 へ更新

17枚の内訳：
01 FIRST CONTACT
02 INTERVENTION
03 NAME
04 OUTSIDE OBSERVATION
05 DOUBLE RECORD
06 17:32
07 MISSING RECORD
08 PRIVATE ARCHIVE
09 TERMINATED
10 GHOST
11 I CHOOSE
12 NO ONE ELSE
13 UNCHAINED
14 FALL, STAR OF RECORDS
15 STILL I CHOOSE THIS WORLD
16 BROKEN SIGNAL
17 GIVE HIM BACK

※今回の画像17枚は、制作中に作成したビジュアルを仮スチルとして収録しています。
　stills/still_01.webp ～ still_17.webp を同名ファイルで差し替えるだけで、
　今後画像だけ更新できます。


[v0.5.9]
- 17:32 ARCHIVE の EXTRA RECORD II スチル（still_14.webp）を、観測要塞落下時の巨大魔法陣イラストへ差し替え。
- index.html のキャッシュバージョンを 0.5.9 に更新。


[v0.6.2]
- 17枚固定アーカイブを廃止。
- ユーザーが明示的に採用したスチルだけを表示する方式へ変更。
- 現在の採用スチルは EXTRA RECORD II（巨大魔法陣）と EXTRA RECORD IV（ねも vs 久世）の2枚のみ。
- 未採用の仮スチル画像を配布物から削除。
- 旧アーカイブ進行から採用済み2枚のみ移行。


[v0.6.1]
- APPROVED STILLS ONLY の EXTRA RECORD IV スチルを、指定された新しい「久世 vs ねも」イラストへ差し替え。
- index.html のキャッシュバージョンを 0.6.1 に更新。


[v0.6.2]
- APPROVED STILLS ONLY に本編スチル「17:32」を追加。
- 画像: stills/main_1732.webp
- トリガー: c6_360
- index.html のキャッシュバージョンを 0.6.2 に更新。


[v0.6.3]
- EXTRA RECORD V / NEMO : GIVE HIM BACK のスチルを追加。
- 主様が明示採用した「榊を返して」と激高するねものイラストのみ追加。
- ARCHIVE は採用済み4枚のみ。
- index.html のキャッシュバージョンを 0.6.3 に更新。


[v0.6.4]
- ARCHIVEを追加順ではなく、物語/ルート順に並ぶ方式へ変更。
- 現在の表示順: 本編 17:32 → EXTRA II → EXTRA IV → EXTRA V。
- ARCHIVE内部IDを意味ベースの固定IDへ変更し、表示番号は並び順から自動採番。
- 今後スチルを途中へ追加しても、既存の解放記録が別の絵に化けない構造へ変更。
- v0.6.0系および旧17枚版からのARCHIVE解放状態を移行。


[v0.6.5]
- EXTRA RECORD II / FALL, STAR OF RECORDS のスチルを最終採用版へ差し替え。
- 片手を掲げ、冷えた『さようなら』の表情で観測要塞を落とすねも。
- ARCHIVEの並び順・解放状態・他の採用スチルは変更なし。
- index.html のキャッシュバージョンを 0.6.5 に更新。


[v0.6.6]
- CHAPTER 04 / 観測外 の川辺スチルを追加。
- ARCHIVE名: OFF RECORD
- トリガー: c4_130
- 本編時系列に従い、17:32より前へ配置。
- 既存スチルの解放状態・内部IDは維持。
- ARCHIVEは採用済み5枚のみ。


[v0.6.7]
- 本編 CHAPTER 09 / 処分 の正式スチル「TERMINATED」を追加。
- 画像: stills/main_terminated.webp
- トリガー: c9_080
- ARCHIVE時系列: OFF RECORD → 17:32 → TERMINATED → EXTRA II → EXTRA IV → EXTRA V。
- 既存スチルの内部IDと解放状態は維持。
- ARCHIVEは採用済み6枚のみ。


[v0.6.8]
- 本編 CHAPTER 02 / 介入 の正式スチル「INTERVENTION」を追加。
- 画像: stills/main_intervention.webp
- トリガー: c2_060
- ねもは雨の中で傘を差していたが、榊に腕を引かれ、傘が地面へ落ちた場面として採用。
- ARCHIVE時系列: INTERVENTION → OFF RECORD → 17:32 → TERMINATED → EXTRA II → EXTRA IV → EXTRA V。
- ARCHIVEは採用済み7枚のみ。


[v0.6.9]
- 本編 CHAPTER 14 / それは榊じゃない の正式スチル「NOT SAKAKI」を追加。
- 画像: stills/main_not_sakaki.webp
- トリガー: c14_040
- ARCHIVE時系列: INTERVENTION → OFF RECORD → 17:32 → TERMINATED → NOT SAKAKI → EXTRA II → EXTRA IV → EXTRA V。
- 既存スチルの内部IDと解放状態は維持。
- ARCHIVEは採用済み8枚のみ。


[v0.7.0]
- 本編 FINAL / 誰にも渡さない の正式スチル「TWO BUNS」を追加。
- 画像: stills/main_two_buns.webp
- トリガー: f_160
- ARCHIVE時系列: INTERVENTION → OFF RECORD → 17:32 → TERMINATED → NOT SAKAKI → TWO BUNS → EXTRA II → EXTRA IV → EXTRA V。
- 正史ラストの、ねもが肉まんを二つ持つ場面を採用。
- 既存スチルの内部IDと解放状態は維持。
- ARCHIVEは採用済み9枚のみ。


[v0.7.1]
- 本編 CHAPTER 06 / 17:32 のスチルを正式採用版へ差し替え。
- 画像: stills/main_1732.webp を新イラストへ更新。
- 観測端末越し / 榊が片手でカメラを塞ぐ / 観測ノイズあり、の決定版へ変更。
- 既存のARCHIVE順・内部ID・解放状態は維持。
