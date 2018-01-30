add_llvm_library(LLVMMCJIT
  MCJITMemoryManager.cpp
  MCJIT.cpp

  DEPENDS
  intrinsics_gen
  )
