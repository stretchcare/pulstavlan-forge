# Pulstavlan Windows Client
This is an open repository containing installation files for Pulstavlan Windows client. This client ensures a good touch fullscreen experience.
We provide both an auto-update version and enterprise installation version.

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

