# git-inflate
Ethically

questionable

tips

for

maximizing

your

git

stats

## About
When you're productive and you really want to get that point across, you need to make sure you're pumping up your stats.
It's the only way your boss is going to understand how much you bring to the table.  Use this README to maximize your
numbers.  If you have a tip of your own, open a Pull Request!

As the project "matures," we may organize this document more robustly.  For now, we'll keep the structure relatively flat.

## Tips

### Use line breaks, not spaces

Whitespace is an excellent opportunity to add lines of code to your diff.

*Bad*:

```js
// 1 LOC
const foo = (bar, baz, qux) => bar && baz && qux;
```

**Good**:

```js
// 13 LOC
function
  foo
    (
      bar,
      baz,
      qux,
    )
  {
    return (
      bar &&
      baz &&
      qux
    );
  }
```
