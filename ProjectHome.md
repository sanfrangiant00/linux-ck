Generic packages as well as CPU-specific packages. Many ARCH users are familiar with the concept of a generic kernel package. The official ARCH kernel is available in two flavors (either i686 or x86\_64) which are generic packages in that i686 will work with any compatible x86 CPU and x86\_64 will work with any compatible x86\_64 CPU.

The repo offers users a choice between the corresponding generic kernel26-ck packages or CPU-specific and optimized kernel26-ck packages:

ck-generic ==> Compiled with generic optimizations suitable for any compatible CPU just like the official ARCH kernel26 package. This is true for both Intel and AMD chips.

ck-atom ==> Intel Atom platform specific optimizations (Atoms 3xx/4xx/5xx) - NOT 2xx!

ck-core2 ==> Intel Core 2-family specific optimizations including Dual and Quads (Core 2/Newer Xeon/Core i3/i5/i7/Mobile Celeron based on Core2).

ck-k7 ==> AMD Athlon XP specific optimization - NOT generic k7!

ck-k8 ==> AMD K8-family specific optimizations (Athlon 64, Athlon 64 X2, 23xx Quad-Core Barcelona, Sempron, Sempron 64 (Socket 754 and AM2).

ck-k10 ==> AMD K10-family specific optimizations (Athlon X2 7x50, Phenom X3/X4, Phenom II, Athlon II X2/X3/X4, Sempron 64 (Socket AM3 only), 61xx Eight-Core Magny-Cours).

ck-p4 ==> Intel Pentium-4 specific optimizations (P4/P4-based Celeron/Pentium-4 M/Older Xeon).

ck-pentm ==> Intel Pentium-M specific optimizations (Pentium-M notebook chips/not Pentium-4 M).