# Extensus

Extensus is a pair of lightweight scripts designed to inventory installed Visual Studio Code extensions on Windows and macOS devices, generating local log files ready for centralised collection.

# Why Extensus?

Visual Studio Code is the most widely used code editor in the world, with millions of developers using it every day. Its extensive extension ecosystem is a key reason for its success, offering support for many programming languages, linters, themes and advanced development tools.

However, this flexibility introduces a significant software supply-chain risk. Many extensions can execute code with the same user privileges as Visual Studio Code itself, potentially exposing development environments to malicious or compromised extensions.

Extensus was created to give security engineers a simple, lightweight way to inventory installed extensions across their device fleet, with the goal of improving visibility into extension usage to support software supply-chain security assessments and help organisations maintain secure development environments.
