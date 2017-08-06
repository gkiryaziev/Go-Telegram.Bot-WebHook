## [Telegram](https://telegram.org/) Bot ([Golang](https://golang.org/) / [Ngrok](https://ngrok.com/) / WebHook)

### Info
```
This is Telegram Bot, written in Go language with WebHook.
The answer comes to the local server through the Ngrok service.
It's a shit-code, but it works, I was just too lazy to make it beautiful ;D.
```

### Usage
```
- create bot and get token
- set token and local port in main.go file
- build and run server
- run ngrok and get https url
- set webhook with token and url sending GET request in favorite browser
- enjoy
```

### WebHook Link
```
https://api.telegram.org/botYOURTOKEN/setWebhook?url=https://f2368743.ngrok.io/api/v1/update
```

### Ngrok screenshot
![Alt text](/screenshot.png?raw=true "screenshot")
