# JavaScript コーティング規約


## 変数宣言

let の使用（varは避ける）
```javascript
let hoge = "moge";
```

## 命名規則

- 変数
```javascript
// キャメルケースを利用(変数型を示唆する接頭語とかはつけず、変数名から推測できるようにする。もしくは今後はTypeScriptへ移行)
let variableSomething
```

- 関数
```javascript
// キャメルケースを利用
const functionSomething = (par1, par2) => {
    xxx
}
```

- クラス名
```javascript
// アッパーキャメルケースを利用
class ClassSomething {
    xxx
}
```

- 定数
```javascript
// 大文字＋スネークケースを利用（関数は別）
const SOMETHING_VALUE = "v1.2.3.0";
```

## 関数宣言
ES6以降で記載していることを意識するために、アロー関数形式で記載する。


## インデント
スペース4つとする（Tabは環境により表示が変わってしまうためNG）

  
  

***

## 参考

- [Google JavaScript Style Guide 和訳](https://cou929.nu/data/google_javascript_style_guide/)
