# Alfred pritunl vpn

This alfred workflow allows you to connect to pritunl with 2f/OTP without having to enter your PIN every time.
![overview](/doc/overview.png)


## Prerequisites

- Pritunl app
- OTP secret from your pritunl profile
- Keychain


## How to

- Add or import a profile to your pritunl application

- It works fine with OTP workflows https://github.com/com30n/alfred-otp or https://github.com/caalberts/alfred-otp

- If you decided not to use the workflows you need to add your BASE32 OTP secrets to Keychain manually:
![add key to keychain](/doc/keychain.png)
  WARN: Account name have to have the following structure: name-otp

- If you are using one of OTP workflows, add the otp secret to keychain:
	- add a new OTP service and token: `otp+ [service] [token]`
	![add new token](/doc/otp+.png)

- type `vpc` (vpn connect) and choose the profile
![choose the profile](/doc/vpc.png)


- choose OTP secret that will using with the profile
![choose the otp](/doc/vpc-otp.png)


- enjoy

