NEMO : 17:32  COMPLETE v0.4.8

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
