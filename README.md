*So we can import Monaco via ESM in the browser finally*

Usage:

```ts
// from a browser:
import monaco from "https://cdn.jsdelivr.net/npm/@imlib/monaco-esm@^0.0.2/+esm";

// or if you're using imlib:
import monaco from '@imlib/monaco-esm';
```

Then you can use it like normal:

```ts
const editor = monaco.editor.create(document.getElementById("container"), { 
  // ...
});
```

All workers work now.
