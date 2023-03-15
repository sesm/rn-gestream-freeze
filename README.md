# rn-gestream-freeze
Minimal example for https://github.com/facebook/hermes/issues/928

Steps to reproduce:

1. `yarn && yarn android`
2. App in emulator becomes unresponsive with 100% JS thread load inside `Error.captureStackTrace`.
