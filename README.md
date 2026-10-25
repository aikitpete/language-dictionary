# language-dictionary

[![License](https://img.shields.io/github/license/aikitpete/language-dictionary)](LICENSE) ![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white) ![Swing](https://img.shields.io/badge/Swing-5382A1) ![Status](https://img.shields.io/badge/status-archived-lightgrey)

Java client-server dictionary and vocabulary trainer: a Swing desktop client talks to a server that stores vocabulary and user data in flat files.

- **Server** (`packages/server`): vocabulary lookup, user list, session handling over sockets, file-based storage (`vocab.txt`, `users.dat`).
- **Client** (`packages/client`): login, search, vocabulary trainer and statistics charts.

**Status:** archived university-era project. The bundled Google Translate client targets a retired API, so the translate feature no longer works.

## Licence
MIT, see [LICENSE](LICENSE). The client bundles two third-party libraries, `charts4j-1.3.jar` and `google-api-translate-java-0.95.jar`, which keep their own licences (see [NOTICE.md](NOTICE.md)).
