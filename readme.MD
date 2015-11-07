将CGPoint, CGSize, CGRect三种类型添加运算符重载. 

例子:

```swift
var point = CGPoint(x: 20, y: 20)
point += (5, 5)
print(point) //(25.0, 25.0)
        
        
var rect = CGRect(x: 20, y: 20, width: 100, height:100)
rect += (0, 0, 100, 100)
print(rect) //(20.0, 20.0, 200.0, 200.0)
```
