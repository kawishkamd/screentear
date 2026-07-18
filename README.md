# Intel Screen Tearing Fix

This script may help fix screen tearing issues on systems with an Intel CPU.

- Make sure you have installed the `xf86-video-intel` package.

  ```bash
  sudo pacman -S xf86-video-intel
  ```

To install and run the script, follow these steps:

- Clone this repository to your local machine.
- Navigate to the cloned directory.
- Make the script executable by running the following command:

  ```bash
  chmod +x tear.sh
  ```

- Run the script with elevated privileges by running the following command:

  ```bash
  sudo ./tear.sh
  ```

<details>
<summary><b>OR</b></summary>
Just copy the <code>20-intel.conf</code> file to <code>/etc/X11/xorg.conf.d/</code> manually.
</details>

**Note:** You will need to restart your X session or reboot your computer for the changes to take effect.
