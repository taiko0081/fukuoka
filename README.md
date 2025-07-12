# 福岡勤務という選択

福岡勤務の魅力を紹介するプロモーションサイト

## 概要

このサイトは福岡で実際に働いているメンバーからのリアルな体験をシェアするために作成されました。
iPad Airブルーをベースとした洗練されたデザインで、3分程度で読めるレポート形式になっています。

## 特徴

- **4つの魅力**: 通勤時間10分、昼食は自宅で、終電の心配なし、美味しいご飯
- **おすすめ店紹介**: 鳥鶏研究団、博多創作居酒屋 ふとっぱら、博多炭処 我が家
- **デザインシステム**: Warm Modern Card Design
- **カラーパレット**: 非常に薄い青のモノトーン
- **レスポンシブ対応**: スマートフォン・タブレット・PC完全対応
- **滑らかなアニメーション**: カードホバー効果、フェードイン、段階的表示

## デザインの特徴

### カラーパレット
```css
--primary-blue: #E8EDF7;      /* 非常に薄いブルー */
--secondary-blue: #F1F5FA;    /* より薄いブルー */
--accent-blue: #F8FAFD;       /* 最も薄いブルー */
--soft-blue: #D6E3F0;         /* ソフトブルー */
--medium-blue: #B8CDE6;       /* ミディアムブルー */
```

### デザインシステム
- **カードベースレイアウト**: 情報を整理しやすく表示
- **グラデーション背景**: 薄い青の美しいグラデーション
- **ホバーエフェクト**: カードのリフトアップとスケール変化
- **インタラクション**: スムーズなアニメーションとトランジション

## ファイル構成

```
fukuoka/
├── index.html              # メインHTMLファイル
├── images/                 # 画像ファイル
│   ├── toritorikenkyudan-main.png    # 鳥鶏研究団の写真
│   ├── futoppara-main.png      # ふとっぱらの写真
│   └── wagaya-main.png         # 我が家の写真
├── README.md              # このファイル
```

## 使用方法

1. index.htmlをブラウザで開く
2. プレゼンテーション用として使用

## 技術仕様

- **HTML5**: セマンティックなマークアップ
- **CSS3**: 
  - Flexbox・Grid レイアウト
  - CSS Variables（カスタムプロパティ）
  - CSS Animations・Transitions
  - Responsive Design
- **JavaScript（ES6+）**: 
  - Intersection Observer API
  - Event Listeners
  - DOM Manipulation
- **外部ライブラリ**: 
  - Lucide Icons（アイコン）
  - Inter Font（Google Fonts）

## アニメーション

- **背景グラデーション**: 15秒で色が動的に変化
- **カードホバー**: translateY + scale変換
- **フェードイン**: Intersection Observerによる段階的表示
- **アイコンエフェクト**: ホバー時の光沢効果

## レスポンシブ対応

### ブレークポイント
- **768px以下**: タブレット・スマートフォン対応
- **480px以下**: 小さなスマートフォン対応

### 対応内容
- グリッドレイアウトの調整
- フォントサイズの最適化
- 画像サイズの調整
- カード配置の変更

## 互換性

- **Chrome 88+**: 完全対応
- **Firefox 103+**: 完全対応
- **Safari 16+**: 完全対応
- **Edge 88+**: 完全対応

## パフォーマンス

- **最適化された画像**: PNG・WEBP形式
- **効率的なCSS**: CSS Variablesによる一元管理
- **軽量JavaScript**: 必要最小限の機能
- **CDN使用**: 外部リソースの高速読み込み

## 開発・デザインコンセプト

福岡の温かさと親しみやすさを**薄い青のモノトーンデザイン**で表現。Apple風のカードデザインシステムを採用し、情報の視認性と美しさを両立。ユーザーが快適に情報を読み取れるよう、コントラストと余白にこだわったミニマルデザインです。

---

**Created with**: HTML5, CSS3, JavaScript  
**Design System**: Warm Modern Card Design  
**Color Theme**: Light Blue Monotone