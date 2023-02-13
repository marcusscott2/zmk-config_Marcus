cmake_minimum_required(VERSION 3.23)
project(zmk_config)

set(CMAKE_CXX_STANDARD 14)

add_executable(zmk_config
        config/corne.conf
        config/corne.keymap
        config/west.yml
        build.yaml)
