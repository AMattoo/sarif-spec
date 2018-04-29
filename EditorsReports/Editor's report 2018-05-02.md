# Editor's report

Laurence J. Golding and Michael Fanning

Presented at TC Meeting #16, May 2nd, 2018

1. After being approved at the last TC meeting (#13), the following spec changes were merged into the provisional draft:

    1. [Issue #46](https://github.com/oasis-tcs/sarif-spec/issues/46): "Support graphs and graph traversals"

    1. [Issue #98](https://github.com/oasis-tcs/sarif-spec/issues/98): "Add encoding property to file object"

    1. [Issue #99](https://github.com/oasis-tcs/sarif-spec/issues/99): "Result object's snippet property"

    1. [Issue #107](https://github.com/oasis-tcs/sarif-spec/issues/107): "Settle on a small set of hash functions."

    1. [Issue #108](https://github.com/oasis-tcs/sarif-spec/issues/108): "Represent VCS properties"

    1. [Issue #113](https://github.com/oasis-tcs/sarif-spec/issues/113): "Provide guidance on including a hostname in a uriBaseIdValue"

    1. [Issue #119](https://github.com/oasis-tcs/sarif-spec/issues/119): "Add tool automation manager/SARIF post-processor profile"

    1. [Issue #120](https://github.com/oasis-tcs/sarif-spec/issues/120): "Identify files that were scanned"

    1. [Issue #125](https://github.com/oasis-tcs/sarif-spec/issues/125): "Address corner case for generated files in run.files dictionary"

    1. [Issue #130](https://github.com/oasis-tcs/sarif-spec/issues/130): "Fix the location object"

1. I made the following changes at editorial discretion:

    1. Updated the comprehensive sample in Appendix I, "Examples", to reflect better usage and correct an error in the use of `invocation.responseFiles`.

    1. Clarified that a hexadecimal `hash.value` has no prefix (_e.g._, `"0x"`) or suffix (_e.g._, `"h"`) and is case-insensitive.

1. The formal spec language for the following additional issues was made available for review on the specified dates, and we will move their adoption in today's meeting:

    1. [Issue #122](https://github.com/oasis-tcs/sarif-spec/issues/122): "Clarify guidance for 'partialFingerprints' components" -- made available on April 27th, 2018.

    1. [Issue #126](https://github.com/oasis-tcs/sarif-spec/issues/126): "Add result.fingerprints array" -- made available on April 27th, 2018.

    1. [Issue #134](https://github.com/oasis-tcs/sarif-spec/issues/134): "conversion.analysisToolLogFileLocation should be an array" -- made available on April 25th, 2018.

    1. [Issue #136](https://github.com/oasis-tcs/sarif-spec/issues/155): "Make sure result.id explicitly notes its relevance to automation/results management systems" -- made available on April 29th, 2018.

    1. [Issue #137](https://github.com/oasis-tcs/sarif-spec/issues/137): "Support annotating image attachments" -- made available on April 24th, 2018.

    1. [Issue #139](https://github.com/oasis-tcs/sarif-spec/issues/130): "Don't require codeFlowLocation.location" -- made available on April 17th, 2018.

    1. [Issue #145](https://github.com/oasis-tcs/sarif-spec/issues/145): "For symmetry, define a logicalLocation object" -- made available on April 28th, 2018.

    1. [Issue #147](https://github.com/oasis-tcs/sarif-spec/issues/147): "Rename suggestion: toolFingerprintContributions -> partialFingerprints, computedFingerprints -> fingerprints" -- made available on April 27th, 2018.

    1. [Issue #148](https://github.com/oasis-tcs/sarif-spec/issues/148): "update stableId to allow for build configuration/other details" -- made available on April 24th, 2018.

    1. [Issue #154](https://github.com/oasis-tcs/sarif-spec/issues/154): "Define a "result management system" conformance profile" -- made available on April 27th, 2018.

    1. [Issue #155](https://github.com/oasis-tcs/sarif-spec/issues/155): "Remove annotations object; use regions instead" -- made available on April 27th, 2018.
