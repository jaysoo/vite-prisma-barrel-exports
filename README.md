This is a demo of barrel exports from `@prisma/client` not working with using Vite.

For example, in `test.ts` you have:

```
export * from '@prisma/client';
```

Then in `App.tsx` you import it:

```ts
import * as x from './test';
```

This results in an error.
