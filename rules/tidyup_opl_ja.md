**現在ルール策定中ですので，今後変更となる可能性があります．**

# Tidy Up for OPL
* 本タスクは部屋の片付けを通じて，物体認識と物体把持にフォーカスする．
* 本競技のルールは，[World Robot Summit 2020](https://worldrobotsummit.org) の World Robot Challenge の競技の一つ，Tidy Upのカスタマイズ版である．
* [WRS2020ルールブック](https://wrs.nedo.go.jp/wrs2020/challenge/download/Rules/DetailedRules_Partner_EN.pdf)を参照し，本家ルールと違う点のみ本ドキュメントに示す．（本家ルールより本ドキュメントルールの方が優先される）

## Rule

### 2 Partner Robot Challenge Real Space

#### 2.2 Competition

- 大会では，全参加チームが同時に競技（タスク）を実施する
- タスクは3回行われ，各チーム3回のうちの最高得点がそのチームの得点となる
  - 各回の間にはインターバルが設けられる

#### 2.3 Standard Robot Platform

- 本タスクでは標準機は設定されない．ロボットインスペクションを通過したロボットが出場可能である

### 3 General Rules Tidy Up Here

#### Settings

##### Environment

- アリーナはWRS2020と同じものが用いられるが，オンラインチーム等一部チームでは完全に再現できないケースも許容される

##### Objects

- Known objects: 事前に運営委員から，3クラス（Food items，Kitchen items，Task items），各クラス3オブジェクト，全9オブジェクトのリストが公開される
- Unknown objects: 3クラス，各クラス1オブジェクト，全3オブジェクトが設定され，競技開始直前に運営委員より告知される．
- Boss-character: 本タスクではBoss-characterは設定されない

#### 3.5 Before the Competition

競技の数日～数週間前

- 各チームには，オブジェクトの現物が運営委員より郵送で届けられる
  - Known objectsは届き次第開封し，調整に用いてよい
  - Unknown objectsは，その旨が箱に書いてあるので，開封してはならない

競技の30分前から

- 運営委員はオブジェクトの初期設置場所を各チームへ伝えるので，各チームはその通りにオブジェクトを並べなければならない
- 運営委員は各チームへUnknown objectsの番号を指定するので，各チームはその番号の箱を開け，中のオブジェクトを取り出し，運営委員の指示通りに設置しなければならない

#### 3.6 During the Competition

- タスクは全ての参加チームが同時に実施する
- タスクは3回行われ，各チーム3回のうちの最高得点がそのチームの得点となる
- チームの最高得点が最も高いチームの優勝とする

### 3.7 Scores

- Bonus Points
  - Boss-character: Boss-characterは設定されない．そのため，これに関連したボーナスポイントはない
  - Opening the three shelf drawers: 本タスクではボーナスポイントは与えられない（本タスクではドロアーは使われず，タスク実施中は常に閉じている）

### 4 Appendix

#### 4.2 Arena Setup

##### 4.2.1 Room 1

- Search AreaはLong Table Bに限定される（全てのオブジェクトはLong Table Bに置かれる．Tall Tableや床にオブジェクトが設置されることはない）
- Search Areaのオブジェクト数は5つであり，4つがKnown object，1つがUnknown objectである

##### 4.2.2 Room 2

- Obstacle Avoidance AreaやFood Areaに置かれるものは，全てのクラスから選ばれる
  - Obstacle Avoidance Areaには3つのKnown objectsが設置される
  - Food Areaには2つのKnown objectsと1つのUnknown objectsが設置される
    - 設置されるオブジェクトはFood itemsに限定されない
- Food Areaのオブジェクトは，お互いに別のオブジェクトを隠すように置かれることはない

#### 4.3 Object to be used

- YCBオブジェクトは使用されない
- 現在運営委員で選定中である
- オブジェクトはロボットに持ちやすいものが設定される．例えばFood itemsでは，[2019年](https://github.com/RoboCupAtHomeJP/AtHome2019/blob/master/OPL_ObjectList_Known%26Alike.pdf)や[2020年](https://github.com/RoboCupAtHomeJP/AtHome2020/blob/master/documents/OPL_Object_List_2020.pdf)のオブジェクトリストのようなものが選ばれる

## お知らせ
* タスクの理解の参考に，[こちらの動画](https://youtu.be/-73t0L2woi8)を合わせてご覧ください
