# scoop-aiproxy

[Scoop](https://scoop.sh) bucket for [aiproxy](https://github.com/aleksanderbernacki12-byte/aiproxy) — a local reverse proxy that blocks leaked secrets and rate-limits LLM API calls.

## Installing

```powershell
scoop bucket add aiproxy https://github.com/aleksanderbernacki12-byte/scoop-aiproxy
scoop install aiproxy
```

The manifest in this bucket is updated automatically by aiproxy's own release pipeline on every tagged release — it is never edited by hand.
