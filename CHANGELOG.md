# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.2]

### Changed

- Remove traces from the signals list

## [0.3.1]

### Added

- Explicit RollingUpdate strategy for zero-unavailable deploys.
- PodDisruptionBudget enabled by default.
- Configurable `preStop` hook and termination grace period for pod draining.

## [0.3.0]

### Added

- OTEL collector sidecar that sends telemetry to optional customer endpoint.

## [0.2.1]

### Changed

- Image tag is now a required input. Default to `latest` has been removed.

## [0.2.0]

### Added

- Support for Azure AKS.
- Support for generic Kubernetes.

## [0.1.1]

### Added

- Support for AWS EKS.
