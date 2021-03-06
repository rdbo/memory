<h1>MOVED TO: <a href="https://github.com/rdbo/libmem">rdbo/libmem</h1>  

# Memory
Memory Management on Windows/Linux  
https://github.com/rdbo/Memory  

# libmem
C-Compatible version of this project, which is being more updated and has more features:  
https://github.com/rdbo/libmem  

# Usage
Just copy the "mem" folder to your project, then include "mem/mem.hpp" and make sure to compile "mem/mem.cpp".  
Check "docs/documentation.txt" for more guidance  

# LICENSE
Read LICENSE  

# Overview
```
mem::ex::get_pid
mem::ex::get_process
mem::ex::get_process_name
mem::ex::get_module_info
mem::ex::is_process_running
mem::ex::read
mem::ex::write
mem::ex::set
mem::ex::scan
mem::ex::protect
mem::ex::allocate
mem::ex::pattern_scan
mem::ex::load_library

mem::in::get_pid
mem::in::get_process
mem::in::get_process_name
mem::in::get_module_info
mem::in::read
mem::in::write
mem::in::set
mem::in::scan
mem::in::protect
mem::in::allocate
mem::in::detour
mem::in::detour_length
mem::in::detour_trampoline
mem::in::detour_restore
mem::in::pattern_scan
mem::in::load_library
```

# Projects
Projects made with the Memory Lib:    
![Counter-Strike 1.6 External Bunnyhop Hack (Linux)](https://github.com/rdbo/cstrike-bhop-ex-linux)  
![Counter-Strike 1.6 Internal Bunnyhop Hack (Linux)](https://github.com/rdbo/cstrike-bhop-in-linux)  

# TODO
```
Add support for allocating and protecting memory externally on Linux
Add support for loading libraries externally on Linux
Clean up code
Add a simple documentation
Add some examples
```
