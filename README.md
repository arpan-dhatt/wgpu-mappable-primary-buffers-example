# wgpu-mappable-primary-buffers-example

Testing behavior of mappable primary buffers.

Output:
```
Storage Buffer Initialized with [1, 2, 3, 4]:
Storage Buffer Before Compute Dispatch has Run: [0, 0, 0, 0]
Storage Buffer After Compute Dispath has Completed: [0, 1, 7, 2]
```

## Credit:
Test derived from [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu/tree/39606585296a3c20214fc60818e210f3b4a541de/wgpu/examples/hello-compute) example 
