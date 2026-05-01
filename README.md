# snowflake
Snowflake-style 64-bit IDs for Go.

## Status

Pre-release. API may change. Built as a foundational library for a larger self-hosted chat project.

## Install

```
go get github.com/michael-duval/snowflake
```

## Usage

```go
gen, _ := snowflake.New(0)
id, _ := gen.Next()
fmt.Println(id)        // 7385920183762944000
fmt.Println(id.Time()) // 2026-05-01 14:23:01.234 +0000 UTC
```

## License

MIT