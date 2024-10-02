[
    alias(
        name = "debian_bullseye_{}".format(arch),
        actual = "@debian_bullseye_{}//:sysroot".format(arch),
        visibility = ["//visibility:public"],
    )
    for arch in [
        "arm64",
        "amd64",
        "armhf",
        "i386",
        "mips64el",
        "mipsel",
    ]
]
