# Docker Compose 模板收藏庫

[English](README.md) | [繁體中文](README.hant.md)

---

歡迎來到我的 Docker Compose 模板收藏庫！🎉 這裡存放著我用來快速啟動各種服務的實用腳本。無論是簡單的開發環境還是更複雜的部署需求，這些模板都能滿足你的需求。把它當成你的工具箱，隨時取用並立即啟動！🚀

## Docker 指南

開始使用這些模板之前，請先確保已安裝 Docker。你可以參考 [Docker 官方網站](https://docs.docker.com/get-docker/) 來完成安裝。Docker Compose 是一個強大的工具，可以幫助你輕鬆管理本地的多個容器。

當你準備就緒後，只需在包含 `docker-compose.yml` 的資料夾中執行以下指令：

```bash
docker-compose up -d
```

當你完成使用後，可以通過以下指令停止所有容器：

```bash
docker-compose down
```

就是這麼簡單！🚀

## 目錄結構

- `docker-compose.yml`: 預設的模板，幫助你快速啟動服務。
- 子目錄: 特定服務或環境的專用設置。

## 使用方法

1. 克隆這個倉庫：

   ```bash
   git clone https://github.com/yshengliao/docker-compose-templates.git
   ```

2. 進入你需要的模板目錄：

   ```bash
   cd docker-compose-templates/<template-directory>
   ```

3. 啟動服務：

   ```bash
   docker-compose up -d
   ```

## Docker Compose 版本注意事項

自新版 Docker Compose 開始，`docker-compose.yml` 中的 `version` 屬性已經不再需要。為了確保相容性並避免混淆，我已經在所有模板中移除了該欄位。

## 授權條款

此作品根據 CC0 1.0 Universal (CC0 1.0) 公共領域貢獻授權釋出。您可以自由複製、修改、散佈這些模板，甚至用於商業用途，無需取得任何許可。

如需詳細資訊，請參閱 [LICENSE](./LICENSE) 文件，或查看完整的法律條文 <https://creativecommons.org/publicdomain/zero/1.0/legalcode>。

## 免責聲明

這些模板是作者用於個人開發的配置。請自行評估是否適合你的需求，尤其是在生產環境中。作者不對這些配置的功能、安全性或穩定性提供任何保證。
