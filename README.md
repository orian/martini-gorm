# martini-gorm
Example martini/gorm application

The tutorial which links to the original code is located at:
https://www.dougcodes.com/go-lang/building-a-web-application-with-martini-and-gorm-part-1

# Run
One must install dependencies:
```shell
go get github.com/jinzhu/gorm
go get github.com/mattn/go-sqlite3
go get github.com/martini-contrib/render
```

Run
```bash
go run server.go
```

**A note** from @orian: I know `gorm` and `martini` from a high level perspective only.
What surprised me is a build time around 22s.
