# Python Async Functions Showcase

🔧 This repository demonstrates the power of asynchronous functions in Python using asyncio module. Check out the cool examples below! 💫

## Examples:

1. **0-basic_async_syntax.py** 🕒
   - `wait_random`: Asynchronously waits for a random delay (0 to max_delay seconds) and returns it.
   - Usage: `print(asyncio.run(wait_random()))`

2. **1-concurrent_coroutines.py** ⏰
   - `wait_n`: Spawns multiple async tasks of `wait_random` with specified n and max_delay.
   - Returns sorted list of delays.
   - Usage: `print(asyncio.run(wait_n(5, 5)))`

3. **2-measure_runtime.py** 📏
   - `measure_time`: Measures total execution time for wait_n(n, max_delay) and returns average time per coroutine.
   - Usage: `print(measure_time(n, max_delay))`

4. **3-tasks.py** 🎯
   - `task_wait_random`: Returns an asyncio.Task that waits for a random delay.
   - Usage: `await task_wait_random(5)`

5. **4-tasks.py** 🎯
   - `task_wait_n`: Spawns async tasks of `task_wait_random` instead of `wait_random`.
   - Usage: `print(asyncio.run(task_wait_n(n, max_delay)))`

Explore these files and witness the magic of async functions! 🚀

Feel free to run the examples and enjoy the awesomeness! ✨
