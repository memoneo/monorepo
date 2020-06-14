# Memoneo

Memoneo is a mobile app that I'm building to track my personal goals, progress, general state of mind, events etc. via speech and text. 

My main motivation is to control my own data and adjust the tracking for my specific personal needs.

## Repos
### api
The REST API backend for Memoneo. This repo is private. Runs on Heroku.

### asr
The API which provides an endpoint to transcribe speech to text. The API uses Deepspeech.rs (0.61). For now the performance is not good enough which is why I don't use it personally for now. Deepspeech 0.7 has been released and improved the performance a bit. So maybe there's promise.

### app-mobile
The React Native mobile app which I use to track data points of my life. This repo is private.

### site
A very basic demo promotional page.

Can be visited at: https://memoneo.gitlab.io/site

### common
Contains components and types that may be shared in the future. The consumers must be configured to transpile the library.

## Todo
- Documentation
- Tests
- Onboarding
- Publishing
- User tests
- iOS Version
- ...

## Tech stack
### Frontend
- React Native
- Typescript
- Redux

### Backend
- Rust
    - Deepspeech.rs
- Kotlin
- PostgreSQL
- JWT
- vertX

### Hosting
- Heroku
- Gitlab Pages
