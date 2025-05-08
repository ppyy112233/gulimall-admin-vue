# gulimall-admin-vue
谷粒商城后台管理系统前端vue项目——————>中文版 README.zh.md。
至少每人 2 次提交（含有效 commit message，且每次均具有有效工作量，有效工作量是指贡献的Changes数量不能少于10 lines）
使用文档（对 AI 辅助的工作进行简要的说明）AI 使用过程截图（每人不少于 3 张，展示你们如何提问、生成与比对），截图提交到img
<!-- by 黎  柚 -->
中文翻译版本 README.zh.md（可借助 AI，但需润色）
任务：中文翻译版本 README.zh.md——>含项目介绍


<!-- by 梁佐妃 -->
中文翻译版本 README.zh.md（可借助 AI，但需润色）
任务：中文翻译版本 README.zh.md——>安装/部署说明

安装
Node.js	验证命令(node -v)	Node.js 中文镜像站
npm	验证命令(npm -v)	npm config set registry https://registry.npmmirror.com
Git	git --version-
1. 克隆我自己的仓库
https://github.com/liangzuofei/gulimall-admin-vue.git
fork 潘燕艳的仓库
https://github.com/ppyy112233/gulimall-admin-vue.git
cd D:\英语
2. 安装项目依赖
npm install --registry=https://registry.npmmirror.com --legacy-peer-deps
3. 环境配置
新建 .env 文件并配置后端服务地址：
VUE_APP_API_BASE_URL=http://localhost:8081/api/remote
5. 本地开发运行启动后端服务
# 进入后端项目目录
cd gulimall-parent/gulimall-admin
# 启动 Spring Boot 应用
mvn spring-boot:run
启动前端服务
# 返回前端项目根目录
cd ../../../gulimall-admin-vue
# 开发模式运行
npm run dev  
访问地址：http://localhost:8080
6. Docker 部署
6.1 修改配置文件
编辑 docker-compose.yml：
将 gulimall-admin-vue 服务端口映射改为 8080:80
配置后端服务连接地址（VUE_APP_API_BASE_URL）
6.2 构建镜像并运行
# 构建前端镜像
docker build -t gulimall-admin-vue:latest ./gulimall-admin-vue
# 启动容器组
docker-compose up -d 
访问地址：http://localhost:8080
7. Linux 服务器部署（推荐）
7.1 构建前端项目   
# 生成生产环境静态文件
npm run build
7.2 配置 Nginx
将输出的 dist 目录部署到 Nginx，配置反向代理指向后端服务。

<!-- by 李金焕 -->
中文翻译版本 README.zh.md（可借助 AI，但需润色）
任务：中文翻译版本 README.zh.md——>带截图主要功能的使用教程


<!-- by 王  愉 -->
项目术语表（中英文对照，不少于 5 个关键词）

<!-- by 覃卫婷 -->
请使用AI对专业术语进行审核。审核——>中文版 README.zh.md,是否有错别字，如果有请重新提交
