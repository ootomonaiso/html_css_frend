# html_css_frend

## アブソリュートとかの話

## positionプロパティ

### static

- デフォルト値
- 上の要素の流れに沿って配置
- top,right,bottom,leftは効かない
  
### relative (相対)

- 元々の位置を基準に配置される
- top,right,bottom,leftで基準の位置からの移動を指定
- 要素だけ移動

### absolute (絶対)
- 最も近い親要素でpostionの値がstatic以外の値だったら
- 基準がなければbodyが参照されるんだって(Google調べ)
- top,right,bottom,leftで基準の位置指定できる
- 元のレイアウトとは独立して配置する