# Goaly — Project Status

## Implemented in the private project

- Expo / React Native mobile application
- NestJS backend
- Prisma/PostgreSQL persistence
- guest/local mode
- authenticated API mode
- financial-domain screens/workflows
- multilingual UI support
- improved empty states and onboarding
- voice-assisted input path
- recommendation flow
- Google OAuth UI/integration code
- CI/test commands

## Verified in the documented UX phase

- mobile typecheck
- mobile lint
- **12/12 Jest tests**
- manual navigation review
- preview APK rebuild after native UI changes

## External / owner configuration still required

- correct Google OAuth project/client IDs
- DeepSeek API key for primary cloud AI mode
- payment-provider production credentials
- SES/email production configuration
- push-notification production credentials
- final physical-device validation

## Graceful degradation

Without a DeepSeek key, AI parsing can fall back to Ollama and then deterministic logic.

## Showcase rule

The public repository intentionally avoids exposing financial-domain implementation, environment configuration and authentication internals.
