# rime-jyutping-minimal

極簡粵語拼音輸入方案，基於 [rime-cantonese](https://github.com/rime/rime-cantonese) 詞庫。

適合人群：會說/想學粵語、想用粵拼打字、但不熟悉拼音規則的用戶。

## 特色

- 聲調可選：打 `gam` 或 `gam2` 都能出字，入門無壓力
- 模糊音支援：n/l 不分、ng/零聲母 不分
- 普通話反查：按 ` 鍵輸入普通話拼音，找到對應粵語詞和讀音
- 黑白極簡主題：clean 到極致的候選詞框

## 安裝方法

### Windows（小狼毫）

1. 下載並安裝 [小狼毫 Weasel](https://github.com/rime/weasel/releases)
2. 下載本倉庫 `rime/` 文件夾內的所有文件
3. 將文件複製到小狼毫用戶文件夾：
4. 右鍵點擊系統托盤的小狼毫圖標 → 重新部署
5. 切換到「粵語拼音」方案即可使用

### Android（Trime）

> 即將支援，敬請期待

## 使用說明

| 操作 | 說明 |
|------|------|
| 直接輸入拼音 | `gam`、`zou6me1` 均可 |
| 聲調輸入（可選） | 在音節後加數字：`gam2` = 咁 |
| 普通話反查 | 按 `` ` `` 鍵，輸入普通話拼音 |
| 切換繁簡 | `Ctrl + ~` 開啟選單 |
| 翻頁 | `=` 下一頁，`-` 上一頁 |

## 聲調對照表

| 聲調 | 數字 | 例字 |
|------|------|------|
| 陰平 | 1 | 詩 si1 |
| 陰上 | 2 | 史 si2 |
| 陰去 | 3 | 試 si3 |
| 陽平 | 4 | 時 si4 |
| 陽上 | 5 | 市 si5 |
| 陽去 | 6 | 事 si6 |

## 詞庫來源

詞庫數據來自 [rime-cantonese](https://github.com/rime/rime-cantonese)，
遵循 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 授權。

## License

Apache-2.0
