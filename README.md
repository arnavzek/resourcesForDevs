# symbols For Devs

Name  | Second Header
------------- | -------------
Close  | × ✗ ✘ ✕
Correct  | ✓ ✔ 
Back | ❮


# Generate Random string in JS

```
 Math.random().toString(36).substring(2, 15)

```
# Mobile First media query

```
@media only screen and (min-width: 800px) {
  body {
    background-color: lightblue;
  }
}

```

# Convert readme to styled HTML
https://dillinger.io/

# Make a library that be used both as a script tag and a node module

```
if (typeof module !== "undefined" && module.exports) {
  module.exports = U;
}
``

# Check if a particular css property is supported in the browser

```
             @supports ((-webkit-backdrop-filter: blur(2em)) or (backdrop-filter: blur(2em))) {
         
              }
```
