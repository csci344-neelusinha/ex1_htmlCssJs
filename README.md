# 1st html project - This is top header
##  This is 2nd level sub header
### This is 3rd level sub header

Next word is using *italics*

Next word is using _italics_ too

Next word is using **bold**

Next word is using __bold__ too

Next word is using ~~strikeThrough~~

Next word is `rendered`

## Lists
### Un-ordered Lists
### Un-ordered List using *
* unOrdered List 1, item1
* unOrdered List 1, item2

### Un-ordered List using -
- unOrdered List 2, item1
- unOrdered List 2, item2


### Un-ordered List using +
+ unOrdered List 3, item1
+ unOrdered List 3, item2

### Ordered Lists (just put any number at front of ordered list items, only number in front of 1st item matters)
3. Ordered List 1, item1

1. Ordered List 1, item2

## Links
[inline style link](https://www.google.com)

[inline style link with title, hover over me](https://www.google.com "Link to google")

[reference style link][reference1]

[reference style link using reference number][2]

[reference style link using link text itself][]

[reference1]: https://www.google.com
[2]: https://wwww.yahoo.com
[reference style link using link text itself]: https://www.baidu.com

## Code and Syntax highlighting 
```javascript
var str1 = "JavaScript string 1";
var str2 = 'JavaScript string 2';
// JS function expression
var func1 = function(inp1) {
    console.log(inp1);
};
// JS function declaration
function func2(inp1) {
    console.log(inp1);
}
// you need () after function to execute it, otherwise it returns the function
console.log(func1);
// 
func1('input1');
func2('input2');
```

```java
public class MyClass {
    private String attr1;
    public MyClass(String _attr1) {
        attr1 = _attr1;
    }
}
```
## Tables
| Column Header 1                      | Column Header 2 | Column Header 3 |
| ------------------------------------ |:---------------:| ---------------:|
|    row 1, col 1                      |  row 1, col 2   | row 1, col 3    |
|    By default Cells are Left Aligned |  centered       | `right aligned` |
| By default rows are Zebra striped    |  *italic*       | **bold**        |


ColumnHdr 1 | ColumnHdr2 | ColumnHdr3
-- | -- | --
raw MD table do not need to be pretty lined up | two | three
1st and Last pipe are optional | dos | tres

## Using HTML tags in MarkDown
<ul style="list-style-type:square;">
    <li>Line Item 1</li>
    <li>of Unordered List, ul, element of HTML</li>
<ul>

