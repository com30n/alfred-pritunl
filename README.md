# Alfred OTP

Alfred workflow to generate OTP secured in keychain.

## How to

- add a new OTP service and token: `otp+ [service] [token]`
![add new token](/doc/otp+.png)

- generate OTP for a service: `otp [service]`. OTP will be copied to clipboard
![generate otp](/doc/otp.png)

## Prerequisites

- Install `oathtool` via `brew install oath-toolkit`
- Keychain

## Credits

Forked from https://github.com/caalberts/alfred-otp
