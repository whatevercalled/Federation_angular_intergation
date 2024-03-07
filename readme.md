federation.config.js 所有的expose檔案都必須有過import 如果沒有Import 無法將其expose出去

使用federation進行合併專案，必須確保angular的專案版本號都一致。

作法：將package.json.lock刪除 node module 刪除 並且重新安裝node module 
