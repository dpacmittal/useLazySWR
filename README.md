# useLazySWR

Tiny react hook wrapped around useSWR to send requests lazily.

# Example

```typescript
import { useLazySWR } from 'uselazyswr';

const App = () => {
  const { execute, data } = useLazySWR('/url', fetcher);
  return <button onClick={execute}>Call Api</button>;
};
```
