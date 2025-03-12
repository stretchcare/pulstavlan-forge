# Pulstavlan Windows Application
This is an open repository containing installation files for Pulstavlan Windows Application. This client ensures a good touch fullscreen experience.
We provide both an auto-update version and a version for enterprise installation.

[The latest release can be found here](https://github.com/stretchcare/pulstavlan-forge/releases/latest)

## PULSTAVLAN_URL environment variable
Set the PULSTAVLAN_URL environment variable on all machines running the application for example using Group Policy Objects.
The value should correspond to the organisations URL to the application including protocol i.e "https://region.pulstavlan.se"

# Enterprise installation

Use the MSI file Pulstavlan.msi for these scenarios.

## Silent installation example
> msiexec /i c:\pulstavlan-desktop\Pulstavlan.msi /qn /norestart /log c:\pulstavlan-desktop\install-log.log

# Single client installation
Use Pulstavlan-[version].Setup.exe file.
This version will automatically download the latest version whenever available and prompt the user to update and restart.

# Shortcuts

| Key          | Description              |
| ------------ | ------------------------ |
| F1           | Opens preferences dialog |
| Ctrl +       | Zoom in                  |
| Ctrl -       | Zoom out                 |
| Ctrl 0       | Reset zoom               |
| Ctrl 0       | Reset zoom               |
| Ctrl+F5      | Reload page              |
| Esc          | Exit application         |
| Ctrl+Shift+I | Open developer console   |

# Machine requirements on startup
On startup a machine check will provide a warning if the requirements are not met:
- The resolution must be 4K (3840x2160)
- Scale must be set to 100% (Do not follow the Windows recommendation, always set 100%)
- The refresh rate must be 60Hz

It is still possible to continue but it is strongly recommended to meet the specifications above.

