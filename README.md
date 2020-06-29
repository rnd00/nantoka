# なんとか

Made because:
- I need some place where I can note down stuffs, accessible from everywhere, not めんどくさい like making a blog or something
- Getting used to git commands and whatnots
- Writing them down in *markdown*
- Things written here might be dumb for my future self, but it would serve as something I could laugh out later on too

---

## [6/29] Error Handling

### thoughts:
- define everything as an object and then call it with custom error handler
- e.g.
  ```javascript
  const ERRORS = {
    notFound: {
      code: 404,
      internal: 404000,
      message: 'Not Found'
    },

    // add more as you need
  }
  ```
- if you need the trace, use `err.trace` at callback
- `err.statusCode` and `err.message` should work if you want to use them later on
---

## calendar!

|月|火|水|木|金|土|日|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|21|22|23|24|25|26|27|
|28|29|30|01|02|03|04|
|-|-|-|-|-|-|-|