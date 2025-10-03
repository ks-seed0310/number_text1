function sleep(ms){ return new Promise(resolve=>setTimeout(resolve, ms)); }
⇈　スリープ　
await sleep(秒×1000)
async function

もし　sleep関数を使うなら
async function(){}とかく
使わないなら
function(){}とかく

もし関数を使うときには
await functionname()
で実行
