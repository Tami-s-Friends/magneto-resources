# magneto-resources

Pre-built binaries used by [pymagneto-core](https://github.com/tami-v-pro/pymagneto_core)

## Contents

| File | Arch | Source |
|---|---|---|
| `binaries/busybox-arm64` | ARM64 (arm64-v8a) | busybox 1.38.0, compiled with SELinux support — required for `device.fs` and `about.kernel`/`about.uptime` in pymagneto_core 4.3.0+ |
| `binaries/busybox-x86_64` | x86_64 (AVD / emulator) | busybox.net 1.31.0-defconfig-multiarch-musl |

## Usage

```bash
mkdir -p ~/.magneto_core/resources/binaries
cd ~/.magneto_core/resources/binaries
curl -O https://raw.githubusercontent.com/tami-v-pro/magneto-resources/main/binaries/busybox-arm64
curl -O https://raw.githubusercontent.com/tami-v-pro/magneto-resources/main/binaries/busybox-x86_64
chmod 755 busybox-arm64 busybox-x86_64
```
