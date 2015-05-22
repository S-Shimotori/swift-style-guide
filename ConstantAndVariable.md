#Constant and Variable

##definition
You can define a few constants or variable connected with each other in the same line.

###global scope
Don't use global variable.  
Give name beginning k as prefix to global scope constant.  
You can define constant with expression.  
```swift
let kGoogleAnalyticsTrackingID = NSBundle.mainBundle().objectForInfoDictionaryKey("GoogleAnalyticsTrackingID") as? String
```

###Let bindings
> Prefer `let`-bindings over `var`-bindings wherever possible

'The Art of Readable Code' chapter 9 explains why you should use constant.

###Collection
Follow Apple Official Documents  
[The Swift Programming Language: Collection Types](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/CollectionTypes.html)
```swift
var elements = [Int]()
var namesOfIntegers = [Int: String]()
```

###Type
####String
Use not NSString but String. Convert String into NSString when you use as NSString.

####When specifying a type, always associate the colon with the identifier
> When specifying the type of an identifier, always put the colon immediately after the identifier, followed by a space and then the type name.  
> Also, when specifying the type of a dictionary, always put the colon immediately after the key type, followed by a space and then the value type.

####specify when constant and variable's type is ambiguous
* Int, UInt
* CGFloat, Float, Double
