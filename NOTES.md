````javascript

export const colorCode = (color) => {
  return COLORS.indexOf(color.toLowerCase())
}

export const COLORS = ['black', 'brown', 'red', 'orange', 'yellow', 'green', 'blue', 'violet', 'grey', 'white']
`````

you can simplify your answer by using an implied return
`````
var func = x => x * x;                  
// concise body syntax, implied "return"
`````

this would yield the following answer

`````
export const colorCode = color =>  COLORS.indexOf(color.toLowerCase())

export const COLORS = ['black', 'brown', 'red', 'orange', 'yellow', 'green', 'blue', 'violet', 'grey', 'white']
