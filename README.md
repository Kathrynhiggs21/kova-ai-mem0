# KOVA Memory Adapter

Experimental memory-provider adapter for KOVA OS.

## Scope

This repository is reserved for memory synchronization and provider-specific persistence behavior. It must not become a second KOVA control plane, dashboard, assistant shell, or canonical user-data store.

Canonical architecture and repository roles live in [Kathrynhiggs21/Kova-ai-SYSTEM](https://github.com/Kathrynhiggs21/Kova-ai-SYSTEM).

## Data boundary

Google Drive remains the canonical user-controlled file layer. A memory provider may store derived conversational context only after retention, deletion, privacy, export, and provider-failure behavior are documented and tested.

Never commit provider keys, user content, access tokens, or production exports.

## Status

Catalogued but disabled in the KOVA runtime registry. This placeholder is not production-ready.
