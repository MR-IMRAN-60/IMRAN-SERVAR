![Imran-Ahmed](https://i.imgur.com/Qhydmxw.jpeg)

# Installation

You can install `imran-servar` using npm:

```bash
npm install imran-servar
```

## Features

* [Pinterest](#pinterest)

## Pinterest <a name="pinterest"></a>

```js
const { pinterestdl } = require('imran-servar');

(async () => {
  console.log(await pinterestdl('https://in.pinterest.com/pin/617204323960160868/'));
})();
```
_You can use [pin.it](https://pin.it) and [in.pinterest.com](https://in.pinterest.com) URLs._

#### Output
```json
{
   "ironman":{
      "url":"https://i.pinimg.com/736x/11/3a/4a/113a4af38e8eae9b500457071986782e.jpg",
      "title":"胡宮 -Komiya- (@komiya_latte) on X",
      "type":"image",
      "Creator":"MOHAMMAD-IMRAN",
      "description":"劇場 "
   }
}
```

------

-----

### Coming Soon

This package is under development, and many exciting features are planned for future releases. Stay tuned for updates and enhancements!

## Contributing

We welcome contributions! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request. If you want to contact me, check my [GitHub profile](https://github.com/MR-IMRAN-60).

Copyright © 2024 IMRAN
