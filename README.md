# Collect Javascript yearly update

## 2016

- [Array.prototype.includes](https://github.com/tc39/proposal-Array.prototype.includes)
- [Exponentiation operator](https://github.com/tc39/proposal-exponentiation-operator)

## 2017

- [Object.values/Object.entries](https://github.com/tc39/proposal-object-values-entries)
- [String.prototype.padStart / String.prototype.padEnd](https://github.com/tc39/proposal-string-pad-start-end)

```javascript
"foo".padEnd(4, "12"); //foo12
"foo".padEnd(8, "12"); //foo12121
```

- [Object.getOwnPropertyDescriptors](https://github.com/tc39/proposal-object-getownpropertydescriptors)

```javascript
  const user = {"name":"jack", age: "18"};
  Object.getOwnPropertyDescriptors(user);
  /**
  {
    "name": {
      "value": "jack",
      "writable": true,
      "enumerable": true,
      "configurable": true
    },
    "age": {
      "value": "18",
      "writable": true,
      "enumerable": true,
      "configurable": true
    }
  }
  /**
```

- [Trailing commas in function parameter lists and calls](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Trailing_commas)

### Parameter definitions

```text
function f(p) {}
function f(p,) {}

(p) => {};
(p,) => {};
```

### Function calls

```text
f(p);
f(p,);

Math.max(10, 20);
Math.max(10, 20,);
```

- [Async Functions](https://github.com/tc39/proposal-async-await)

- [Shared memory and atomics](https://github.com/tc39/ecmascript_sharedmem)

## 2018 (going)

- Lifting template literal restriction
- s (dotAll) flag for regular expressions
- RegExp named capture groups
- Rest/Spread Properties
- RegExp Lookbehind Assertions
- RegExp Unicode Property Escapes
- Promise.prototype.finally
- Asynchronous Iteration

## 2019 (going)

- Optional catch binding
- JSON superset
- Array.Flat()
- Array.flatMap()
- Object.fromEntries()
- String.trimStart() & String.trimEnd()
- Optional Catch Binding
- Function.toString()
- Symbol.description

## 2020 (going)

- Dynamic import
- Nullish Coalescing
- Promise.allSettled
- globalThis

## 2021 (going)

- String.prototype.replaceAll
- Promise.any()
- WeakRefs
- [Logical assignment operators](https://exploringjs.com/impatient-js/ch_operators.html#logical-assignment-operators)
