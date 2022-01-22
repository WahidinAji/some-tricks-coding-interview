# some-tricks-coding-interview
some tricks of coding interview basic logic

Write in with 🤍 and [Golang](https://go.dev/)
## LIST
* [Math Factorial](https://github.com/WahidinAji/math-factorial)
* [Data Structure of Set](https://github.com/WahidinAji/struktur-data-set)
* [Web Scraping](https://github.com/WahidinAji/CrawlLink_example) <-- not yet ready
* [FizzBuzz and Palindrom](https://github.com/WahidinAji/fizz-buzz-and-palindrom-with-golang)


### Codewars
* [Sam](https://www.hackerrank.com/challenges/grading/problem)

```go
func gradingStudents(grades []int32) []int32 {
    var result []int32
    for i := 0; i < len(grades); i++ {
        if grades[i] >= 38 {
            var mod = grades[i] % 5
            if mod >= 3 {
                grades[i] += 5 - mod
            }
        }
        result = append(result, grades[i])
    }
    return result
}
```
