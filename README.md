<div id="header" align="center">

[![GitHub issues](https://img.shields.io/github/issues-raw/BroadcomMFD/rexx-language-support)](https://github.com/BroadcomMFD/rexx-language-support/issues)
[![slack](https://img.shields.io/badge/chat-on%20Slack-blue)](https://join.slack.com/t/che4z/shared_invite/zt-37ewynplx-wCoabaIDxN6Ofm4_XBinZA)
[![Code4z](https://img.shields.io/badge/Code4z-marketplace-cc092f)](https://marketplace.visualstudio.com/search?term=code4z&target=VSCode)

</div>

# Rexx Language Support

The Rexx Language Support plugin leverages the language server protocol to provide syntax awareness, syntax coloring and autocomplete features for Rexx code. Files with the extensions `.rex`, `.rexx`, `.zrx` and `.rxj` are recognised as Rexx files.

<img align="left" alt="This extension is part of the Code4z experience" width="80" height="82" src="https://raw.githubusercontent.com/BroadcomMFD/code4z/refs/heads/main/icon5.png" />

Rexx Language Support is part of the [Code4z](https://techdocs.broadcom.com/code4z) experience from Broadcom, which offers a modern experience for mainframe application developers. To get started with Code4z, check out our foundational [extension pack](https://marketplace.visualstudio.com/items?itemName=broadcomMFD.code4z-extension-pack).

<br />

## Address Software Requirements

* Java version 11 or higher.

## Features

The Rexx Language Support plugin enables the following features:

### Autocomplete

Autocomplete speeds up the coding process by suggesting the most likely keywords to follow existing code. The plugin provides autocomplete functionality for all Rexx keywords.

![Autocomplete](https://raw.githubusercontent.com/BroadcomMFD/rexx-language-support/3680907e86029337ca295da877f449f1ce6622e5/images/rexx-autocomplete.gif)

You can customize the case used by the autocomplete feature. In the REXX Language Support extension settings, change the **Rexx-lsp > Keyword: Textcase** parameter to one of the following:

* **AUTO**
  * Automatically detects the case used by other keywords in the code. 
* **LOWER_CASE**
  * Suggests keywords in lower case.
* **TITLE_CASE**
  * Suggests keywords in title case.
* **UPPER_CASE**
  * Suggests keywords in upper case. 

### Syntax Check

This feature checks for mistakes and errors in Rexx code. The syntax check feature reviews the whole content of the code and underlines any errors.

![Autocomplete](https://raw.githubusercontent.com/BroadcomMFD/rexx-language-support/3680907e86029337ca295da877f449f1ce6622e5/images/rexx-syncheck.gif)

### Syntax Coloring

Contrasting colors are used in displayed code for ease of identifying and distinguishing keywords, variables, operators, operands and comments.

### Customize Maximum Record Length 

REXX Language Support enables you to customize the maximum record length. The default maximum record length is 80 characters. Any lines that are longer than the maximum record length are marked as errors.

To edit the maximum record length, open the REXX Language Support extension settings and edit the value **Rexx-lsp: Max Line Length**. Specify **0** to deactivate the feature.

You can also change the maximum record length and trim records using the Quick Fix functionality:

1. Hover over a line marked as an error for exceeding the maximum record length.
2. Select **Quick Fix...**
3. Select from the following options:
    *  To trim all characters exceeding the maximum record length, select **Trim line to max length**
    *  To set the maximum record length to a predefined value, select the **Set Max Length** option.
    *  To set the maximum record length to 0 and disable the feature, select **Deactivate Max Length**.

![MaxLength](https://raw.githubusercontent.com/BroadcomMFD/rexx-language-support/6a73e1f1c7bd6247a84f95760ab2003b5cbabf06/images/rexx-maxLength.gif)

## Privacy Notice
The extensions for Visual Studio Code developed by Broadcom Inc., including its corporate affiliates and subsidiaries, ("Broadcom") are provided free of charge, but in order to better understand and meet its users’ needs, Broadcom may collect, use, analyze and retain anonymous users’ metadata and interaction data, aggregate such data with similar usage data of other Broadcom customers. Please, find more detailed information in [License and Service Terms & Repository](https://www.broadcom.com/company/legal/licensing).

For this data collection is used built-in Microsoft VS Code Telemetry, which [can be disabled, if you do not want to send usage data](https://code.visualstudio.com/docs/getstarted/telemetry#_disable-telemetry-reporting).

**The current release of Rexx Language Support collects anonymous data for the following events:**
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