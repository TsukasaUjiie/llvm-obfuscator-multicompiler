add_llvm_library(LLVMObfuscation
  CryptoUtils.cpp
  Substitution.cpp
  BogusControlFlow.cpp
  Utils.cpp
  SplitBasicBlocks.cpp
  StringObfuscation.cpp
  PrngAESCtr.cpp
  Flattening.cpp
  )

add_dependencies(LLVMObfuscation intrinsics_gen)
