# Enable intel_iommu in GRUB
1. Edit /etc/default/grub and add the following options to GRUB_CMDLINE_LINUX_DEFAULT:
```bash
intel_iommu=on
```

2. Run `update-grub`

