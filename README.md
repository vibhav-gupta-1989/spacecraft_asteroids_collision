CUDA-based Parallel Collision Detection
- Implemented CUDA-based parallel collision detection of a spacecraft with ~90K asteroids, replacing O(N) CPU checks with massively parallel GPU kernel
  (1024-thread blocks).
- Designed GPU memory pipeline and used atomic operations for collision reduction.
- Benchmarked CPU vs GPU execution, achieving up to 10x speedup.
