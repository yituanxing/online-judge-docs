# 部署

## 部署流程
1. **后端**:
    - 打包微服务为 Docker 镜像。
    - 使用 Docker Compose 部署（MySQL + Nacos + RabbitMQ + 微服务）。
    - 配置 Nginx 负载均衡。
2. **前端**:
    - 使用 Vite 构建 Vue3 项目。
    - 部署到 Nginx 静态资源目录。
3. **基础设施**:
    - 配置 ELK 日志系统。
    - 配置 XXL-JOB 定时任务。
    - 配置阿里云 ECS 环境。
4. **文档**:
    - 使用 MkDocs 部署到 GitHub Pages。

## 部署环境
- **开发**: Windows 10
- **生产**: 阿里云 ECS (Linux)

## 访问
- 系统: [https://example.com](https://example.com)
- 文档: [https://your-github-username.github.io/online-judge-docs/](https://your-github-username.github.io/online-judge-docs/)