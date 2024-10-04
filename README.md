# Docker Compose Templates

Welcome to my Docker Compose template stash! 🎉 Here are the scripts I use to fire up my favorite services. Whether it’s a quick dev setup or something more complex, I’ve got you covered. It’s like a neat toolbox—grab what you need and go. 🚀

歡迎來到我的 Docker Compose 模板收藏庫！🎉 這裡放滿了我常用來啟動各種服務的實用腳本。無論是簡單的開發環境，還是更複雜的架構，這裡都能幫助你迅速上手。把它當作一個整理好的工具箱，隨取隨用！🚀

## Docker Guide

To use these Docker Compose templates, install Docker. See the [Docker website](https://docs.docker.com/get-docker/) for instructions. Docker Compose helps you easily manage and automate multiple containers locally.

要使用這些 Docker Compose 模板，首先需要安裝 Docker，請參考 [Docker 官網](https://docs.docker.com/get-docker/) 的安裝說明。Docker Compose 是個非常方便的工具，可以幫助你輕鬆管理和自動化本機的多個容器。

Simply run the following command in the directory containing the `docker-compose.yml`:

只要在有 `docker-compose.yml` 的目錄中執行以下指令，就能開始使用：

```bash
docker-compose up -d
```

When you're done developing, stop all containers with:

當你開發完成後，可以使用以下指令來停止所有容器：

```bash
docker-compose down
```

It's that simple! 🚀 就是這麼簡單！🚀

## Directory Structure

- `docker-compose.yml`: The default template to get you up and running quickly.  
  預設的模板，讓你可以快速開始使用。
- Subdirectories: For more specific needs—think environment-based setups or service-specific settings.  
  子目錄則是針對不同環境或服務的特定設定。

## Usage

1. Clone this repository:  
   克隆這個倉庫：

   ```bash
   git clone https://github.com/yourusername/docker-compose-templates.git
   ```

2. Navigate to the desired template:  
   進入你想要使用的模板目錄：

   ```bash
   cd docker-compose-templates/<template-directory>
   ```

3. Start the services:  
   啟動服務：

   ```bash
   docker-compose up -d
   ```

## Note on Docker Compose Version

Starting from newer versions of Docker Compose, the `version` attribute in `docker-compose.yml` has been deprecated and is no longer required. In this repository, we have removed the `version` field from all templates to avoid confusion and ensure compatibility with the latest Compose versions.

自新版 Docker Compose 開始，`docker-compose.yml` 中的 `version` 屬性已經被廢棄，不再需要指定。在此倉庫中，我們已移除所有模板中的 `version` 欄位，以避免混淆並確保與最新版本相容。

## Templates

What kind of magic do we have in here? Well, a bit of everything:

這裡有什麼神奇的模板呢？應有盡有：

- **awsdynamodb**: For quickly setting up an AWS DynamoDB local instance.  
  快速設置 AWS DynamoDB 本地實例。
- **jaeger**: A template to run Jaeger for distributed tracing.  
  適用於分佈式追蹤的 Jaeger 模板。
- **mysql**: Set up a MySQL database in a snap.  
  快速設置 MySQL 資料庫。
- **nsq**: Easily deploy an NSQ messaging system.  
  輕鬆部署 NSQ 訊息系統。
- **postgres**: Launch a PostgreSQL database.  
  啟動 PostgreSQL 資料庫。
- **redis**: For those Redis caching needs.  
  為你的 Redis 緩存需求設計。

## License

This work is dedicated to the public domain under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication. You can copy, modify, and distribute it freely, even for commercial purposes, without asking permission.

For more details, see the [LICENSE](./LICENSE) file or visit the full legal text at <https://creativecommons.org/publicdomain/zero/1.0/legalcode>.

## Disclaimer

These configurations are used by the author for personal development purposes. Please assess their suitability for your own use case, especially in production environments. The author does not provide any warranty or guarantee regarding the functionality, security, or stability of these settings.

這些設定是作者用於個人開發用途。請自行評估是否適合你的使用場景，尤其是生產環境。作者不對這些設定的功能、安全性或穩定性提供任何保證或擔保。
