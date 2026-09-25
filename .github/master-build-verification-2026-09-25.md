# Master build verification

Temporary no-code marker used to trigger the existing GitHub Actions `build`
workflow against the unchanged upstream `master` source on 2026-09-25.

The marker intentionally changes no production code, tests, Gradle configuration,
or dependencies. It exists only so the fork runs the current workflow/runner/JDK
against the same source revision used as the base of the integration-test PoC.
