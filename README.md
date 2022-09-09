# Small Basic for VS Code

This Visual Studio Code extension adds support for [**Microsoft's Small Basic**](http://smallbasic.com) language.

## Features

- Syntax highlighting
- Code snippets (e.g. `For ... EndFor`, `If ... Else ... EndIf`, ...)

## Installation

### From repository

Copy this folder to `%USERPROFILE%\.vscode\extensions` (on Windows) or `~/.vscode/extensions` (on Linux/ Mac) and restart VS Code.

### From VS Code Marketplace

Go to [Small Basic extension marketplace page](https://marketplace.visualstudio.com/items?itemName=alxnull.vscode-smallbasic).

## Changelog

See the [changelog](CHANGELOG.md) for details.

## Install UTXT syntax for VSCode

  $ rm -rf ~/.vscode/extensions/utxt
  $ cp -r utxt ~/.vscode/extensions

## Pattern types

          "enum": [
            "comment",
            "comment.block",
            "comment.block.documentation",
            "comment.line",
            "comment.line.double-dash",
            "comment.line.double-slash",
            "comment.line.number-sign",
            "comment.line.percentage",
            "constant",
            "constant.character",
            "constant.character.escape",
            "constant.language",
            "constant.numeric",
            "constant.other",
            "constant.regexp",
            "constant.rgb-value",
            "constant.sha.git-rebase",
            "emphasis",
            "entity",
            "entity.name",
            "entity.name.class",
            "entity.name.function",
            "entity.name.method",
            "entity.name.section",
            "entity.name.selector",
            "entity.name.tag",
            "entity.name.type",
            "entity.other",
            "entity.other.attribute-name",
            "entity.other.inherited-class",
            "header",
            "invalid",
            "invalid.deprecated",
            "invalid.illegal",
            "keyword",
            "keyword.control",
            "keyword.control.less",
            "keyword.operator",
            "keyword.operator.new",
            "keyword.other",
            "keyword.other.unit",
            "markup",
            "markup.bold",
            "markup.changed",
            "markup.deleted",
            "markup.heading",
            "markup.inline.raw",
            "markup.inserted",
            "markup.italic",
            "markup.list",
            "markup.list.numbered",
            "markup.list.unnumbered",
            "markup.other",
            "markup.punctuation.list.beginning",
            "markup.punctuation.quote.beginning",
            "markup.quote",
            "markup.raw",
            "markup.underline",
            "markup.underline.link",
            "meta",
            "meta.cast",
            "meta.parameter.type.variable",
            "meta.preprocessor",
            "meta.preprocessor.numeric",
            "meta.preprocessor.string",
            "meta.return-type",
            "meta.selector",
            "meta.structure.dictionary.key.python",
            "meta.tag",
            "meta.type.annotation",
            "meta.type.name",
            "metatag.php",
            "storage",
            "storage.modifier",
            "storage.modifier.import.java",
            "storage.modifier.package.java",
            "storage.type",
            "storage.type.cs",
            "storage.type.java",
            "string",
            "string.html",
            "string.interpolated",
            "string.jade",
            "string.other",
            "string.quoted",
            "string.quoted.double",
            "string.quoted.other",
            "string.quoted.single",
            "string.quoted.triple",
            "string.regexp",
            "string.unquoted",
            "string.xml",
            "string.yaml",
            "strong",
            "support",
            "support.class",
            "support.constant",
            "support.function",
            "support.function.git-rebase",
            "support.other",
            "support.property-value",
            "support.type",
            "support.type.property-name",
            "support.type.property-name.css",
            "support.type.property-name.less",
            "support.type.property-name.scss",
            "support.variable",
            "variable",
            "variable.language",
            "variable.name",
            "variable.other",
            "variable.parameter"
          ]

## Colors

  comment.line       = grey

  constant.numeric   = orange
  constant.character = orange
  constant.regexp    = orange

  emphasis           = "white"

  entity.name.class  = orange

  header             = "white"

  invalid.illegal    = "white"

  keyword.control    = lila
  keyword.operator   = lila

  markup.bold        = orange
  markup.deleted     = red
  markup.changed     = lila
  markup.heading     = red
  markup.inline.raw  = "white"
  markup.inserted    = green
  markup.italic      = lila - italic
  markup.list        = "white"
  markup.list.numbered = "white"
  markup.other       = "white"
  markup.quote       = orange
  markup.raw         = green
  markup.underline   = "white"

  meta.cast          = "white"
  meta.preprocessor  = "white"

  storage.type       = lila

  string.html        = green
  string.quoted      = green
  string.regexp      = blue
  string.xml         = green

  strong             = "white"

  support.class      = orange
  support.constant   = orange

  variable.name      = red
  variable.parameter = "white"



# Syntax highlight info

https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide

