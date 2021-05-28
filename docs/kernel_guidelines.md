# Maintainer Guidelines for StormBreaker:

The use of “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” is per the IETF standard defined in RFC2119.

Exceptions **SHOULD** be made by contacting the administration team.

- Maintainers should keep their branches name "main". In case if sub-branches exist "like EAS, HMP, Oldcam, Newcam", then add a "/" after "main" for keeping continuity between them "like main/eas, main/hmp, main/eas-oldcam".
- Maintainers should push their ak3 repo as the name of the branch their device codename over our repo "https://github.com/stormbreaker-project/AnyKernel3/commits/master"

- We don’t allow using useless/placebo custom iosched/governors on your kernel.
- We don’t allow CPU/GPU clock manipulation and/or hardware voltage manipulation.
- We don't allow forcing a determinate SELinux status.

- We allow using custom kernel base if they are free-to-use.
- We allow using older Linux/CAF upstream if they give some problems.
- We allow using particular measures that make the kernel booting up "like https://github.com/KudProject/kernel_msm-4.9/commit/adfcd0e5550957cf23b5a6cdd94b81207fb2ffe7 or https://github.com/KudProject/kernel_msm-4.9/commit/28f2f199dc183680426191d67827e5ca30517df8".

- Is advised to regenerate the defconfig after you enable/disable a module/configs.

- Try to keep consistency between commits.
- Try to clean up your kernel source from useless/placebo commits.
- Try to maintain compatibility with most of the firmware available for your device.

- All the builds "blind or not" must be tested before release.
- Maintainers must push their source code on StormBreaker GitHub organization with proper authorship.
- Maintainers can build the kernel by using CI services directly on StormBreaker Github organization.
