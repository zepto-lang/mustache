# template

A minimal templating engine in and for zepto.
It is still under construction.

# Usage

There is a single endpoint at the moment, called `template`:
```clojure
(load "template.zp")
(define template (import "template:template"))
(template "i am {{who}} and this is {{what}}" (make-hash ["who" "fred"] ["what" "awesome"]))
```

<hr/>
Have fun!
