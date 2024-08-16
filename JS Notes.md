# JavaScript Note

## Primitive Data Type
- Number: all numbers in js are floating points
- String
- Boolean
- Undefined (let child;) 
- Null: empty value
- Symbol: Unique values that cannot be changed
- BigInt: Larger integers than the Number can hold

**Dynamic Typing**: We don't manually define the data type of the value stored in a variable. The type is determined automatically.

Using **typeof** to show the type of a variable
```
console.log(typeof hello);
```

**mutable and immutable variables**
```
let age = 30;
const birthday = 2000;

// const can't use like: const job; You must assign a value to it.

// var is similar to let BUT
// var: Function-scope
// let: Block-scope 
var age = 30;
```

const: 不可修改的变量
var：在function内部
let：在block内部
空头：在gloabl范围的variable 

Type的转换
Number(String) 和python差不多

```
console.log(Boolean(0));			// false
console.log(Boolean(undefined));	// false
console.log(Boolean("Jonas"));		// true
console.log(Boolean({}));			// true
console.log(Boolean(''));			// false

```

'18' == 18 		// true (loose)
'18' === 18		// false (strict)













     