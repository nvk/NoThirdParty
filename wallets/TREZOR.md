TREZOR launched in August 2014 as the first Bitcoin hardware wallet, offering secure cold storage plus the ability to spend with the convenience of a hot wallet. TREZOR is a small, key-sized device which connects to your computer with a USB cable. It stores your Bitcoin private keys offline and signs transactions for you. It can be safely used on a malware infected computer.

TREZOR is compatible with a number of wallets, including Electrum, Multibit HD, and GreenAddress on desktop, GreenBits on Android, and myTREZOR.com on the web. Use the TREZOR Chrome extension to manage your device.

TREZOR can also be used as a secure login device on a number of websites. 

## Security

TREZOR provides top-notch security for bitcoins–there may not be a better option. The setup protects against both physical and virtual theft.

TREZOR is an HD wallet where you control the private keys, so an entire wallet can be backed up with 24 words which are generated on setup. The original 24-word seed is generated with RNG from both the device and the computer. The seed is generated offline and displayed on the TREZOR’s screen, which ensures that the seed is never on an internet-connected device.

On setup, the user generates a PIN code. If someone steals the TREZOR itself, the PIN is required for spending. After each incorrect guess, the wait between guesses is raised by a power of two. Making 30 guesses would take 17 years at this rate.

For extra security, you can add a passphrase to the 24-word seed. This acts as a 25th word in the seed. You must remember the passphrase because the seed without the passphrase is not enough to recover the wallet. A passphrase offers more security, but if forgotten the wallet cannot be recovered.

If a TREZOR is lost, you can recover the entire wallet with the 24-word seed and passphrase if used. Recovery can be done with another TREZOR or with other supported Bitcoin wallets.

TREZOR’s screen allows you to confirm that you’re sending to the intended recipient, but this does not prevent against phishing attacks. If someone changes the address on your computer, it’d still appear as the correct address even when confirming with TREZOR’s screen. In the future, BIP70 will help prevent against this kind of attack.

A full overview of how TREZOR handles security threats can be found on the Satoshi Labs website.

## Privacy

TREZOR itself offers very good privacy. The device is shipped with no serial number, so Satoshi Labs has no way of tracking your actions after you receive the device. All of the software is open source. The device itself is a login, so no usernames or passwords are needed when using TREZOR.

Privacy is determined by the wallet which the TREZOR is connected to: Electrum, Multibit HD, and GreenAddress on desktop, GreenBits and Mycelium on Android, and myTREZOR.com on the web.
