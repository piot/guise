<h1 align="center">
    <img src="docs/images/logo.svg" width="256" />
</h1>

## Introduction

> Guise: outward appearance of someone, which is often different from their real nature.

A simplified authentication system. Designed for internal development and testing, do not use in production.

* [guise-serialize](https://github.com/piot/guise-serialize-c). Serialization of the protocol.
* [guise-client-c](https://github.com/piot/guise-client-c). Used for user authentication in an application.
* [guise-server-lib](https://github.com/piot/guise-server-lib). The server part. Can be embedded in another application.
* [guise-daemon](https://github.com/piot/guise-daemon). Guise server executable designed for deployment. Depends on:
  * [udp-server-c](https://github.com/piot/udp-server-c). receiving and sending UDP datagrams.
* [guise-session-client-c](https://github.com/piot/guise-session-client-c). Only used for other services, e.g. the [Relay Server](https://github.com/piot/relay-server-lib), to verify user session IDs.

Read more about the [Guise Protocol](https://github.com/piot/guise-serialize-c/blob/main/docs/index.adoc).
