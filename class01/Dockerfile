# 1. ビルドステージ
FROM golang:1.21 AS builder

# 作業ディレクトリを設定
WORKDIR /class01

# 必要なファイルをコピー
COPY . .

# バイナリをビルド（静的にリンク）
RUN go build -o main main.go

CMD [ "./main" ]
