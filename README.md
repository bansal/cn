# @bansal/cn

An utility function to merge tailwindcss classes.
Borrowed from [@shadcn/ui](https://github.com/shadcn-ui/ui)

## install

```bash
npm install @bansal/cn
```

## Usage

```javascript
import { cn } from "@bansal/cn";
const className = cn(
  "flex justify-start items-center p-0",
  "justify-between items-start",
  "p-4"
);
// className = "flex justify-between items-start p-4"
```
