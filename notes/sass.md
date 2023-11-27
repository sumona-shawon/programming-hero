### How to use SASS
- install vs code extension: Live Sass Compiler
- create scss file & css file with same name
- code written in scss file will be converted into css

### Topic
- preprocessing
- variables
- nesting
- partials
- modules
- mixing
- extend
- operators

### Code
- variables
```
    $primary color: blue;
    h1{
        color: $primary-color;
    }
    ul{
        border: 2px solid $primary-color;
    }
```
- nesting
```
    nav{
        ul{
            border: 2px solid $primary;
            li{
                color: purple;
            }
        }
    }
```
- modules
```
    
```