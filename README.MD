# HTTP status checker

## Description

Check the current status of website.
Able to detect if website is downed due to http request returns 404.

**_DEMO:_**

<img src="./checker.jpg" width="80%">

## Usage

open main.go and add URL for status checking website in `links` slice.

```
func main() {
	// add URL for checking website in bellow.
	links := []string{
		"http://google.com",
		"http://!404!facebook.com",
		"http://stackoverflow.com",
		"http://golang.org",
		"http://amazon.com",
	}
```

then run: `$ run main.go`

## Requirement

- Golang

## Licence

[MIT](./LICENSE.txt)

## Author

[Shoe Kure](https://github.com/roy1210)