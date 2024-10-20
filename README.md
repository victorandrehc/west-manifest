# Introduction
This Repository is meant to be as single manifest file of Victor's Zephyr studies and personal projects

# How to clone this project:
1. Install `west` command tool and Zephyr toolchain as said on Zephyr's [getting started](https://docs.zephyrproject.org/latest/develop/getting_started/index.html) page

2. on a shell terminal, execute:
    ```bash
    cd <work_dir>
    west init -m https://github.com/victorandrehc/west-manifest
    west update
    ```

3. [Optional] Enable nanopb module:
    ```bash
    west config manifest.project-filter -- +nanopb
    west update
    ```
