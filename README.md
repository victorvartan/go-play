# go-play: playing around with GO!

For running on AWS Lambda:
```
go get -u github.com/aws/aws-lambda-go/lambda

go get -u github.com/aws/aws-lambda-go/events
```

For building the zip file to be deployed to AWS Lambda:
```
GOOS=linux go build main.go
zip function.zip main
```

These commands worked on Cloud9! How cool is that?!
