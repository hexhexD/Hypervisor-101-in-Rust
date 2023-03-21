# Welcome to Hypervisor 101 in Rust
This is a day long course to quickly learn the inner working of hypervisors and techniques to write them for high-performance fuzzing.

This course covers foundation of hardware-assisted virtualization technologies, such as VMCS/VMCB, guest-host world switches, EPT/NPT, as well as useful features and techniques such as exception interception for virtual machine introspection for fuzzing.

The class is made up of lectures using the materials within this directory and hands-on exercises with source code under the `Hypervisor-101-in-Rust/hypervisor` directory.

This lecture materials are written for the `gcc2023` branch; check out the starting point of the branch before you start.

```shell
git checkout e4c948ce1ed2afcdbd63d18f7b0f115d73d91bfc
```
