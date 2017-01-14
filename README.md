# Lua-Adapter
Use this lightweight wrapper- / adapter-class as an interface between Lua and C++.

Usage:

      LuaAdapter lua("test.lua");      
      
      int width {0};
      lua.get("width", width);  // width=600
» see **test.cpp** for more examples

Compile: 
      
      g++ lua_adapter.cpp test.cpp -std=c++0x -llua -ldl -Wall



Requirements:
- liblua5.2-dev
- liblua5.2-0 (or later)


