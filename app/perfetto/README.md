#### Tracing with Perfetto

- Checkout directory /perfetto
- Run the application on device/emulator
- Connect device/emulator via ADB
- Run command:
`./record_android_trace -c perfetto.config -o test-trace.perfetto-traceadb`

- After you're done playing with app, press command + C
- Once analysis is done, trace details will be automatically launched in one of the Browsers installed in your machine.