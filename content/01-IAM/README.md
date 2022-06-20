<h3 style='color:yellowgreen'>IAM Policies Structure </h3>

<img src='../../assets/IAM_Policies_structure.png'>


<h3 style='color:yellowgreen'>MFA Devices Options in AWS</h3>

- Virtual MFA devices
    - Google Authenticator ( phone Only )
    - Authy (Multi Device)

 they have support multiple tokens on a single device. 
- Universal 2nd Factor (U2F) Security Key 
    - YubiKey by Yubico (3rd party)
 support for multiple root and IAM users using a single security key. 3
- Hardware Key Fob MFA Device 
    - Provided by Gemalto (3rd party)

- Hardware Key Fob MFA Device for AWS GovCloud(US)
    - Provided by SurePassID (3rd party)
if you are using a cloud of government in the the US.