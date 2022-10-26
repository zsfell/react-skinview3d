# react-skinview3d

Three.js powered Minecraft skin viewer component for react - see upstream project for more info [skinview3d](https://github.com/bs-community/skinview3d)

[![NPM](https://img.shields.io/npm/v/react-skinview3d.svg)](https://www.npmjs.com/package/react-skinview3d)
[![npm stats](https://img.shields.io/npm/dw/react-skinview3d)](https://www.npmjs.com/package/react-skinview3d)

Try on codesandbox.io

[![CodeSandbox](https://img.shields.io/badge/Codesandbox-040404?style=for-the-badge&logo=codesandbox&logoColor=DBDBDB)](https://codesandbox.io/s/react-skinview3d-vb7f88?file=/src/App.tsx)
## Install

```bash
npm install react-skinview3d
```

## Usage

```jsx
import React from "react"
import ReactSkinview3d from "react-skinview3d"

const App = () => {

  return (
    <ReactSkinview3d
      skinUrl="textures/skin-1.8-slim-no_hd.png"
      capeUrl="textures/minecon-cape-2016.png"
      height="500"
      width="500"
    />
  )

}

export default App;
```

## License

MIT © [Hacksore](https://github.com/Hacksore)
