# JavaScript SDK

```typescript
import { FlowForgeClient } from "@flowforge/sdk";

const client = new FlowForgeClient({ apiKey: "your-key" });
const workflows = await client.listWorkflows("tenant-id");
```
