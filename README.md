# mini-gpu-lib

CUDA-like runtime library for mini-gpu. User-facing API.

## API Reference

### Device Management
- [ ] `mini_init()` — Initialize GPU device
- [ ] `mini_shutdown()` — Shutdown GPU device
- [ ] `mini_device_info()` — Query device properties
- [ ] `mini_reset()` — Reset GPU state

### Memory Management
- [ ] `mini_malloc()` — Allocate GPU memory
- [ ] `mini_free()` — Free GPU memory
- [ ] `mini_memcpy()` — Copy data (host ↔ device)
- [ ] `mini_memset()` — Set GPU memory to value
- [ ] `mini_malloc_host()` — Allocate pinned host memory

### Kernel Execution
- [ ] `mini_launch()` — Launch kernel on GPU
- [ ] `mini_launch_async()` — Launch kernel asynchronously
- [ ] `mini_set_arg()` — Set kernel argument
- [ ] `mini_get_thread_id()` — Get thread ID (device-side)
- [ ] `mini_get_block_id()` — Get block ID (device-side)
- [ ] `mini_get_block_dim()` — Get block dimensions (device-side)

### Synchronization
- [ ] `mini_sync()` — Wait for GPU to complete all work
- [ ] `mini_stream_create()` — Create execution stream
- [ ] `mini_stream_sync()` — Wait for stream to complete
- [ ] `mini_stream_destroy()` — Destroy stream
- [ ] `mini_event_create()` — Create event
- [ ] `mini_event_record()` — Record event in stream
- [ ] `mini_event_wait()` — Wait for event
- [ ] `mini_event_destroy()` — Destroy event

### Shared Memory
- [ ] `mini_shared_alloc()` — Allocate shared memory (device-side)
- [ ] `mini_syncthreads()` — Barrier within thread block (device-side)

### Error Handling
- [ ] `mini_get_last_error()` — Get last error code
- [ ] `mini_error_string()` — Convert error to string
