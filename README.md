From this course: https://egghead.io/lessons/react-a-beginners-guide-to-react-introduction

used

```
rename -n 's/(\d{2,})/sprintf("%02d", $1 + 1)/e' *
```

to rename files by incrementing a number in the file. ` -n``` argument is for a dry run.  `"%02d"`in the`sprintf` command does padding to ensure numbers have a leading zero if the number of digits is less than 2.
