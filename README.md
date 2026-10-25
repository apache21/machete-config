# machete-config

Signed backend address for the Machete DGX app (`lib/core/config/backend_config.dart`).
`backend.json` = `{"payload": "<json>", "sig": "<ed25519, base64>"}`. The app verifies the
signature with a key compiled into it, so editing this file without the private key does nothing.
