# Lecture 1 JavaScript Notes

I learned that JavaScript has some surprising behavior with numbers and types. For example, `typeof null` returns `"object"`, and decimal math can produce results that look unexpected.

```javascript
0.1 + 0.2
typeof null
[] == false
`2+3 =${2+3}`
```

```
0.30000000000000004
'object'
true
'2+3 =5'
```

Some things I noticed:

- JavaScript can compare different types in surprising ways.
- The value `null` is special, even though `typeof null` gives `"object"`.
- Template literals can include expressions using `${}`.