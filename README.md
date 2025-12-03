# LibreTranslate Docker 镜像镜像

这是一个自动同步 LibreTranslate 官方镜像到个人 Docker Hub 仓库的 GitHub Actions 配置。

## 功能
- 自动同步 `libretranslate/libretranslate:latest` 到个人仓库
- 支持手动触发同步
- 每周日凌晨 2 点自动同步

## 使用方法

### 拉取镜像
```bash
docker pull hanmenger/libretranslate:latest
