<img width="1920" height="1080" alt="Preview" src="https://github.com/user-attachments/assets/99277de8-ce6d-4ac7-a9e0-7184e32903e6" />


Ventoy Theme
A Windows 7 Aero-inspired boot menu for Ventoy and GRUB, with custom artwork, a blue selector, and SF Pro-style text.
Features
- Windows 7 Aero look
- Support for 1080p and 4K, plus other screen resolutions
- Automatic resolution matching in Ventoy
- Custom background, selector, and fonts
Installation (Ventoy)
1. Download the 1080p or 4K ZIP from Releases.
2. Extract it on your Linux PC.

Open a terminal in the extracted folder and run:
python3 install-to-ventoy.py /path/to/VentoyUSB
Replace /path/to/VentoyUSB with the path to your mounted Ventoy data partition (the large partition where you store ISOs).

The installer copies the theme and backs up your existing ventoy.json.
Installation (GRUB)
1. Copy the appropriate grub/aero-v6-* theme folder to /boot/grub/themes/.
2. Set GRUB_THEME in /etc/default/grub to that folder's theme.txt.
3. On Arch/Artix Linux, run:
4. sudo grub-mkconfig -o /boot/grub/grub.cfg
Notes
- No ISO files found? Add a supported ISO to your Ventoy USB drive.
- Text too big? Check Ventoy's graphics resolution under F5 → Tools → Resolution Configuration.
- A 4K monitor doesn't necessarily mean Ventoy boots in 4K.
Credits
- Background artist: (https://x.com/ssums12) (https://www.youtube.com/@sum123) (https://www.pixiv.net/en/users/7175089) 
- Fonts: SF Pro
  
- If you would like this taken down Message me at, I am just a Fan, Wanted to Create somethin cewl...,
(https://x.com/super_kibble)
