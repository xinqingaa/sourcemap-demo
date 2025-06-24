```json
{
  "version": 3,
  "file": "AboutView-CxPSxYyM.js",
  "sources": ["../../src/views/AboutView.vue"],
  "sourcesContent": [
    "<template>\n  <div class=\"about\">\n    <h1>This is an about page</h1>\n  </div>\n</template>\n\n<style>\n@media (min-width: 1024px) {\n  .about {\n    min-height: 100vh;\n    display: flex;\n    align-items: center;\n  }\n}\n</style>\n"
  ],
  "names": ["_hoisted_1", "_openBlock", "_createElementBlock", "_cache", "_createElementVNode"],
  "mappings": "wEACOA,EAAA,CAAA,MAAM,OAAO,kBAAlB,OAAAC,EAAA,EAAAC,EAEM,MAFNF,EAEMG,EAAA,CAAA,IAAAA,EAAA,CAAA,EAAA,CADJC,EAA8B,UAA1B,wBAAqB,EAAA"
}
```

- `version`: `SourceMap` 标准版本
- `file`: 转换后的文件名
- `sourceRoot` 转换前文件所在目录，若为空说明与转换前在同一目录
- **`sources`**: 转换器按文件，是一个数组，可能存在多个文件合并
- **`sourcesContent`**: 真正的源代码
- `names`: 转换前所有的变量名和属性名
- `mappings`: 所有映射点
