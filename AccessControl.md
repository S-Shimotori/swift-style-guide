#Access Control

##Always specify access control explicitly for top-level definitions

##definitions within top-level ones
> However, definitions within those can leave access control implicit, where appropriate

Don't forget to set access control to variables from interface builder
```swift
@IBOutlet private weak var label: UILabel!
```
