# Maintainer Guidelines for StormBreaker:

The use of “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” is per the IETF standard defined in RFC2119.

Exceptions **SHOULD** be made by contacting the administration team.

- We don’t allow using any type of improper custom iosched/governors on your kernel.
- We don’t allow CPU/GPU clock manipulation and/or hardware voltage manipulation.
- We don't allow forcing a determinate SELinux status.
- We don't allow blind builds if they aren't properly tested.

- We allow using custom kernel base if they are free-to-use.
- We allow using older linux/caf upstream if they give some problems.
- We allow using certain measures that makes the kernel booting up "example https://github.com/KudProject/kernel_msm-4.9/commit/adfcd0e5550957cf23b5a6cdd94b81207fb2ffe7 or https://github.com/KudProject/kernel_msm-4.9/commit/28f2f199dc183680426191d67827e5ca30517df8".

- Is recommended regenerating the defconfig after you enable/disable a module/configs.

- Try to keep a consistency between commits.
- Try to cleanup your kernel source from useless/blacebo commits.
- Try to maintain compability with most of firmwares available for your device.

- All the builds must be properly tested before releasing.
- Maintainers must push their source code on StormBreaker github organization with proper author ship.

- Maintainers can build the kernel by using CI services directly on StormBreaker Github organization.
