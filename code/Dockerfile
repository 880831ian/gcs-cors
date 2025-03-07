# 使用 Nginx 作為 Web 伺服器
FROM nginx:alpine

# 設定工作目錄
WORKDIR /usr/share/nginx/html

# 複製 HTML 檔案到容器內
COPY index.html /usr/share/nginx/html/index.html

# 啟動 Nginx
CMD ["nginx", "-g", "daemon off;"]