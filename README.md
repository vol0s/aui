<h1 align="center">
  <a href=https://www.archlinux.org/>Archlinux</a> Ultimate Installer
</h1>
<h4 align="center">Installation & Configuration of archlinux has never been much easier!</h4>

## Note
* You can first try it in a `VirtualMachine`

## Prerequisites

- A working internet connection
- Logged in as 'root'

## Obtaining The Repository
### With git
- Increase cowspace partition: `mount -o remount,size=2G /run/archiso/cowspace`
- Get list of packages and install git: `pacman -Sy git`
- Get the script: `git clone git://github.com/helmuthdu/aui`

### Without git
- Increase cowspace partition: `mount -o remount,size=2G /run/archiso/cowspace`
- Get the script: ` wget https://github.com/helmuthdu/aui/tarball/master -O - | tar xz`
    - an alternate URL (for less typing (github shorten)) is ` wget https://git.io/vS1GH -O - | tar xz`
    - an alternate URL (for less typing) is ` wget http://bit.ly/NoUPC6 -O - | tar xz`
    - super short `wget ow.ly/wnFgh -O aui.zip`

## How to use
- FIFO [System Base]: `cd aui ; ./fifo`
- LILO [The Rest]: `cd aui ; ./lilo`

## Thank helmuthdu
If you like my work, please consider a small Paypal donation at helmuthdu@gmail.com :)

## License :scroll:
This project is licenced under the GNU General Public License V3. For more information, see the `LICENSE` file or visit https://www.gnu.org/licenses/gpl-3.0.en.html.
