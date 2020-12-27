# 1. Overview
We explore temporal locality using statistics to optimize original TBN prefetching(TBNp) policy implemented by NVIDIA CUDA drivers. 

# 2. Performance Evaluation 
We measure performance with Rodinia Benchmark
http://www.cs.virginia.edu/rodinia/doku.php

# 3. Result
For SRAD we got a speedup of 15 percent in the unlimited memory case, and a speedup of 12 percent in the limited memory case compared to original TBNp. 

![alt text](https://github.com/yeojinia/gpu_tbntl_prefetcher/blob/main/limited_memory_result.png?raw=true)
![alt text](https://github.com/yeojinia/gpu_tbntl_prefetcher/blob/main/unlimited_memory_result.PNG?raw=true)

# 4. Contributors
Yeojin Kim,
Josiah Blaisdell,
SangYeon Lee

