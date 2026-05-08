# LiveKit (livekit)

LiveKit is an open-source WebRTC platform with a managed Cloud offering. APIs cover Rooms, Egress (recording, RTMP), Ingress (RTMP/SRT/WHIP), SIP (telephony), and Agents (LLM voice agents). Server APIs use Twirp (HTTP+Protobuf).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/livekit/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- Realtime, WebRTC, Audio, Video, Open Source, AI Agents, Voice, Cloud

## APIs
- **LiveKit RoomService API** - Twirp/Protobuf
- **LiveKit Egress API** - recording / streaming
- **LiveKit Ingress API** - RTMP/SRT/WHIP ingest
- **LiveKit SIP API** - PSTN bridging
- **LiveKit Agents API** - voice/multimodal AI agents

All APIs reachable at the project's `https://your-project.livekit.cloud` host (or your self-hosted equivalent).

## Notes on OpenAPI
LiveKit defines its server APIs in Protobuf (Twirp), not OpenAPI. Canonical definitions live in `livekit/protocol` GitHub repository.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Portal](https://livekit.io/)
- [Documentation](https://docs.livekit.io/)
- [Pricing](https://livekit.io/pricing)
- [GitHub](https://github.com/livekit)
- [License](https://github.com/livekit/livekit/blob/master/LICENSE)
- [Plans](plans/livekit-plans-pricing.yml) - partially reconciled
- [RateLimits](rate-limits/livekit-rate-limits.yml) - partially reconciled
- [FinOps](finops/livekit-finops.yml) - reconciled FOCUS-aligned

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
