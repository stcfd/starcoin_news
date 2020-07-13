
---
title: Build from Source
weight: 5
---

Build starcoin from source.

<!--more-->

1. Clone source code

     ```shell
    git clone https://github.com/starcoinorg/starcoin.git
    cd starcoin
    ```
2. Setup build environment

    ```shell
    ./scripts/dev_setup.sh
    ```
3. Run debug build

    ```shell
   cargo build
    ```
4. Run release build

    ```shell
   cargo build --release
    ```
   
The debug version starcoin at target/debug/starcoin, and release version at target/release/starcoin.