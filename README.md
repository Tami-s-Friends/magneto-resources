# magneto-resources

Pre-built binaries used by [pymagneto-core](https://github.com/tami-v-pro/pymagneto_core)

## Contents

| File | Arch | Source |
|---|---|---|
| `binaries/busybox-arm64` | ARM (works on arm64-v8a and armv7) | busybox.net 1.31.0-defconfig-multiarch-musl (armv8l) |
| `binaries/busybox-x86_64` | x86_64 (AVD / emulator) | busybox.net 1.31.0-defconfig-multiarch-musl |

## Usage

```bash
mkdir -p ~/.magneto_core/resources/binaries
cd ~/.magneto_core/resources/binaries
curl -O https://raw.githubusercontent.com/tami-v-pro/magneto-resources/main/binaries/busybox-arm64
curl -O https://raw.githubusercontent.com/tami-v-pro/magneto-resources/main/binaries/busybox-x86_64
chmod 755 busybox-arm64 busybox-x86_64
```
