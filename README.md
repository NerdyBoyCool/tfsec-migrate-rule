# tfsec-migrate-rule
tfsecのignore形式が変更になったので golang scriptで ignore 形式を変換するスクリプト

```
$ go build main.go
$ cp ./main ~/sample-terraform-project # mv main binary to terraform project
$ ./main
```
