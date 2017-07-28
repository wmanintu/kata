# Reverse String

Write a function that takes a string as input and returns the string reversed.

```
Example:
Given s = "hello", return "olleh".
```

```js
import test from 'ava'
import reverseString from './reverseString'

test('reverseString', function (t) {
  t.is(reverseString(''), '')
  t.is(reverseString('a'), 'a')
  t.is(reverseString('hello'), 'olleh')
})
```
