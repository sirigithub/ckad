* Every jq query results in an array output [].
* $ represets the root element.
* To specify criteria use $[?()]
* The ? is used for specifiying criteria.
* @ symbol in the criteria means each item in the list
e.g $[?(@ > 40 )] each item in the list.
* Navigate lists, to access an element in the list use $[index]
* To get element 1 and 4 use $[0,4]
* To get elements from 1 to 4 use $[1:4]
 