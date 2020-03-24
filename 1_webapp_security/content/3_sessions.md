# Sessions

Sessions enable the application to maintain user-specific state, while users interact with the application. For example, sessions allow users to authenticate once and remain signed in for future requests.

[HTTP Session](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#HTTP_session)

## Exercise

1. Login to a web application of your choice
1. Copy the created cookie and/or the local storage data
1. Open another browser or same browser in private mode
1. Access the same application and store the copied data for the given site

## Attacks

- Session Hijacking
- Replay Attacks for CookieStore Sessions
- Session Fixation

## Countermeasures

- Session Reset after successful login
- Session Expiry
