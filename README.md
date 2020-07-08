[![GitHub issues](https://img.shields.io/github/issues-raw/BroadcomMFD/rexx-language-support)](https://github.com/BroadcomMFD/rexx-language-support/issues)

# LSP for Rexx

The LSP for Rexx plugin leverages the language server protocol to provide syntax awareness, syntax coloring and autocomplete features for Rexx code. Files with the extensions `.rex`, `.rexx`, `.zrx` and `.rxj` are recognised as Rexx files.

## Prerequisites

* Java version 11 or higher.

## Features

The LSP for Rexx plugin enables the following features:

### Autocomplete

Autocomplete speeds up the coding process by suggesting the most likely keywords to follow existing code. The plugin provides autocomplete functionality for all Rexx keywords.

![Autocomplete](/images/rexx-autocomplete.gif)

### Syntax Check

This feature checks for mistakes and errors in Rexx code. The syntax check feature reviews the whole content of the code and underlines any errors.

![Autocomplete](/images/rexx-syncheck.gif)

### Syntax Coloring

Contrasting colors are used in displayed code for ease of identifying and distinguishing keywords, variables, operators, operands and comments.

# Privacy Notice
The extensions for Visual Studio Code developed by Broadcom Inc., including its corporate affiliates and subsidiaries, ("Broadcom") are provided free of charge, but in order to better understand and meet its users’ needs, Broadcom may collect, use, analyze and retain anonymous users’ metadata and interaction data, aggregate such data with similar usage data of other Broadcom customers.

For this data collection is used built-in Microsoft VS Code Telemetry, which can be disabled, if you do not want to send usage data.

**Current release of REXX Language Support will collect anonymous data for the following events:**
* Activation of this VS Code extension
* Use of autocomplete feature
* Count of lines of opened REXX file (Performance)
* Parsing time (Performance)

**Each such event is logged with the following information:**
* Event time
* Operating system and version
* Country or region
* Anonymous user and session ID
* Version numbers of Microsoft VS Code and REXX Language Support
