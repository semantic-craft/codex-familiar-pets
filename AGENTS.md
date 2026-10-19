# Pet asset maintenance

This repository contains pet packages, not the Codex application source.

- Package source: [pets](pets/); each package contains `pet.json` and `spritesheet.webp`. Preview sheets live in [previews](previews/).
- Asset format, installation and verification: [README](README.md). Rights and permitted use: [NOTICE](NOTICE.md).
- Check changed metadata, image dimensions, frame layout and transparency; keep [checksums.txt](checksums.txt) consistent with changed package bytes. A checksum proves byte identity, not animation quality.
- 验证：`check`（运行 `scripts/check`：`shasum -a 256 -c checksums.txt`；图像尺寸、帧布局与透明度仍需人工检查）。
- Installation and selection are separate operations from editing a package. Do not treat preview files as installed-client acceptance.
Read relevant [lessons](lessons.md) before implementation, review, or acceptance; update the matching entry after an observed correction or missed case.
