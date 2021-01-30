## Symbols

Name  | Second Header
------------- | -------------
Close  | × ✗ ✘ ✕
Correct  | ✓ ✔ 
Back | ❮
Search | ⌕


## Generate Random string in JS

```
 Math.random().toString(36).substring(2, 15)

```
## Mobile First media query

```
@media only screen and (min-width: 800px) {
  body {
    background-color: lightblue;
  }
}

```

## Beautiful Console log
```
  
    console.log(
      "%c" + data,
      `color: Green; background-color: LightGreen; padding: 2px 5px; border-radius: 5px;`
    ); //type of print: error, warning, greeting
  

```

## Convert readme to styled HTML
https://dillinger.io/

## Make a library that be used both as a script tag and a node module

```
   if (typeof module !== "undefined" && module.exports) {
     module.exports = moduleName;
   }
``

# Check if a particular css property is supported in the browser

```
   @supports ((-webkit-backdrop-filter: blur(2em)) or (backdrop-filter: blur(2em))) {

    }
```
