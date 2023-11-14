# Changelog
All notable changes to `cnj-monitoring-downstream` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [4.1.0] - 2023-11-14
### Added
- Tagging of git branch
### Changed
- Upgraded to helm-maven-plugin version 5.0.0
- Now a helm chart is packaged and pushed as an artifact during the commit-stage build
- Now the helm chart is pulled before deploying during the integration-test-stage build

## [4.0.0] - 2023-06-09
### Changed
- moved to new AWS CodeBuild build pipeline
- moved to new CloudTrain EKS cluster
- upgraded everything

## [3.0.0] - 2023-02-23
### Changed
- upgraded to Java 17
- upgraded to Spring Boot 3.0.2
- consolidated with hello world use case

## [2.3.0] - 2022-08-12
### Changed
- upgraded to cnj-common-observability-spring 0.4.0 to have consolidated Undertow metric names
- name of Spring Boot application JAR is using suffix `-spring` now

## [2.2.0] - 2022-07-29
### Added
### Changed
- upgraded to cnj-common-obervability-spring 0.3.0 to have support of Undertow metrics

## [2.1.0] - 2022-03-09
### Added
### Changed
- re-release after repo split
