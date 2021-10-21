# go-record

---
## 事先準備
- 下載專案
- 安裝 Portaudio
- 安裝 gordonklaus/portaudio

### 下載專案
```
git clone 
```

### 安裝 Portaudio
```
brew install portaudio
```

### 安裝 gordonklaus/portaudio
```
go get github.com/gordonklaus/portaudio
```
---
## 執行專案
- Run 
- Stop

### Run
```go
go run main.go <fileName>
```

### Stop
```
ctrl + c
```

---
產生出的audio data是raw data
如果想轉成其他格式的話
可以使用Audacity去做編輯

## 參考資料

https://gist.github.com/suapapa/d598d99360497252433af430902bb49e
https://github.com/gordonklaus/portaudio