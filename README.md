# Windows 11 vTPM and Native Key Provider

Documentation and test results for deploying Windows 11 with vTPM, using a Native Key Provider (NKP), storing recovery information in CyberArk, restoring NKP on another vCenter, and validating Cross vCenter Migration.

## Project structure

- `Documentation/` - final deployment and recovery guide
- `Screenshots/01-Native-Key-Provider/`
- `Screenshots/02-NKP-Backup/`
- `Screenshots/03-CyberArk/`
- `Screenshots/04-Windows11-vTPM/`
- `Screenshots/05-NKP-Restore/`
- `Screenshots/06-Cross-vCenter-Migration/`
- `Troubleshooting/` - Broadcom Support case and troubleshooting notes

## Tested environment

- Source vCenter: vSphere Client 8.0.3.01000
- Source ESXi: VMware ESXi 8.0.3, build 25429389
- Target vCenter: vSphere Client 9.1.0.0100
- Target ESXi: VMware ESXi 9.1.0.0200, build 25557999

## Result

Cross vCenter Migration of a Windows 11 VM with vTPM enabled was successfully completed after validating the Native Key Provider configuration and key consistency between the source and destination environments.
