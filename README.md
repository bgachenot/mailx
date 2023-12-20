Mailx
======

[![Go Report Card](https://goreportcard.com/badge/github.com/bgachenot/mailx)](https://goreportcard.com/report/github.com/bgachenot/mailx)
[![Go Reference](https://pkg.go.dev/badge/github.com/bgachenot/mailx.svg)](https://pkg.go.dev/github.com/bgachenot/mailx)
[![GitHub License](https://img.shields.io/github/license/bgachenot/mailx)](LICENSE)
[![codecov](https://codecov.io/gh/bgachenot/mailx/branch/main/graph/badge.svg?token=GXGTBNC94F)](https://codecov.io/gh/bgachenot/mailx)

Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`.

Compatibility
------

- Compatible with go 1.16+

Features
------

Gomail supports:

- Attachments
- Embedded files
- HTML and text templates
- TLS connection and STARTTLS extension
- Sending multiple emails with the same SMTP connection

Installing
------

go mod:

```shell
go get github.com/bgachenot/mailx
```

Example
------

- See [example](example_test.go)

Changes
------

See the [CHANGES](CHANGE.md) for changes.

License
------

See the [LICENSE](LICENSE) for Rights and Limitations (MIT).

toto