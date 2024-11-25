# mac-scrollbar-better

> Scrollbar React component with macOS style.

- It's a fork and improved version of [mac-scrollbar](https://github.com/MinJieLiu/mac-scrollbar).

## Compare to mac-scrollbar

- [https://dengfuping.github.io/mac-scrollbar-better](https://dengfuping.github.io/mac-scrollbar-better)
- [MinJieLiu.github.io/mac-scrollbar](https://minjieliu.github.io/mac-scrollbar)

## Usage

```shell
npm i mac-scrollbar-better
```

Import style

```jsx
import 'mac-scrollbar-better/dist/mac-scrollbar-better.css';
```

Basic

```tsx
import { MacScrollbar } from 'mac-scrollbar-better';

function Foo() {
  return (
    <MacScrollbar>
      <div>Content</div>
    </MacScrollbar>
  );
}
```

Global window scrollbar

```tsx
import { GlobalScrollbar } from 'mac-scrollbar-better';

function App() {
  return <GlobalScrollbar />;
}
```

### API

- API is full compatible with [mac-scrollbar](https://github.com/MinJieLiu/mac-scrollbar?tab=readme-ov-file#api)
