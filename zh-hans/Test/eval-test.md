# 可执行代码的页面

## 执行JavaScript
```eval-js
function hello(arg) {
    return `hello ${arg}`
}
hello('world')
```

## 执行Python2
```eval-python
def hello(arg):
    return 'hello %s'%arg
print hello('world')
```

## 执行Ruby
```eval-ruby
def hello arg
    "hello #{arg}"
end
hello 'world'
```

## 执行PHP
```eval-php
function hello($arg) {
    return "hello $arg";
}
echo hello('world');
```