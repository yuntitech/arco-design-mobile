## 基础用法 @en{Basic Usage}

#### 1

```js
import { useState } from 'react';
import { ImagePicker } from '@arco-design/mobile-react';

export default function ImagePickerDemo() {
    const [images, setImages] = useState([
        { url: 'http://sf1-cdn-tos.toutiaostatic.com/obj/arco-mobile/_static_/large_image_1.jpg' }
    ]);
    return <ImagePicker images={images} onChange={setImages}/>;
}
```
