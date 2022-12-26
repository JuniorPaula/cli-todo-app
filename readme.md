# A simple CLI TODO app in GOLang 

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)

My first App in Golang 😃
This is a simple **CLI** **TODO** App, to save yours tasks. 

![Screenshot from 2022-12-23 17-52-23](https://user-images.githubusercontent.com/79703497/209541938-f161e8f4-11a8-46db-a2e3-24cc77e33488.png)

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
