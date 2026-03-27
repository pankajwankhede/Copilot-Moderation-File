# Logging Rules

NEVER LOG:
- password
- token
- sessionId

ALWAYS:
- trackingId

GOOD:
log.info("userId={} trackingId={}", mask(userId), trackingId);
