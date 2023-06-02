# Stable Diffusion web UI root installer
A Stable Diffusion web UI installer with enabled root support.
This installer will automatically fetch the latest [master release of AUTOMATIC1111s Stable Diffusuion Web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui/).

Automatic Installation on Linux:
Install the dependencies:
# Debian-based:
`sudo apt install wget git python3 python3-venv`
# Red Hat-based:
`sudo dnf install wget git python3`
# Arch-based:
`sudo pacman -S wget git python3`

Navigate to the directory you would like the webui to be installed and execute the following command:

`bash <(wget -qO- https://raw.githubusercontent.com/timfischbach/stable-diffusion-webui-root-installer/master/webui.sh)`

Run webui.sh.
Check webui-user.sh for options.


NOTE: If you want to launch the finished installation as root too, change the installed webui.sh file:
Line 49: `can_run_as_root=0`
to:
`can_run_as_root=1`
Save the file afterwards.
