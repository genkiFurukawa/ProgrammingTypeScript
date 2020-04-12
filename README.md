# めも

1.プログラムがAbstractSyntaxTree(抽象構文木)
2.ASTがバイトコードにコンパイルされる
3.バイトコードがランタイムによって評価される

* TypeScriptCompiler(TSC)はJavaScriptコードを実行する前に型チェックを行う

* 明示的に型をTypeScriptに伝えるにはアノテーションを使う

```typescript
let a: number = 1;
let c: boolean[] = [true, false]
```

* TypeScriptは漸進的型付き言語(gradually typed language)