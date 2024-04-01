# iCloud for Windows

With iCloud for Windows, you can access your photos, videos, mail, calendar, files, and other important information on your Windows PC.

- https://www.microsoft.com/store/apps/9PKTQ5699M62

## Endpoints

The list of iCloud allowed domains was derived from their documentation, which can be found at:

https://support.apple.com/en-us/101555

| Endpoint                  | Documented? | Purpose                                                   |
|---------------------------|-------------|-----------------------------------------------------------|
| setup.icloud.com          | ✔️          | Required to log in with an Apple ID                       |
| certs.apple.com           | ✔️          | Certificate validation                                    |
| crl.entrust.net           | ✔️          | Certificate validation                                    |
| crl3.digicert.com         | ✔️          | Certificate validation                                    |
| crl4.digicert.com         | ✔️          | Certificate validation                                    |
| ocsp.apple.com            | ✔️          | Certificate validation                                    |
| ocsp.digicert.com         | ✔️          | Certificate validation                                    |
| ocsp.entrust.net          | ✔️          | Certificate validation                                    |
| ocsp2.apple.com           | ✔️          | Certificate validation                                    |
| valid.apple.com           | ✔️          | Certificate validation                                    |
| *.push.apple.com          | ✔️          | Push notifications                                        |
| configuration.apple.com   | ❔          | Documented to exist in macOS only, but is used on Windows |
| *.apple-cloudkit.com      | ✔️          | iCloud services                                                         |
| *.apple-livephotoskit.com | ✔️          | iCloud services                                                         |
| *.cdn-apple.com           | ✔️          | iCloud services                                                         |
| *.gc.apple.com            | ✔️          | iCloud services                                                         |
| *.icloud.com              | ✔️          | iCloud services                                                         |
| *.icloud.apple.com        | ✔️          | iCloud services                                                         |
| *.icloud-content.com      | ✔️          | iCloud services                                                         |
