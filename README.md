# [ECMAScript](https://github.com/tc39/ecma262) proposals

* [Stage 0 Proposals](stage-0-proposals.md)
* [Finished Proposals](finished-proposals.md)
* [Inactive Proposals](inactive-proposals.md)

[ECMAScript Internationalization API Specification](ecma402/README.md) proposals

## Active proposals

Proposals follow [this process document](https://tc39.github.io/process-document/).
This list contains only stage 1 proposals and higher that have not yet been withdrawn/rejected, or become finished.

### Stage 3

| :rocket: | Proposal                                                                       | Author                                                                  | Champion                                                                | Tests                                          |
| -------- | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------- |
| :rocket: | [`Function.prototype.toString` revision][function-to-string]                   | Michael Ficarra                                                         | Michael Ficarra                                                         | [:white_check_mark:][tests-function-to-string] |
|          | [`globalThis`][globalThis]                                                     | Jordan Harband                                                          | Jordan Harband                                                          | [:white_check_mark:][tests-global]             |
|          | [`import()`][dynamic-import]                                                   | Domenic Denicola                                                        | Domenic Denicola                                                        | [:white_check_mark:][tests-dynamic-import]     |
|          | [Legacy RegExp features in JavaScript][regexp-legacy]                          | Claude Pache                                                            | Mark Miller<br />Claude Pache                                           | [:white_check_mark:][tests-regexp-legacy]      |
|          | [`BigInt`][bigint]                                                             | Daniel Ehrenberg                                                        | Daniel Ehrenberg                                                        | [:construction:][tests-bigint]                 |
|          | [`import.meta`][import-meta]                                                   | Domenic Denicola                                                        | Domenic Denicola                                                        | [:question:][tests-import-meta]                |
|          | [Private instance methods and accessors][private-methods]                      | Daniel Ehrenberg                                                        | Daniel Ehrenberg<br />Kevin Gibbons                                     | [:question:][tests-private-methods]            |
| :rocket: | [`Array.prototype.{flat,flatMap}`][flat]                                       | Brian Terlson<br />Michael Ficarra                                      | Brian Terlson<br />Michael Ficarra                                      | [:white_check_mark:][tests-flat]               |
|          | [Class Public Instance Fields & Private Instance Fields][class-fields]         | Daniel Ehrenberg<br />Kevin Gibbons                                     | Daniel Ehrenberg<br />Jeff Morrison<br />Kevin Smith<br />Kevin Gibbons | [:question:][tests-class-fields]               |
|          | [Static class fields and private static methods][static-class-features]        | Daniel Ehrenberg<br />Kevin Gibbons<br />Jeff Morrison<br />Kevin Smith | Shu-Yu Guo and Daniel Ehrenberg                                         |                                                |
|          | [`String.prototype.{trimStart,trimEnd}`][trims]                                | Sebastian Markbåge                                                      | Sebastian Markbåge                                                      | [:white_check_mark:][tests-trims]              |
|          | [`String.prototype.matchAll`][matchall]                                        | Jordan Harband                                                          | Jordan Harband                                                          | [:white_check_mark:][tests-matchall]           |
|          | [`Symbol.prototype.description`][symbol-description]                           | Michael Ficarra                                                         | Michael Ficarra                                                         | [:white_check_mark:][tests-symbol-description] |
|          | [`Object.fromEntries`][object-from-entries]                                    | Darien Maillet Valentine                                                | Jordan Harband<br />Kevin Gibbons                                       | [:white_check_mark:][tests-fromentries]        |
|          | [Well-formed `JSON.stringify`][well-formed-stringify]                          | Richard Gibson                                                          | Mathias Bynens                                                          | [:white_check_mark:][tests-well-formd-strngfy] |

### Stage 2

| :rocket: | Proposal                                                                       | Author                                   | Champion                                             |
| -------- | ------------------------------------------------------------------------------ | ---------------------------------------- | ---------------------------------------------------- |
|          | [Numeric separators][numeric_separators]                                       | Sam Goto<br />Rick Waldron               | Sam Goto<br />Rick Waldron                           |
|          | [`function.sent` metaproperty][function-sent]                                  | Allen Wirfs-Brock                        | Allen Wirfs-Brock                                    |
|          | [Decorators][decorators]                                                       | Daniel Ehrenberg                         | Yehuda Katz<br />Brian Terlson<br />Daniel Ehrenberg |
| :rocket: | [`throw` expressions][throw-expressions]                                       | Ron Buckton                              | Ron Buckton                                          |
|          | [`Atomics.waitAsync`][nonblocking]                                             | Lars Hansen                              | Shu-yu Guo<br />Lars Hansen                          |
|          | [Hashbang Grammar][hashbang-grammar]                                           | Bradley Farias                           | Bradley Farias                                       |
|          | [WeakRefs][weakrefs]                                                           | Dean Tribble                             | Dean Tribble                                         |
|          | [Top-level `await`][await]                                                     | Myles Borins                             | Myles Borins                                         |
|          | [`Function.prototype.toString()` censorship][censorship]                       | Domenic Denicola                         | Domenic Denicola                                     |
|          | [New Set methods][set-methods]                                                 | Michał Wadas                             | Sathya Gunasekaran                                   |
|          | [Realms][realms]                                                               | Caridy Patiño<br />Jean-Francois Paradis | Dave Herman<br />Mark Miller<br />Caridy Patiño      |
|          | [`ArrayBuffer.prototype.transfer`][buffer-transfer]                            | Domenic Denicola                         | Domenic Denicola                                     |
|          | [RegExp Match array offsets][regex-offsets]                                    | Ron Buckton                              | Ron Buckton                                          |
|          | [Sequence properties in Unicode property escapes][unicode-sequence-properties] | Mathias Bynens                           | Mathias Bynens                                                          |                                                |
|          | [`InterpreterDirective`][interpreter-directive]                                | Bradley Farias                           | Bradley Farias                                       |
|          | [Temporal][temporal]                                                           | Maggie Pint<br />Matt Johnson            | Maggie Pint<br />Brian Terlson                       |

### Stage 1

| :rocket: | Proposal                                                                                     | Author                                               | Champion                                               |
| -------- | -------------------------------------------------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------ |
|          | [`export v from "mod";` statements][export-from]                                             | Lee Byron                                            | Ben Newman<br />John-David Dalton                      |
| :rocket: | [Observable][observable]                                                                     | Jafar Husain                                         | Jafar Husain<br />Mark Miller                          |
|          | [Frozen Realms][frozen-realms]                                                               | Mark Miller<br />Chip Morningstar<br />Caridy Patiño | Mark Miller<br />Chip Morningstar<br />Caridy Patiño   |
|          | [`Math` Extensions][more-math]                                                               | Rick Waldron                                         | Rick Waldron                                           |
|          | [`of` and `from` on collection constructors][collection-of-from]                             | Leo Balter                                           | Leo Balter                                             |
|          | Generator arrow functions (`=>*`)                                                            |                                                      | Brendan Eich<br />Domenic Denicola                     |
|          | [`Promise.try`][try]                                                                         | Jordan Harband                                       | Jordan Harband                                         |
|          | [Optional Chaining][chaining]                                                                | Gabriel Isenberg<br />Claude Pache                   | Gabriel Isenberg                                       |
|          | [`Math.signbit`: IEEE-754 sign bit][signbit]                                                 | JF Bastien                                           | JF Bastien                                             |
|          | [Error stacks][stacks]                                                                       | Jordan Harband                                       | Jordan Harband                                         |
|          | [`do` expressions][do]                                                                       | Dave Herman                                          | Dave Herman                                            |
|          | [Float16 on TypedArrays, DataView, `Math.hfround`][float16s]                                 | Leo Balter                                           | Leo Balter                                             |
|          | Change `Number.parseInt`/`parseFloat` to not coerce `null`/`undefined`/`NaN` (repo link TBD) |                                                      | Brendan Eich                                           |
|          | [Binary AST][binary-ast]                                                                     | Shu-yu Guo                                           | Shu-yu Guo                                             |
|          | [Pipeline Operator][pipeline]                                                                | Daniel Ehrenberg                                     | Daniel Ehrenberg                                       |
|          | [Extensible numeric literals][extensible-literals]                                           | Daniel Ehrenberg                                     | Daniel Ehrenberg                                       |
|          | [First-class protocols][protocols]                                                           | Michael Ficarra                                      | Michael Ficarra                                        |
|          | [Nullish coalescing Operator][nullish-coalescing]                                            | Gabriel Isenberg                                     | Gabriel Isenberg                                       |
|          | [Partial application][partial-application]                                                   | Ron Buckton                                          | Ron Buckton                                            |
|          | [Cancellation API][cancel-api]                                                               | Ron Buckton                                          | Ron Buckton & Brian Terlson                            |
|          | [`String.prototype.replaceAll`][replace-all]                                                 | Peter Marshall<br />Jakob Gruber<br />Mathias Bynens | Mathias Bynens                                         |
|          | [`String.prototype.codePoints`][codepoints]                                                  | Ingvar Stepanyan                                     | Mathias Bynens                                         |
|          | [Distinguishing literal strings][distinguishing-literal-strings]                             | Mike West                                            | Adam Klein<br />Mike West                              |
|          | [`Object.freeze` + `Object.seal` syntax][freeze-seal-syntax]                                 | Keith Cirkel                                         | Keith Cirkel                                           |
|          | [Block Params][block-params]                                                                 | Sam Goto                                             | Sam Goto                                               |
|          | [`{BigInt,Number}.fromString`][from-string]                                                  | Mathias Bynens                                       | Mathias Bynens                                         |
|          | [`Math.seededRandoms()`][seeded-randoms]                                                     | Tab Atkins                                           | Tab Atkins                                             |
|          | [Maximally minimal mixins][mixins]                                                           | Justin Fagnani                                       | Justin Fagnani                                         |
| :rocket: | [Getting last element of Array][arraylast]                                                   | Keith Cirkel                                         | Keith Cirkel                                           |
|          | [Collection methods][collection-methods]                                                     | Michał Wadas                                         | Sathya Gunasekaran                                     |
|          | [Richer Keys][richer-keys]                                                                   | Bradley Farias                                       | Bradley Farias                                         |
|          | [Slice notation][slice-notation]                                                             | Sathya Gunasekaran                                   | Sathya Gunasekaran                                     |
|          | [Logical Assignment Operators][logical-assignment]                                           | Justin Ridgewell                                     | Justin Ridgewell                                       |
|          | [Module Keys][module-keys]                                                                   | Mike Samuel                                          | Mike Samuel                                            |
|          | [Class Static Block][static-blocks]                                                          | Ron Buckton                                          | Ron Buckton                                            |
|          | [class Access Expressions][class-access-expressions]                                         | Ron Buckton                                          | Ron Buckton                                            |
|          | [Pattern Matching][matching]                                                                 | Kat Marchán<br />Brian Terlson                       | Kat Marchán<br />Brian Terlson<br />Sebastian Markbåge |
|          | [Explicit Resource Management][resource-management]                                          | Ron Buckton                                          | Ron Buckton                                            |
|          | [Dynamic Modules][dynamic-modules]                                                           | Bradley Farias                                       | Bradley Farias                                         |
|          | [JavaScript Standard Library][standard-library]                                              | Michael Saboff<br />Mattijs Hoitink                  | Michael Saboff<br />Mattijs Hoitink                    |
|          | [`"use module"`][modules-pragma]                                                             | Dave Herman                                          | Dave Herman                                            |
|          | [`for-in` mechanics][for-in-mechanics]         |                                             | Kevin Gibbons                                        | Kevin Gibbons                                          |
|          | [uniform parsing of quasi-standard `Date.parse` input][uniform-date-parse]                   | Richard Gibson                                       | Richard Gibson                                         |
|          | [JSON.parse source text access][json-parse-source]                                           | Richard Gibson                                       | Richard Gibson                                         |
|          | [Promise.allSettled][allsettled]                                                             | Jason Williams                                       | Mathias Bynens                                         |
|          | [IDL for ECMAScript][idl]                                                                    | Daniel Ehrenberg                                     | Daniel Ehrenberg                                       |

:rocket: means the champion thinks it's ready to advance but has not yet presented to the committee.

:white_check_mark: means a pull request for tests was merged.

:question: means there is no pull request for tests yet.

:construction: means a pull request for tests was created, but not merged yet.

### Contributing new proposals

Please see [Contributing to ECMAScript](https://github.com/tc39/ecma262/blob/master/CONTRIBUTING.md) for the most up-to-date information on contributing proposals to this standard.

### Onboarding existing proposals

Proposals that are Stage 1 and above must be transferred to [the TC39 GitHub organization](https://github.com/tc39) for discoverability and archival purposes. To onboard a proposal that lives outside the TC39 organization:

1. Transfer your repository to the [@tc39-transfer](http://github.com/tc39-transfer) organization
  - if you are a TC39 delegate, but not an admin in that organization, please contact [@LJHarb](https://github.com/ljharb)
2. [@bterlson](https://github.com/bterlson), [@littledan](https://github.com/littledan), or [@leobalter](https://github.com/leobalter) will transfer your repository to the TC39 organization the next chance they get.

Note that as part of the onboarding process your repository name may be normalized. Don't worry, repo redirects will continue to work **as long as** you never create a fork, or a new repository, with the same name - although Github Pages redirects will be broken (please update your links!).

[function-to-string]: https://github.com/tc39/Function-prototype-toString-revision
[globalThis]: https://github.com/tc39/proposal-global
[dynamic-import]: https://github.com/tc39/proposal-dynamic-import
[regexp-legacy]: https://github.com/tc39/proposal-regexp-legacy-features
[bigint]: https://github.com/tc39/proposal-bigint
[class-fields]: https://github.com/tc39/proposal-class-fields
[function-sent]: https://github.com/allenwb/ESideas/blob/master/Generator%20metaproperty.md
[trims]: https://github.com/sebmarkbage/ecmascript-string-left-right-trim
[tests-trims]: https://github.com/tc39/test262/pull/1246
[decorators]: http://github.com/tc39/proposal-decorators
[import-meta]: https://github.com/tc39/proposal-import-meta
[numeric_separators]: https://github.com/tc39/proposal-numeric-separator
[private-methods]: https://github.com/tc39/proposal-private-methods
[export-from]: https://github.com/tc39/proposal-export-default-from
[observable]: https://github.com/tc39/proposal-observable
[matchall]: https://github.com/tc39/String.prototype.matchAll
[tests-matchall]: https://github.com/tc39/test262/pull/1500
[weakrefs]: https://github.com/tc39/proposal-weakrefs
[frozen-realms]: https://github.com/FUDCo/frozen-realms
[more-math]: https://github.com/rwaldron/proposal-math-extensions
[collection-of-from]: https://github.com/leobalter/proposal-setmap-offrom
[try]: https://github.com/ljharb/proposal-promise-try
[chaining]: https://github.com/tc39/proposal-optional-chaining
[signbit]: http://jfbastien.github.io/papers/Math.signbit.html
[stacks]: https://github.com/ljharb/proposal-error-stacks
[do]: https://github.com/tc39/proposal-do-expressions
[realms]: https://github.com/caridy/proposal-realms
[temporal]: https://github.com/maggiepint/proposal-temporal
[float16s]: https://docs.google.com/presentation/d/1Ta_IbravBUOvu7LUhlN49SvLU-8G8bIQnsS08P3Z4vY/edit?usp=sharing
[nonblocking]: https://github.com/tc39/proposal-atomics-wait-async
[symbol-description]: https://github.com/tc39/proposal-Symbol-description
[tests-symbol-description]: https://github.com/tc39/test262/pull/1590
[flat]: https://github.com/tc39/proposal-flatMap
[throw-expressions]: https://github.com/rbuckton/proposal-throw-expressions
[binary-ast]: https://github.com/syg/ecmascript-binary-ast
[pipeline]: https://github.com/tc39/proposal-pipeline-operator
[extensible-literals]: https://github.com/littledan/proposal-extensible-numeric-literals
[protocols]: https://github.com/michaelficarra/proposal-first-class-protocols
[nullish-coalescing]: https://github.com/tc39/proposal-nullish-coalescing
[partial-application]: https://github.com/tc39/proposal-partial-application
[cancel-api]: https://github.com/tc39/proposal-cancellation
[interpreter-directive]: https://gist.github.com/bmeck/59cf8c16959eccffd8b7e9828826a842
[replace-all]: https://github.com/psmarshall/string-replace-all-proposal
[codepoints]: https://github.com/RReverser/string-prototype-codepoints
[distinguishing-literal-strings]: https://github.com/mikewest/tc39-proposal-literals
[freeze-seal-syntax]: https://github.com/keithamus/object-freeze-seal-syntax
[block-params]: https://github.com/samuelgoto/proposal-block-params
[static-class-features]: http://github.com/tc39/proposal-static-class-features/
[tests-function-to-string]: https://github.com/tc39/test262/issues/1163
[tests-global]: https://github.com/tc39/test262/issues/765
[tests-dynamic-import]: https://github.com/tc39/test262/issues/1164
[tests-regexp-legacy]: https://github.com/tc39/test262/issues/1165
[tests-bigint]: https://github.com/tc39/test262/issues/1056
[tests-optional-catch]: https://github.com/tc39/test262/issues/1166
[tests-import-meta]: https://github.com/tc39/test262/issues/1342
[tests-private-methods]: https://github.com/tc39/test262/issues/1343
[tests-flat]: https://github.com/tc39/test262/pull/1388
[tests-numeric_separators]: https://github.com/tc39/test262/issues/1051
[tests-class-fields]: https://github.com/tc39/test262/issues/1161
[from-string]: https://github.com/mathiasbynens/proposal-number-fromstring
[seeded-randoms]: https://github.com/tabatkins/js-seeded-random
[censorship]: https://github.com/domenic/proposal-function-prototype-tostring-censorship
[await]: https://github.com/tc39/proposal-top-level-await
[mixins]: https://github.com/justinfagnani/proposal-mixins
[arraylast]: https://github.com/keithamus/proposal-array-last
[set-methods]: https://github.com/tc39/set-methods
[collection-methods]: https://github.com/tc39/collection-methods
[object-from-entries]: https://github.com/bakkot/object-from-entries
[hashbang-grammar]: https://github.com/bmeck/proposal-hashbang
[richer-keys]: https://docs.google.com/presentation/d/1q3CGeXqskL1gHTATH_VE9Dhj0VGTIAOzJ1cR0dYqDBk/edit#slide=id.p
[slice-notation]: https://github.com/gsathya/proposal-slice-notation/
[logical-assignment]: https://github.com/jridgewell/proposal-logical-assignment
[unicode-sequence-properties]: https://github.com/mathiasbynens/proposal-regexp-unicode-sequence-properties
[well-formed-stringify]: https://github.com/gibson042/ecma262-proposal-well-formed-stringify
[tests-well-formd-strngfy]: https://github.com/tc39/test262/pull/1787
[module-keys]: https://github.com/mikesamuel/tc39-module-keys
[static-blocks]: https://github.com/rbuckton/proposal-class-static-block#readme
[class-access-expressions]: https://github.com/rbuckton/proposal-class-access-expressions
[matching]: https://github.com/tc39/proposal-pattern-matching
[regex-offsets]: https://github.com/rbuckton/proposal-regexp-match-offsets
[buffer-transfer]: https://github.com/domenic/proposal-arraybuffer-transfer/
[resource-management]: https://github.com/rbuckton/proposal-using-statement
[dynamic-modules]: https://github.com/guybedford/proposal-dynamic-modules
[standard-library]: https://github.com/msaboff/JavaScript-Standard-Library
[modules-pragma]: https://github.com/tc39/proposal-modules-pragma
[for-in-mechanics]: https://github.com/bakkot/for-in-exploration
[uniform-date-parse]: https://github.com/gibson042/ecma262-proposal-uniform-interchange-date-parsing
[json-parse-source]: https://github.com/gibson042/ecma262-proposal-JSON-parse-with-source
[allsettled]: https://github.com/jasonwilliams/proposal-promise-allSettled
[idl]: https://github.com/littledan/proposal-idl
[tests-fromentries]: https://github.com/tc39/test262/pull/1676
