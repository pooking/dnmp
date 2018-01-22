FROM node:6.10.1

# 定义工作目录
# Create app directory
RUN mkdir -p /www
WORKDIR /www
# 安装npm
RUN npm install
# RUN npm rebuild images --force
# RUN npm rebuild node-sass
# 开放端口
EXPOSE 8000
CMD [ "npm", "start" ]
