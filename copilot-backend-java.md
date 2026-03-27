# Spring Boot Rules

- Use DTOs
- Validate input
- No dynamic SQL
- Secure APIs

BAD:
return entity;

GOOD:
return DTO;
