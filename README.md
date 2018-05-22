# qemu-test

Some test scripts and images for QEMU.

Not super clean, but functional.

Usage:

    git clone qemu-test
    cd qemu-test
    wget https://github.com/cirosantilli/linux-kernel-module-cheat/releases/download/uploads/images-ab21ef58deed8536bc159c2afd680a4fabd68510.zip
    unzip images-*.zip
    cd ..
    git clone qemu
    cd qemu
    ../qemu-test/configure
    make -j "$(nproc)"
    ../qemu-test/$arch/<script>

Images generated from: <https://github.com/cirosantilli/linux-kernel-module-cheat/releases/tag/uploads>
