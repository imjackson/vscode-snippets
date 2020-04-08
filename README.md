# Jackson's VSCode User Snippets

## About

This respository holds my VSCode User Snippets files.

## Directory

### JavaScript

Found in: `javascript.json`

| snippet           | purpose                                                           |
| ----------------- | ----------------------------------------------------------------- |
| **functions**     |
| `fnd`             | `function ${1:name}(${2:params}) { $0 }`                          |
| `fne`             | `const ${1:varName} = (${2:params}) => { $0 }`                    |
| `nfne`            | `const ${1:varName} = function ${2:name}(${3:params}) { $0 }`     |
| `iife`            | `(() => { $0 })()`                                                |
| **loops**         |
| `fl`              | For loop statement                                                |
| `wl`              | While loop statement                                              |
| `dwl`             | Do...while loop statement                                         |
| `fil`             | For...in loop statement (loop over iterable names)                |
| `fol`             | For...of loop statement (loop over iterable values)               |
| **destructuring** |
| `dco`             | `const { ${1:values} } = ${2:object}`                             |
| `dca`             | `const [ ${1:values} ] = ${2:array}`                              |
| **console**       |
| `cl`              | `console.log($0)`                                                 |
| `cw`              | `console.warn($0)`                                                |
| `cer`             | `console.error($0)`                                               |
| `cin`             | `console.info($0)`                                                |
| `cti`             | `console.time($0)`                                                |
| `ctie`            | `console.timeEnd($0)`                                             |
| `ctb`             | `console.table($0)`                                               |
| `ccl`             | `console.clear()`                                                 |
| **other**         |
| `maparray`        | Implements array.map, passing currentValue and index              |
| `simplemaparray`  | Implements array.map, passing only currentValue with arrow syntax |
| `functimeout`     | Implements setTimeout() around a function                         |

### CSS

Found in: `css.json`

| snippet            | purpose                                                                                |
| ------------------ | -------------------------------------------------------------------------------------- |
| **display**        |
| `d`                | `display: $0;`                                                                         |
| `db`               | `display: block;`                                                                      |
| `di`               | `display: inline;`                                                                     |
| `dib`              | `display: inline-block;`                                                               |
| `dg`               | `display: grid;`                                                                       |
| `df`               | `display: flex;`                                                                       |
| **font/text**      |
| `co`               | `font-family: $0;`                                                                     |
| `ff`               | `font-family: $0;`                                                                     |
| `fs`               | `font-size: $0;`                                                                       |
| `fw`               | `font-weight: $0;`                                                                     |
| `fst`              | `font-style: $0;`                                                                      |
| `td`               | `text-decoration: $0;`                                                                 |
| `lh`               | `line-height: $0;`                                                                     |
| **other**          |
| `csflex`           | Creates styling rules for a flex-box with placeholders                                 |
| `centerflex`       | Creates styling rules for a completely centered flex-box                               |
| `setfont`          | Outputs lines for setting font family/size/weight                                      |
| `fullbreak`        | Creates styling rules for a full-width horizontal rule                                 |
| `calcwidth`        | Creates a width styling rule containing a calc() value                                 |
| `widthpadding`     | Creates width and padding styling rules containing a calc() value to factor in padding |
| `fileheader`       | Creates css file comment header for file description                                   |
| `fadein-keyframe`  | Outputs basic fade-in css keyframes                                                    |
| `loading-keyframe` | Outputs basic spinner loading circle css keyframes                                     |
| `loading-element`  | Outputs basic spinner loading circle element style rules                               |
| `media-query`      | Outputs max-width-based media query                                                    |

### React

Found in: `react.code-snippets`

| snippet                      | purpose                                                                               |
| ---------------------------- | ------------------------------------------------------------------------------------- |
| **basic statements/methods** |
| `imp`                        | `import ${1:React} from '${2:react}'`                                                 |
| `impd`                       | `import { ${1:Component} } from '${2:module}'`                                        |
| `expc`                       | `export const $0`                                                                     |
| `expd`                       | `export default $0`                                                                   |
| **components**               |
| `class-component`            | Creates a class-based react component structure                                       |
| `functional`                 | Creates a functional react component structure                                        |
| `stateless`                  | Creates a functional stateless react component structure                              |
| **hooks**                    |
| `useState`                   | `const [${1:state}, ${2:setState}] = useState(${3:false})`                            |
| `useContext`                 | `const { ${1:values} } = useContext($2)`                                              |
| `useRef`                     | `const ${1:ref} = useRef(${2:null})`                                                  |
| `useEffect`                  | `useEffect(() => { $1 }, [$2])`                                                       |
| `useLayoutEffect`            | `useLayoutEffect(() => { $1 }, [$2])`                                                 |
| **conditionals**             |
| `renif`                      | `{ ${1:condition} && ( $0 )}`                                                         |
| `renifel`                    | Ternary statement to conditionally render two components                              |
| `retif`                      | Statement to return a react element within component body if condition turns true     |
| `retifs`                     | `if (${1:condition}) return ${2:component}`                                           |
| **destructuring**            |
| `dcs`                        | Destructure state statement                                                           |
| `dcc`                        | Destructure context statement                                                         |
| `dcp`                        | Destructure props statement                                                           |
| **other**                    |
| `elem-react`                 | Creates a react-html element + 'className' attribute                                  |
| `ternstyle`                  | Creates a react-html style attribute with ternary operator                            |
| `onchangehandler`            | Creates an input changeHandler for 'name' and 'value' attributes                      |
| `conditionalrender`          | Creates a conditional rendering of a single component based on a single boolean state |
| `inputattrs`                 | Creates row of standard text input element attributes                                 |
| `fileheader`                 | Creates js/jsx file comment header for file description                               |
| **React Native**             |
| `rnimp`                      | `import { ${1:Component} } from 'react-native'`                                       |
| `rnss`                       | `export default StyleSheet.create({$0})`                                              |
