# Telnet service login password is a weak password

## Basic equipment information

> hikvision-D1 driving recorder

> firmware version : 2.0.9

## The telnet service of the device is turned on

> Use the port scanning tool to scan the device IP address and find that the device has the telnet service enabled by default,Try to connect and find that an account and password are required, As shown below:

<img width="314" alt="屏幕截图 2023-12-19 195548" src="https://github.com/cvdyfbwa/Weak-password/assets/150313831/f12480ef-15c7-463e-9118-a146a1ba3cfc">

<img width="463" alt="image" src="https://github.com/cvdyfbwa/Weak-password/assets/150313831/a4f0a45d-a1f1-4acf-9018-071aacdf9ea4">

## Crack the password file in the firmware

> Analyze the firmware and find the password file,Use tools to crack password files and finally get account numbers and passwords, As shown below:

<img width="312" alt="image" src="https://github.com/cvdyfbwa/Weak-password/assets/150313831/c3558045-5a2a-440a-8bc8-0159ef4f76c2">

<img width="467" alt="屏幕截图 2023-12-19 182220" src="https://github.com/cvdyfbwa/Weak-password/assets/150313831/33b4cef3-8e1f-4d18-885c-7905bd7e3f5b">

## Try connecting using telnet

> Successfully entered the shell interface, As shown below:

<img width="854" alt="屏幕截图 2023-12-19 194143" src="https://github.com/cvdyfbwa/Weak-password/assets/150313831/548beea5-5de6-4da5-bcc5-05f4b86f3e9f">





