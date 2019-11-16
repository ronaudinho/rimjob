![wtfpl](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png)
:trollface:
`Review Ini Mas/Mbak` pr review job assigner or rimjob in short

##### how do i use this?
assuming your go env is set
```
go get github.com/ronaudinho/rimjob
go build
export GITHUB_TOKEN=your_github_token
export REVIEWER_POOL=github_login_of_everyone_you_want_to_ask_for_review
./rimjob [link to pr]
```
if REVIEWER_POOL is not set, will simply request for review from anyone eligible

##### why you no do `asd`/`etc`/`whatever`?
this meme driven development to solve my own problem so YAGNI ftw. i assume no one would ever stumble upon this anw.
