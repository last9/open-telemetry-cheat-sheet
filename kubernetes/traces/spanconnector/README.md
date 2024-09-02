# Convert OpenTelemetry Traces to Metrics using SpanConnector

This directory contains examples and configurations for converting OpenTelemetry traces to metrics using the SpanConnector processor.

For a detailed explanation and guide, check out our blog post:
[Convert OpenTelemetry Traces to Metrics using SpanConnector](https://last9.io/blog/convert-opentelemetry-traces-to-metrics-using-spanconnector/)

## Contents

- [spanconnector-config.yaml](spanconnector-config.yaml): Configuration example for the SpanConnector processor

## Usage

To use this configuration, you need to have the OpenTelemetry Collector deployed with the SpanConnector processor. You can apply this configuration using:

```bash
otelcol --config spanconnector-config.yaml