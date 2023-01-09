# ForceUnwrapping



**Force unwrap:**
```
let stringPi = "3.14"
let doublePi = Double(stringPi)!



func emptyArray(_ optionalInt: [Int]?) {
    let unwrapped = optionalInt!
    print("The length is \(unwrapped.count) ")
}
emptyArray([])
```

**Force unwrap property of struct:**
```
struct ForceUnwrapStruct {
    var optionalProperty1: String?
    var optionalProperty2: String?
}

let constantStruct = ForceUnwrapStruct(optionalProperty1: "Ahmet", optionalProperty2: "Alex")
print(constantStruct)
print(constantStruct.optionalProperty1!)
```
