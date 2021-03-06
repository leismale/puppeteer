<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [HeapProfiler](./puppeteer.protocol.heapprofiler.md) &gt; [SamplingHeapProfileNode](./puppeteer.protocol.heapprofiler.samplingheapprofilenode.md)

## Protocol.HeapProfiler.SamplingHeapProfileNode interface

Sampling Heap Profile node. Holds callsite information, allocation statistics and child nodes.

<b>Signature:</b>

```typescript
export interface SamplingHeapProfileNode 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [callFrame](./puppeteer.protocol.heapprofiler.samplingheapprofilenode.callframe.md) | [Runtime.CallFrame](./puppeteer.protocol.runtime.callframe.md) | Function location. |
|  [children](./puppeteer.protocol.heapprofiler.samplingheapprofilenode.children.md) | [SamplingHeapProfileNode](./puppeteer.protocol.heapprofiler.samplingheapprofilenode.md)<!-- -->\[\] | Child nodes. |
|  [id](./puppeteer.protocol.heapprofiler.samplingheapprofilenode.id.md) | [integer](./puppeteer.protocol.integer.md) | Node id. Ids are unique across all profiles collected between startSampling and stopSampling. |
|  [selfSize](./puppeteer.protocol.heapprofiler.samplingheapprofilenode.selfsize.md) | number | Allocations size in bytes for the node excluding children. |

