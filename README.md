# react-animated-heart

[!["Monthly Download"](https://img.shields.io/npm/dm/react-animated-heart.svg)](https://npmjs.org/package/react-animated-heart)
[!["Latest Release"](https://img.shields.io/npm/v/react-animated-heart.svg)](https://github.com/ShaunLWM/react-animated-heart/releases/latest)
[![MIT license](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/ShaunLWM/react-animated-heart/blob/master/LICENSE)

A simple Twitter-like animated button. <small>desperately needed it for one of my projects.</small>

![script preview](img/ss.gif)
## Installation
```npm install react-animated-heart```

```yarn add react-animated-heart```

## Usage
```javascript
import React, { useState } from "react";
import Heart from "react-animated-heart";

export default function App() {
  const [isClick, setClick] = useState(false);
  return (
    <div className="App">
      <Heart isClick={isClick} onClick={() => setClick(!isClick)} />
    </div>
  );
}
```

## License
MIT
