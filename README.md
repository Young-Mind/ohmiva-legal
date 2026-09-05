# Ohmiva Legal

Public legal-information site for the Android app **Ohmiva**.

## Draft status

The repository is intentionally **not ready for production** yet. The HTML pages contain:

- `RELEASE_REQUIRED_PROVIDER_NAME`
- `RELEASE_REQUIRED_PROVIDER_ADDRESS`
- `RELEASE_REQUIRED_PROVIDER_EMAIL`

and a visible draft banner plus `noindex,nofollow`.

Before enabling this site for the Play Store:

1. replace all provider placeholders,
2. remove the draft banner and robots noindex tags,
3. enable GitHub Pages from `main` / root,
4. verify all public HTTPS URLs,
5. update the Ohmiva app's `ReleaseLegalConfig.kt` with those URLs,
6. perform the final legal review.

No analytics, advertising, external fonts or tracking scripts are used.
