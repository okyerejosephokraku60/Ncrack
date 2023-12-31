# Ncrack
How to Setup NCRACK in Termux.


*How to setup NCRACK on Termux.*

You can use Ncrack on Termux. Ncrack is a network authentication cracking tool primarily used for cracking passwords in various protocols such as SSH, FTP, Telnet, etc.

To install Ncrack on Termux, follow these steps:

1. Open Termux on your Android device.

2. Update the package repositories by running the following command:
```
pkg update
```

3. Install the required dependencies (GCC, Make, LibPCAP, OpenSSL) by running the command:
```
pkg install -y root-repo
```
```
pkg install -y nmap
```
Note: The `nmap` package includes Ncrack.

4. Once the installation is complete, you can verify Ncrack by running:
```
ncrack --help
```


You can now use Ncrack to perform network authentication cracking within Termux. However, please keep in mind that using Ncrack or any other tool for unauthorized activities or without proper consent is illegal and unethical. Always ensure that you have the necessary permissions and adhere to ethical guidelines when conducting any security-related activities.
