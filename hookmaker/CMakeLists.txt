add_executable(hookmaker WIN32 hookmaker.cpp hookmaker_res.rc)
target_link_libraries(hookmaker comctl32 shlwapi cr2 ole32)
target_compile_options(hookmaker PUBLIC -DUNICODE -D_UNICODE -D__CRT_STRSAFE_IMPL)
