#Function

##return value
ommit return value type when it's void.

##argument
set external parameter name to the first argument if needed
```swift
func dateFromString(dateString: String) -> NSDate
dateFromString("2014-03-14")
func convertPointAt(#column: Int, #row: Int) -> CGPoint
convertPointAt(column: 42, row: 13)
```

use default value
```swift
func stringFromDate(date NSDate = NSDate()) -> String
let text = stringFromDate()
```

write _ if the first arugment doesn't need external parameter name and you set default value
```swift
func log(_ message: String = "default message")
log("this is message")
log()
```
