# README

# Contents

- Introduction
- Prerequisites
- Installing and configuring the module
- License

# Introduction

This Cubecart module provides an easy method to integrate with the payment gateway.
 - The httpdocs directory contains the files that need to be uploaded to the root directory of where Cubecart is installed
 - Supports CS Cart versions: **4.x+**

# Prerequisites

- The module requires the following prerequisites to be met in order to function correctly:
    - For a full list of requirements please see: https://www.cubecart.com/hosting-requirements
    - SSL **NB: HTTPS is expected to be in place as the payment gateway will respond over SSL when integrating directly. Failure to provide an environment where HTTPS traffic is possible, will result in the 3DSv2 payment flow failing***

> Please note that we can only offer support for the Module itself. While every effort has been made to ensure the payment module is complete and bug free, we cannot guarentee normal functionality if unsupported changes are made.

# Installing and configuring the module

1. Copy the contents of the httpdocs into your root directory of CubeCart. If you are prompted to overwrite or merge files, select 'Yes' to all.
2. Login to the Admin panel of your CubeCart Shop.
3. Select 'Payment Gateway' under the 'Module' subheading in the left hand menu.
4. Look for CardStream and select the checkbox to the left of the logo. Scroll down and click save.
5. From the same screen, select the edit icon to the right of the CardStream module. Ensure that the 'Status' and 'Default' boxes are checked. Your payment gateway URL should correctly be set to 'https://gateway.cardstream.com/hosted/' by default. Fill in the relevant information in the boxes shown and select 'save'.
6. Your CardStream payment module is now installed!

License
----
MIT