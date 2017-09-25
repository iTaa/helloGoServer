# 基于最新版的alpine
FROM alpine

# 设置工作目录
RUN mkdir -p /root/app
WORKDIR /root/app

# 生成默认start文件
RUN echo "echo \"please load you start script on /root/app/start.sh \n \
content example: \n \
python manager.py\"" > /root/app/start.sh

# 设置启动容器时启动的命令
CMD ["sh", "/root/app/start.sh"]