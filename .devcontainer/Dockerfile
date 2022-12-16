FROM ubuntu:latest
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y texlive-lang-japanese texlive-full
ENV TZ=Asia/Tokyo
ENV DEBIAN_FRONTEND=
RUN kanji-config-updmap-sys auto
