# qemu-test

Some test scripts and images for QEMU.

Not super clean, but functional.

Usage:

    git clone qemu-test
    cd qemu-test
    wget https://github.com/cirosantilli/linux-kernel-module-cheat/releases/download/sha-dbecf15f8ff9169e64e5f9402a692647174860ae/images-dbecf15f8ff9169e64e5f9402a692647174860ae.zip
    unzip images-*.zip
    cd ..
    git clone qemu
    cd qemu
    ../qemu-test/configure
    make -j "$(nproc)"
    ../qemu-test/$arch/<script>

Images generated from: <https://github.com/cirosantilli/linux-kernel-module-cheat/releases/tag/uploads>
