# Python Async Comprehension Examples

✨ This repository showcases the power of async comprehensions in Python using asyncio module. Check out the exciting examples below! 🚀

## Files:

1. **0-async_generator.py** 🌀
   - `async_generator`: A coroutine that yields random numbers between 0 and 10 asynchronously, waiting for 1 second in each iteration.
   - Usage example: `async for i in async_generator():`

2. **1-async_comprehension.py** 🎯
   - Imports `async_generator` from the previous file.
   - `async_comprehension`: A coroutine that collects 10 random numbers using an async comprehension over `async_generator`.
   - Usage example: `print(await async_comprehension())`

3. **2-measure_runtime.py** ⏱️
   - Imports `async_comprehension` from the previous file.
   - `measure_runtime`: Measures the total runtime of executing `async_comprehension` four times in parallel using `asyncio.gather()`.
   - Returns the total runtime.
   - Usage example: `print(asyncio.run(main()))`

Feel free to explore each file and run the examples to witness the magic of async comprehensions! ✨⚡️

GitHub repository: [alx-backend-python](https://github.com/username/alx-backend-python)
Directory: 0x02-python_async_comprehension

Enjoy the journey and happy coding! 🌟
