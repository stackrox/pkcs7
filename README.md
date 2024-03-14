# stackrox/pkcs7

pkcs7 implements parsing and creating signed and enveloped messages. Documentation on
[GoDoc](http://godoc.org/github.com/fullsailor/pkcs7).

This is a fork of [fullsailor/pkcs7](https://github.com/fullsailor/pkcs7). It adds support
for more hash algorithms, see
[stackrox/pkcs7/commit/cfdb0aa](https://github.com/stackrox/pkcs7/commit/cfdb0aa4717989152fdcc58bca185659e6308f5a).
The original project is apparently unmaintained and our upstream contribution
[fullsailor/pkcs7/pull/42](https://github.com/fullsailor/pkcs7/pull/42) has not been
accepted (yet).

Another possible and maintained alternative to [fullsailor/pkcs7](https://github.com/fullsailor/pkcs7)
is [digitorus/pkcs7](https://github.com/digitorus/pkcs7) but it does not seem to handle
some RSA algorithms in `getHashForOID()` this fork does. It is unclear if this is important
but this fork served us well so we'll favor using it for the time being.

[![GoDoc](https://godoc.org/github.com/fullsailor/pkcs7?status.svg)](https://godoc.org/github.com/fullsailor/pkcs7)
