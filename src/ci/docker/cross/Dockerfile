FROM alexcrichton/rust-slave-linux-cross:2017-02-02
ENTRYPOINT []

ENV CARGO_TARGET_ARM_UNKNOWN_LINUX_GNUEABI_LINKER=arm-linux-gnueabi-gcc \
    CARGO_TARGET_ARM_UNKNOWN_LINUX_GNUEABIHF_LINKER=arm-linux-gnueabihf-gcc \
    CARGO_TARGET_ARMV7_UNKNOWN_LINUX_GNUEABIHF_LINKER=armv7-linux-gnueabihf-gcc \
    CARGO_TARGET_AARCH64_UNKNOWN_LINUX_GNU_LINKER=aarch64-linux-gnu-gcc \
    CARGO_TARGET_I686_UNKNOWN_FREEBSD_LINKER=i686-unknown-freebsd10-gcc \
    CARGO_TARGET_X86_64_UNKNOWN_FREEBSD_LINKER=x86_64-unknown-freebsd10-gcc \
    CARGO_TARGET_X86_64_UNKNOWN_NETBSD_LINKER=x86_64-unknown-netbsd-gcc \
    CARGO_TARGET_MIPS_UNKNOWN_LINUX_GNU_LINKER=mips-linux-gnu-gcc \
    CARGO_TARGET_MIPSEL_UNKNOWN_LINUX_GNU_LINKER=mipsel-linux-gnu-gcc \
    CARGO_TARGET_MIPS64_UNKNOWN_LINUX_GNUABI64_LINKER=mips64-linux-gnuabi64-gcc \
    CARGO_TARGET_MIPS64EL_UNKNOWN_LINUX_GNUABI64_LINKER=mips64el-linux-gnuabi64-gcc \
    CARGO_TARGET_POWERPC_UNKNOWN_LINUX_GNU_LINKER=powerpc-linux-gnu-gcc \
    CARGO_TARGET_POWERPC64_UNKNOWN_LINUX_GNU_LINKER=powerpc64-linux-gnu-gcc \
    CARGO_TARGET_POWERPC64LE_UNKNOWN_LINUX_GNU_LINKER=powerpc64le-linux-gnu-gcc \
    CARGO_TARGET_S390X_UNKNOWN_LINUX_GNU_LINKER=s390x-linux-gnu-gcc
