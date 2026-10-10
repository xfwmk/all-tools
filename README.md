# all-tools
All of my pentesting CLI versions in one repository
______________________________________________________________________________________________________________________________________________________________________________________

kali:
# Kali Attack Interface
Pentesting tools CLI (better version)
Built for Kali linux however any will work provided it has all of the tools installed.

Requirements:
- bash
- sudo
- curl
- netcat
- hping3
- openssl
- stunnel
- nmap
- nslookup
- ike-scan

Optional (Only needed if you want to use the security menu in this script.):
- Mullvad VPN
- Proxychains
- Tor
(The "VPN" function will later be configured for Mullvad VPN, others will not work with this script stock.)


NOT WORKING!!
WILL COMPLETE ONCE I REINSTALL KALI LINUX TO TEST!!
______________________________________________________________________________________________________________________________________________________________________________________

pentestingCLI:
This shellscript is an easy way to perform DoS or Recon, made for fun and not intended to EVER be used for malicious or personal gain.
The author does not claim any responsibility for any potential malicous or illegal activities performed using this script
Intended for use only on linux emphasis on kali, due to the lack of pentesting tools on other distros i stripped some functionality that would otherwise be possible on kali

Required applications:
hping3,
nping (comes with Nmap)

install:

$ wget https://github.com/xfwmk/Pentesting-CLI/blob/main/pentestCLI

Make executable...

chmod +x pentestCLI

To run:

./pentestCLI

Use however you want otherwise
by xfwmk
______________________________________________________________________________________________________________________________________________________________________________________

pentestingCLI.py:
This python script is an easy way to perform DoS or Recon, made for fun and not intended to EVER be used for malicious or personal gain. The author does not claim any responsibility for any potential malicous or illegal activities performed using this script Intended for use only on linux emphasis on kali, due to the lack of pentesting tools on other distros i stripped some functionality that would otherwise be possible on kali

Required applications: hping3, nping (comes with Nmap), python3

install:

$ wget https://github.com/xfwmk/Pentesting-CLI-python/edit/main/pentestCLI

Now run:

python3 pentestCLI

Use however you want otherwise by xfwmk
