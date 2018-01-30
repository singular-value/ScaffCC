set(LLVM_LINK_COMPONENTS
  Support
  )

add_clang_library(clangRewrite
  FixItRewriter.cpp
  FrontendActions.cpp
  HTMLPrint.cpp
  RewriteMacros.cpp
  RewriteModernObjC.cpp
  RewriteObjC.cpp
  RewriteTest.cpp
  DeltaTree.cpp
  HTMLRewrite.cpp
  RewriteRope.cpp
  Rewriter.cpp
  TokenRewriter.cpp

  LINK_LIBS
  clangBasic
  clangLex
  )
