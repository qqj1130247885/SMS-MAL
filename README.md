# SMS-MAL
These data are related to paper"An Empirical Study on Malicious SMS-Based Apps".

In this work, we summarize 7 fine-grain categories for SMS-based malware and the general attack chain for each category. To contribute to relevant research topics, such as AI-based interpretable malicious behavior classification, we release 56 malware samples and their corresponding attack chains as a benchmark. We hope they can be used as a fundamental dataset in future SMS-based malware research.

The following figure shows a brief description about the potential harm,characterization-based family label, discoverability, and the number of collected cases.

![fig.1](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/information.png)

The following is a brief introduction about the 7 categories and their corresponding attack chains.

## Message stealer

This category of malware can steal victim’s messages by secretly sending them from the infected device to a remote server.
![fig.1](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/messageStealer.jpg)


## Misclick to pay

This category of malware can cause unaware service charges by bypassing a two-factor authentication (2FA), such as typing in a verification code by user, and completing a subscription payment. 

![fig.2](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/misclick.jpg)


## LOAD-DEX

This category of malware can cause unaware service charges by bypassing a 2FA and completing a payment, too. However, different from “Misclick to pay”, the malicious behavior will be triggered directly after started.

![fig.3](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/loaddex.jpg)

## Account&Password stealer

This category of malware can steal victim’s privacy, such as the account information and login password to digital property, by providing a fake login/payment interface.


![fig.4](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/accountstealer-attackchain.jpg)

## Automatically send messages

This category of malware can cause unaware service charges by bypassing 2FA and completing a payment.

![fig.5](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/message.jpg)

## Remote control

This category of malware can perform SMS-based malicious behaviors with remote control commands. 

![fig.6](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/remotecontrol.jpg)

## Fission application

This category of malware can be spread to more devices efficiently by sending the download link to all contacts on victim’s device.


![fig.7](https://github.com/qqj1130247885/SMS-MAL/blob/main/image/flission.jpg)
