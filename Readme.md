# react-hacker-text-effect

react-hacker-text-effect is a react base component that add encryption effect to given text.

codesandbox demo -> [Demo](https://codesandbox.io/s/nervous-galileo-oupmu?file=/src/App.js:0-289)
## Installation

Use the package manager [npm](https://www.npmjs.com/package/react-hacker-text-effect) to install react-hacker-text-effect.

```bash
npm install react-hacker-text-effect
```

## Usage

```jsx
import React from "react";
import { HackText } from "react-hacker-text-effect";

import "./styles.css";

export default function App() {
  return (
    <div className="App">
      <h1>react-hacker-text-effect</h1>
      <HackText word="Secret Message" textSize="28px" />,
    </div>
  );
}
```

props| default value| info
--- | --- | ---
word | `Loading` | string, the text you want to apply the effect on.
textSize| `60px` | string, text font size.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)