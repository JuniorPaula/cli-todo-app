# A simple CLI TODO app in GOLang 

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)

My first App in Golang 😃
This is a simple **CLI** **TODO** App, to save yours tasks. 

### how can i add a new task ?
~~~go
go run ./cmd/todo/main.go -add yours task
~~~

### how can i list all tasks ?
~~~go
go run ./cmd/todo/main.go -list
~~~

### how can i marke a task as completed ?
~~~go
go run ./cmd/todo/main.go -complete=taskId
~~~

### about the Build ?
~~~go
go build ./cmd/todo
~~~