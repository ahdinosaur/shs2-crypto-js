# SHS2 Crypto

An implementation of the crypto in the [secret-handshake](https://github.com/ahdinosaur/secret-handshake) protocol version 2, with a focus on readibility.

This module provides functions `createMsg1`, `verifyMsg1` and so on. These are documented in `client.js` and `server.js`. See `test/test.js` for example usage.

Run `npm test` to run the shs1 integration tests on this implementation. For this to work, `test/client.js` and `test/server.js` need to be executable.
