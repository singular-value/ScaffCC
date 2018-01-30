add_llvm_library(LLVMLinker
  LinkArchives.cpp
  LinkItems.cpp
  Linker.cpp
  IRMover.cpp
  LinkModules.cpp

  ADDITIONAL_HEADER_DIRS
  ${LLVM_MAIN_INCLUDE_DIR}/llvm/Linker

  DEPENDS
  intrinsics_gen
  )
