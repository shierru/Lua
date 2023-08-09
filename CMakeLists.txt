cmake_minimum_required(VERSION 3.1)
project(lua LANGUAGES C VERSION 5.4.6)

option(LUA_SUPPORT_DL "Support dynamic loading of compiled modules" OFF)
option(LUA_BUILD_AS_CXX "Build lua as C++" OFF)
option(LUA_ENABLE_SHARED "Build dynamic liblua" OFF)

enable_language(CXX)

add_subdirectory(lua)
