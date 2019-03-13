# Compose file for Gitlab Community Edition

買 QNAP 不用內建 Container Station 來建置系統會覺得很可惜
剛開始架設站台第一直覺使用 Virtualization Station 架設 CentOS 然後再安裝 GitLab
但發現站台在 VM上運作很吃 QNAP 的資源
甚至會影響原本 QNAP APP 運作速度
因此就轉向使用 Container Station 內建「gitlab-ce」
但使用內建安裝後需自行調整 SMTP, Docker Hostname
稍微麻煩
因此, 身為一位工程師
懶還要更懶
全部在Docker-Compose設定完就可以運作

## Quickstart

```bash
git clone https://github.com/aihuastyle/docker-compose-gitlab-ce.git
docker-compose up -d
```

Enjoy!
