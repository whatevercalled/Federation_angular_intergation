In tsconfig.app.json change your include array from
```
"include": [
    "src/**/*.d.ts"
  ]
To
```
```
"include": [
    "src/**/*.d.ts",
    "src/**/**/*.d.ts"
  ]
```
避免federation.config.js無法編譯component的錯誤

