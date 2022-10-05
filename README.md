# metabase for danran

DanRanのBI環境

## 構成
### 開発環境

- docker composer

### 本番環境

| id       | なんか                    |
|----------|--------------------------|
| 構成管理            | CDK / Docker   |
| Metabase本体        | Fagate         |
| Metabase情報の永続化 | RDS            |

## 起動方法
### 開発環境
```
docker compose up -d

open http://localhost:3001
```

## その他
### Docker関連
```
# 滅びの呪文（全部消す）
docker compose down --rmi all --volumes --remove-orphans
```