target_sources(swiftSILOptimizer PRIVATE
  BasicBlockOptUtils.cpp
  CFGOptUtils.cpp
  CanonicalizeInstruction.cpp
  CanonicalOSSALifetime.cpp
  CanonicalizeBorrowScope.cpp
  CastOptimizer.cpp
  CheckedCastBrJumpThreading.cpp
  CompileTimeInterpolationUtils.cpp
  ConstantFolding.cpp
  ConstExpr.cpp
  Devirtualize.cpp
  DifferentiationMangler.cpp
  DistributedActor.cpp
  Existential.cpp
  GenericCloner.cpp
  Generics.cpp
  InstructionDeleter.cpp
  InstOptUtils.cpp
  KeyPathProjector.cpp
  LexicalDestroyFolding.cpp
  LexicalDestroyHoisting.cpp
  LoadStoreOptUtils.cpp
  LoopUtils.cpp
  OptimizerStatsUtils.cpp
  PartialApplyCombiner.cpp
  PerformanceInlinerUtils.cpp
  ShrinkBorrowScope.cpp
  SILInliner.cpp
  SILSSAUpdater.cpp
  SpecializationMangler.cpp
  StackNesting.cpp
  ValueLifetime.cpp
  OwnershipOptUtils.cpp)
