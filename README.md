
# FinELikEWinE-Clang_69

A copy of the **AOSP Clang** toolchain (`clang-r614150`, Clang/LLD 23.0.1) used by the
FinELikEWinE kernel builder, so builds don't depend on anyone else's download link.

- Builder: https://github.com/suman-1007-cyber/FinELikEWinE-MT6768-ActioN_69
- Download: see **Releases** (`clang.tar.gz`, with its SHA-256 in `clang.sha256`)

## How the copy was made
The workflow **Mirror Clang** (Actions tab) downloads the archive, checks that it is a valid
`.tar.gz` containing `bin/clang`, and attaches it to a release of this repo. To add another
version later, run the workflow again with a new URL and a new tag.

## Credits
- Compiler: Google / the Android Open Source Project (LLVM, Apache-2.0 with LLVM exceptions)
- Original archive: [@MrShockWAVEog](https://github.com/MrShockWAVEog) (Google-Clang-Mirror)
