# SwiftUI-Notes
All the notes that I create to understand all the happenings in SwiftUI

# Structs

Structures are general purpose constructs that form a key building block of your programs. `structs` in Swift are first class citizens - meaning they can contain functions, data, and pretty much anything else.

The main difference in Swift with `structs` and `classes` is to think of `structs` as value only objects. Meaning they are passed by value, have no identity, and should be treated more as value only objects. Which Swift encourages. Don't create a class unless your really need it. Instead work with `enums` and `structs`.

```swift
struct Resolution {
    var width = 0
    var height = 0
}
```
