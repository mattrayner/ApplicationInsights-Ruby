# Changelog

This file needs to be updated with every significant pull request. It is used to write down release notes.

## Version 0.6.0
* Expose request id to parent Rack application when using `ApplicationInsights::Rack::TrackRequest` middleware through `env['ApplicationInsights.request.id']`

## Version 0.5.5
* Add some basic logging when failed to send telemetry to the server
* Add timestamp as an optional parameter to the TelemetryChannel::write() method

## Version 0.5.4

Changelog started after this release. 