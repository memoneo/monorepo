<p align="center">
    <br>
    <img src="https://memoneo.gitlab.io/site/static/logo.svg" width="128"/>
    <br>
<p>

# Memoneo - mood tracker and diary

Memoneo is a mobile app that I'm building to track my personal goals, progress, general state of mind, events etc. via speech and text. My main motivation is to control my own data and adjust the tracking for my specific personal needs.

<br>
<img src="https://memoneo.gitlab.io/site/static/demo.jpg" width="300" />

## Repos
### api
The vert.x REST API backend for Memoneo. This repo is private. Runs on Heroku.

### asr
The warp API which provides a single endpoint to transcribe speech to text. The API uses Deepspeech.rs (0.61). For now the model performance is not good enough which is why I don't use it personally for now. Deepspeech 0.7 has been released and improved the performance a bit (but not by a margin which is sufficient). So maybe there's promise in the future.

### app-mobile
The React Native mobile app which I use to track data points of my life. This repo is private.

### site
A very basic demo promotional page. Not optimized for mobile.

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
