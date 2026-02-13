Paraparamiko provides deterministic ProxyJump resolution and multi-hop `Transport` construction for Paramiko, driven directly by the OpenSSH client configuration of the user. It implements structured `Include` and `Match` parsing, explicit hop-by-hop authentication orchestration and strict host key verification to prevent accepting unknown or untrusted hosts. It focuses on predictable transport stacks and controlled SSH behavior without modifying Paramiko internals.

It integrates with Bitwarden and KeePassXC for credential retrieval, enabling automated handling of password, keyboard-interactive and 2FA flows. It supports agent-based authentication and direct key loading, including passphrase-protected and unprotected keys, resolving authentication methods per hop based on configuration and available credentials.

Stretch goals include X11 forwarding and related channel management features.
