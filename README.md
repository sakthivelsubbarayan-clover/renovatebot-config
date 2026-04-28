# Shared Renovate Configuration

This directory contains the shared Renovate configuration for projects within this repository or organization.

## Purpose

The goal of this shared configuration is to centralize and standardize Renovate settings, ensuring consistent dependency management practices across multiple projects. This helps in maintaining security, stability, and up-to-date dependencies efficiently.

## How to Use

To extend this shared configuration in your project's `renovate.json` file, add the following:

```json
{
  "extends": [
    "github>sakthivelsubbarayan-clover/renovatebot-config//.github"
  ]
}

```

## Key Configuration Aspects

This shared configuration includes:
*   `config:base`: A standard Renovate preset for common settings.
*   `automerge`: Configured to automatically merge minor and patch updates when possible.
*   `dependencyDashboard`: Enabled for a clear overview of dependency status.
*   `vulnerabilityAlerts`: Enabled to automatically create pull requests for known security vulnerabilities.

For more details on the specific settings, refer to the `renovate.json` file in this directory.
