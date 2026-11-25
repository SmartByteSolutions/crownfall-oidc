# crownfall-oidc

Public JSON Web Key Set used by Epic Online Services to verify Crownfall Online account ID tokens
(OpenID identity provider for EOS Connect / Easy Anti-Cheat).

- `jwks.json` contains **public keys only** (RSA, RS256).
- Rotating the key: add the new key to `jwks.json`, keep the old one until issued tokens expire (10 min).
