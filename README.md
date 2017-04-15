# qframe-handler
Template to start new qframe handler

## HelloWorld

To get things going, please use this examplary handler.

```bash
$ go run main.go
2017/04/15 11:01:40 [II] Dispatch broadcast for Data and Tick
2017/04/15 11:01:40 [II] Start log handler testv0.0.0
2017/04/15 11:01:42 Send message
2017-04-15T11:01:42.19815 INFO    sType:test   sName:[1]test       1
```

The main function starts the handler and submits a test-message from a fictonary input `test`.<br>
The handler is configured with `handler.test.inputs: test`, so it reacts and outputs the msg to stdout.
