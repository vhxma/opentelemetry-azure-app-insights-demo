This is the original demo from OpenTelemetry: https://github.com/open-telemetry/opentelemetry-dotnet-instrumentation/tree/main/examples/demo

To ensure the demo works, please follow these steps:
- In otel-config-update.yaml, please update the azuremonitor exporter with the correct connection string (copy and paste from application insights in portal) – is line 33
- Also update line 57 of the Program.cs file for the Service (Service/Program.cs) to an API you can GET successfully from the Service container
