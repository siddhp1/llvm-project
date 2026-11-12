# Contributions

## Merged Upstream

- [KnownFPClass] Teach KnownFPClass that `sinh(non-positive) = non-positive` | [Issue #229536](https://github.com/llvm/llvm-project/issues/229536) | [PR #230627](https://github.com/llvm/llvm-project/pull/230627)
- [InstCombine] Teach `frem` that `frem(x, y)` == `frem(x, -y)` | [Issue #235856](https://github.com/llvm/llvm-project/issues/235856) | [PR #237329](https://github.com/llvm/llvm-project/pull/237329)
- [ValueTracking] Teach LLVM that `rem_euclid` is always positive | [Issue #224449](https://github.com/llvm/llvm-project/issues/224449) | [PR #236900](https://github.com/llvm/llvm-project/pull/236900)

## Submitted Patches

- [KnownFPClass] Add `KnownFPClass::fadd(x, CRHS)` to rule out subnormal results | [Issue #234364](https://github.com/llvm/llvm-project/issues/234364) | [PR #237966](https://github.com/llvm/llvm-project/pull/237966)

## Ongoing Work

- [ValueTracking] Add vector support to computeKnownBitsFromEuclideanRem | [Issue #224449](https://github.com/llvm/llvm-project/issues/224449) | [PR #241890](https://github.com/llvm/llvm-project/pull/241890)
