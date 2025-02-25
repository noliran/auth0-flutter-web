# [0.0.1-alpha.4] - 2021-03-21

## Added
- options for `getTokenWithPopup` (`GetTokenWithPopupOptions` and `PopupConfigOptions`)
- `Auth0ClientOptions` (align with parameter of `createAuth0Client`)
- warning for missing mandatory fields

## Changed
- parameter of `createAuth0Client` from `Auth0CreateOptions` to `Auth0ClientOptions`

## Removed
- `Auth0CreateOptions`

# [0.0.1-alpha.3] - 2021-03-13

## Added
- options for `LoginWithPopup` (`PopupLoginOptions` and `PopupConfigOptions`)
- `BaseLoginOptions`
- scope for login in example

# [0.0.1-alpha.20210224] - 2021-02-24

## Added
- invoke `loginWithPopup`, `logout`, `getUser` and `getIdTokenClaims` in `Auth0` object in dart
- show name and avatar returned from Google in example
- logout button in example

# [0.0.1-alpha] - 2021-02-13

## Added
- invoke `createAuth0Client` from dart with limited options in `Auth0CreateOptions` in dart
- part of `Auth0` object in dart
