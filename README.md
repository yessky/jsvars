jsvars
======
A Light and Fast JavaScript Varaible Scanner

## Description

used for scanning variables of given javascript source code.

jsvars implements a simple & fast parser which based on lexical-like analysis.

## Usage

```html
<script src="src/jsvars.js"></script>
<script>
	var vars = jsvars('var abc = 123, bcd = 456;');
	// return {abc: 1, bcd: 1}
</script>
```

## Download

[download](https://github.com/yessky/jsvars/blob/master/src/jsvars.js)