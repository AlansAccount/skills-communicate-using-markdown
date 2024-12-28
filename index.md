# A single hash symbol for <h1> header
### Three hashes for <h3> header
###### and 6 hashes for <h6> header sizes ie going from 1 to 6 hashes.

![Image of Yaktocat from Step 2: Add an image](https://octodex.github.com/images/yaktocat.png)

## Step 3: Adding some code:
#### Examples From the Instructions:

```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

``` javascript
var myVar = "Hello, world!";
```

#### Some of my own.

``` React.js
export default function exampleFunction(props) {
  const [toggle, setToggle] = useState(false);

  function buttonToggleHandler() {
    setToggle(true);
  }

  return (
    <>
      <button onClick={buttonToggleHandler}>Show 2nd Button</button>
      {toggle && <button>Button</button>}
    </>
  )
}
```
