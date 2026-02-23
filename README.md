# Hikari-Arm64e-Release

This repository utilizes GitHub Actions to build an Xcode Toolchain integrated with Hikari and automatically publishes it.  
You can download the appropriate Xcode Toolchain for your environment from the GitHub Releases page.

## Usage Example
```
export SDKROOT=$(xcrun --sdk macosx --show-sdk-path)
./Hikari_LLVM23.0.0git.xctoolchain/usr/bin/clang test.c -mllvm -hikari -mllvm -enable-strcry -mllvm -enable-indibran -mllvm -enable-subobf -mllvm -enable-funcwra -mllvm -enable-splitobf -mllvm -enable-bcfobf
```

## Source Code
* [llvm-project (next-hikari branch)](https://github.com/Baw-Appie/llvm-project/tree/next-hikari)
* [Hikari-LLVM23-Core](https://github.com/Baw-Appie/Hikari-LLVM23-Core)
* [Hikari-LLVM23-Headers](https://github.com/Baw-Appie/Hikari-LLVM23-Headers)

## Acknowledgements
A significant portion of the codebase in this repository was adapted or forked from existing projects.  
This project would not have been possible without the foundational work of the repositories listed below. A huge thank you to all the original authors and contributors!

* [Hikari by HikariObfuscator Team](https://github.com/HikariObfuscator/Hikari)
* [HikariCore by HikariRebooted Team](https://github.com/HikariRebooted/HikariCore)
* [Hikari-LLVM15 by 61bcdefg](https://github.com/61bcdefg/Hikari-LLVM15)
* [Hikari-LLVM19 by PPKunOfficial](https://github.com/PPKunOfficial/Hikari-LLVM19)
