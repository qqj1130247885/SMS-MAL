# SMS-MAL
These data are related to paper"An Empirical Study on Malicious SMS-Based Apps".

To contribute to relevant research topics, such as AI-based interpretable malicious behavior classification, we release 56 malware samples as a benchmark. We hope they can be used as a fundamental dataset in future SMS-based malware research.

The following is a brief introduction about the 7 categories and their corresponding attack chains.

## Message stealer

This category of malware can steal victim’s messages by secretly sending them from the infected device to a remote server.
![123](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/messageStealer.jpg)


## Misclick to pay

This category of malware can cause unaware service charges by bypassing a two-factor authentication (2FA), such as typing in a verification code by user, and completing a subscription payment. 

![123](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/misclick.jpg)


## LOAD-DEX

This category of malware can cause unaware service charges by bypassing a 2FA and completing a payment, too. However, different from “Misclick to pay”, the malicious behavior will be triggered directly after started.

![123](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/loaddex.jpg)

## Account&Password stealer

This category of malware can steal victim’s privacy, such as the account information and login password to digital property, by providing a fake login/payment interface.

![123](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/accountstealer-attackchain.jpg)

## Automatically send messages

This category of malware can cause unaware service charges by bypassing 2FA and completing a payment.

![123](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/message.jpg)

## Remote control

This category of malware can perform SMS-based malicious behaviors with remote control commands. 

![123](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/remotecontrol.jpg)

## Fission application

This category of malware can be spread to more devices efficiently by sending the download link to all contacts on victim’s device.

![123](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/flission.jpg)
