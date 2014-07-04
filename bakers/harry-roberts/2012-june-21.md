

Always be explicit in your code. Don’t use `margin:0` if you really mean `margin-bottom:0`. Every time
you use shorthand you need to check that it’s not inadvertently setting (or unsetting) another value at
the same time.