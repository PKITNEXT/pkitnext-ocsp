# PKITNEXT LABS – OCSP Tester

Free GUI tool for testing OCSP responders (RFC 6960) – Windows and macOS.

## Download

➡ [**Releases**](https://github.com/PKITNEXT/pkitnext-ocsp/releases)

| Platform | File |
|---|---|
| Windows x64 | `pkitnext-ocsp-tester.exe` (portable, no installer needed) |
| macOS Apple Silicon | `pkitnext-ocsp-tester-macos-arm64.zip` |
| macOS Intel | `pkitnext-ocsp-tester-macos-intel.zip` |

## Features

- Load end-entity and issuer certificate (PEM or DER format)
- Or enter a serial number directly – **hex** (`01:ab:cd`) or **decimal** (`123456`)
- Test multiple OCSP responders in parallel
- Displays certificate status: **good** / **revoked** / **unknown**
- Shows serial number in both hex and decimal (copy button)
- Response time measurement and raw response bytes
- Demo certificates with one-click refresh

## Quick Start

1. Download and run `pkitnext-ocsp-tester.exe`
2. Load end-entity + issuer certificate **or** switch to “Serial number (hex dec)” mode
3. Enter one or more OCSP responder URLs
4. Click **▶ Run OCSP Tests**

## Requirements

- **Windows:** Windows 10 / Server 2016 or newer (x64)
- **macOS:** macOS 11 or newer (Apple Silicon or Intel)

## About

Built by **PKITNEXT LABS** · [www.pkitnext.de](https://www.pkitnext.de)
