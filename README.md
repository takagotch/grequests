### grequests
---
https://github.com/levigross/grequests

```go
response := Get("http://some-wonderful-file.txt", nil)

if err := response.DownloadToFile("randomFile"); err != nil {
  log.Println("Unable to download file: ", err)
}

response.Bytes() == nil
response.String() == ""


response := Get("http://some-wonderful-file.txt", nil)

response.Bytes() == `file-bytes`
response.String() == "file-string"

if err := resp.DownloadToFile("randomFile"); err != nil {
  log.Println("Unable to download file:", err)
}

response.ClearInternalBuffer()

response.Bytes() == nil
response.String() == ""
```

```
```

```
```


