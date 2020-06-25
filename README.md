# cpu
internal/cpu(in Go standard lib) with these detections:

>- AVX512
>
>- Cache Size
>
>- Invariant TSC
>

It also provides false sharing range, see `X86FalseSharingRange` for X86 platform.

# Acknowledgement

[klauspost/cpuid](https://github.com/klauspost/cpuid)