# cpptimer
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Simple header only timer for C++ applications using [std::chrono](https://cplusplus.com/reference/chrono/).
Simply include the header, then you can, e.g.,

```
#incldue "timer.h"

// ...

Timer timer;
timer.start();
// cool computations
timer.stop();
std::printf("Blazing fast calculation took %e ms \n", timer.ellapsedNanoseconds);
```

Support for nanoseconds, microseconds, milliseconds, seconds, minutes, and hours.
