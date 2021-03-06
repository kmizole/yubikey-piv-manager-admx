# Administrative Template for YubiKey PIV Manager

## Introduction
This ADMX administrative template allows administrators to easily deploy configuration of the [YubiKey PIV Manager](https://github.com/Yubico/yubikey-piv-manager) through Active Directory Group Policy. It can also be used on standalone computers to unlock some features of the PIV Manager that are disabled by default, like controlling the Pin and Touch policies. The affected registry locations are documented at [Yubico's website](https://developers.yubico.com/yubikey-piv-manager/Settings_and_Group_Policy.html).

![Group Policy Editor Screenshot 1](https://github.com/MichaelGrafnetter/yubikey-piv-manager-admx/raw/master/screenshot.png)

![Group Policy Editor Screenshot 2](https://github.com/MichaelGrafnetter/yubikey-piv-manager-admx/raw/master/screenshot2.png)

## Installation
Just copy the ADMX and ADML files into the [local or central ADMX store](https://msdn.microsoft.com/en-us/library/bb530196.aspx#manageadmxfiles_topic2).

## TODO
- Change the registry value locations from unmanaged to managed paths. This will prevent registry tattooing and allow to define "Computer Configuration" policies in addition to "User Configuration" policies.
