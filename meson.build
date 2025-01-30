# Example based on docs:
# https://mesonbuild.com/Python-module.html#extension_module
# and tutorial:
# https://mesonbuild.com/meson-python/tutorials/introduction.html#the-meson-build-description

project('python_rust', 'rust')

py = import('python').find_installation()

rust_ext = py.extension_module(
    'python_rust_lib',  # Output name
    'src/lib.rs',  # Rust source
    install: true
)
