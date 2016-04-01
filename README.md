# Markdown

Render markdown (commonly used in messages)

```jsx
import * as Markdown from 'patchkit-markdown'

<Markdown.Block md={md} />
<Markdown.Inline md={md} />

// if provided, msg will supply username lookup for @-mentions
<Markdown.Block md={md} msg={msg} />
```

Use the .less file:

```less
@import "node_modules/patchkit-markdown/styles.less"
```