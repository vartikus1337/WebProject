# webproject

Example use of the assembly of mitosis for cross-Framivore libraries of components

## For assembling cross-components

> [!IMPORTANT]
> After established dependences

```bash
cd ./ui
bun run build
```

## To verify the collected components:

In folders as service/*

```bash
cd ./services/service-
bun run dev
```

## An example of using the collected components in projects:

react:
```tsx
import { nameComponent } from 'ui-kit/react';
```

svelte:
```tsx
import { nameComponent } from 'ui-kit/svelte';
```

### Another 

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run .
```

This project was created using `bun init` in bun v1.2.2. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.
