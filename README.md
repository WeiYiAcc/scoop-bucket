# scoop-bucket

WeiYiAcc 的私人 [Scoop](https://scoop.sh) bucket。收录官方 bucket 没有的工具。

## 使用

```powershell
scoop bucket add weiyiacc https://github.com/WeiYiAcc/scoop-bucket
scoop install weiyiacc/multica
```

## 收录

| App | 说明 |
|---|---|
| [multica](bucket/multica.json) | Multica CLI — multi-agent AI coding assistant |

## 自动更新

Excavator GitHub Action 每 4 小时跑一次 `checkver -u`，按 manifest 的
`checkver`/`autoupdate` 规则自动提交新版本。
