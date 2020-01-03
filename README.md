# jdk8-ffmpeg

jdk -version: 8

ffmpeg -version: 4.1

本镜像根据https://hub.docker.com/r/elderbyte/docker-alpine-jdk8-ffmpeg/dockerfile 创建，在此表示感谢

原镜像中ffmpeg版本为3.4，ffmpeg -stream_loop 添加循环的bgm时生成的视频长度为音频长度，无法循环

现将ffmpeg升级为4.1，解决了该问题

