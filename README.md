# Bykeyboard PC program

The Windows program for Bykeyboard, the Android app that turns a phone or tablet into a keyboard and trackpad for a
Windows PC. The program is needed for the Wi-Fi and USB cable modes; the Bluetooth mode needs no program.

- Download: `Bykeyboard-PC.zip` under [Releases](https://github.com/promm-1i/bykeyboard/releases/latest)
- Setup guide: https://noveriq.co.kr/bykeyboard/en/ (한국어: https://noveriq.co.kr/bykeyboard/)
- Phone app: Google Play, "Bykeyboard"

Windows 11, 64-bit. Unzip and run `bykeyboard.exe`; it sits in the notification area. A phone connecting for the first
time over Wi-Fi shows a card with a 6-digit number on the PC; choose Allow there (or press Alt+A, and Ctrl+Alt+Y brings
the card up). If "Windows protected your PC" appears, choose More info → Run anyway. The first Wi-Fi connection may ask
to allow Bykeyboard through Windows Firewall; tick both private and public networks if the PC's network is public.

Over USB, plug the phone in with a data cable while the program runs. USB debugging can stay off. The first time, a card
asks to install the USB driver once (Windows' own WinUSB driver, one administrator prompt); after that, file transfer for
that phone is off on this PC until you choose "Remove Bykeyboard from this PC" in the tray menu.

Only the program files are published here, not the source code.
