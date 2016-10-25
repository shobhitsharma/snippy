# Swippy

## Development

```bash
# Build the entire example and execute unit and integration tests plus lint check.
./gradler clean build

# Install the debug apk on the current connected device.
./gradler installDebug

# Execute domain and data layer tests (both unit and integration)
./gradler runUnitTests

# Execute espresso and instrumentation acceptance tests.
./gradler runAcceptanceTests
 ```