# @midwayjs/hooks

> [中文文档](./README.zh-cn.md)

Midway Hooks Api

## Usage

```typescript
import { useContext } from '@midwayjs/hooks'

// get url query
export function getQuery() {
  const ctx = useContext()
  return ctx.query
}
```
