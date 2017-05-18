# psswiftiosuiunittest


## 3. UI Testing
### 3 Providing Access on Hard to Reach Elements
Open Developer Tool->Accessibility Inspector


#### 03:30
create User Defined Runtime Attributes
```
Key Path: accessibilityLabel
Type: String
Value: mainTable
```

#### 04:06
build for testing
```
let app = XCUIApplication()
let table = app.tables["mainTable"]
```

### 4 Working with XCTAssert
#### 06:14
```
let table = app.tables["mainTable"]
XCTAssertEqual(table.cells.count,5)
```
