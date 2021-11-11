## v-graphin-icons


v-graphin's font icons

## Usage

```jsx | pure
import IconLoader from "v-graphin-icons"
import "v-graphin-icons/dist/index.css"
import { registerFontFamily } from "v-graphin"
/** 加载 font icons **/
const icons = registerFontFamily(IconLoader);
const data = Utils.mock(10).graphin();

data.nodes.forEach((node) => {
  node.style = {
    icon: {
      type: 'font',
      fontFamilay: 'graphin',
      value: icons.plus,
    },
  };
});
```
