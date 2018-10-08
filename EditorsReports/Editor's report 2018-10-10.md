# Editor's report

Laurence J. Golding and Michael Fanning

Presented at TC Meeting #25, October 10th, 2018

1. The following issues were closed without further action:

    1. [Issue #197](https://github.com/oasis-tcs/sarif-spec/issues/197): "Snippet, lineSnippet and multilineSnippet"

        Per discussion with Michael Fanning, who opened the issue, there is nothing more to do here.
        Michael's last remaining concern on this issue was to ensure the spec was clear on the issue of
        "region property domain separation" (line/column vs. offset/length properties). It is.

    1. [Issue #199](https://github.com/oasis-tcs/sarif-spec/issues/199): "Random-access readable format"

        There is work going on at Microsoft to develop a general-purpose, high-performance, random access JSON-
        equivalent serialization format, but it will not be part of SARIF v2.0. Michael will add comments to the
        issue documenting his discussions with Micro Focus on this topic.

    1. [Issue #229](https://github.com/oasis-tcs/sarif-spec/issues/229): "We do not have an automationGuid to match automationLogicalId"

        I closed this as duplicate of [Issue #217](https://github.com/oasis-tcs/sarif-spec/issues/217): "Consider adding a discrete 'id' object,"
        because Michael and I decided to address this inconsistency by introducing the "id" object he'd previously proposed.

    1. [Issue #254](https://github.com/oasis-tcs/sarif-spec/issues/254): "Rename externalizableProperty.version to SARIF version."

        After discussion in the issue with Jim Kupsch, I decided not to do this, and instead made editorial change #255 (see below).

1. After being approved as amended at the last TC meeting (#24), the following spec changes were merged into the provisional draft:

    1. [Issue #232](https://github.com/oasis-tcs/sarif-spec/issues/232): "Why is the 'results' array required?"

    1. [Issue #234](https://github.com/oasis-tcs/sarif-spec/issues/234): "Consider making originalUriBaseIds a dictionary of file location objects"

    1. [Issue #235](https://github.com/oasis-tcs/sarif-spec/issues/235): "Wrap externalized files with contextual information"

    1. [Issue #238](https://github.com/oasis-tcs/sarif-spec/issues/238): "objects without property bags"

    1. [Issue #240](https://github.com/oasis-tcs/sarif-spec/issues/240): "Consider removing type inconsistency with message property in exception object"

    1. [Issue #242](https://github.com/oasis-tcs/sarif-spec/issues/242): "Rename startTime/endTime to startTimeUtc and endTimeUtc"

    1. [Issue #243](https://github.com/oasis-tcs/sarif-spec/issues/243): "Consider making file.hashes a dictionary"

    1. [Issue #244](https://github.com/oasis-tcs/sarif-spec/issues/244): "Rename versionControlDetails.uri to repositoryUri"

    1. [Issue #251](https://github.com/oasis-tcs/sarif-spec/issues/251): "We don't need a hash object"

1. I made the following changes at editorial discretion:

    1. [Issue #231](https://github.com/oasis-tcs/sarif-spec/issues/231): "Section on external files should go ahead and list all the properties that are externalizable"

        I made this change as part of [#235](https://github.com/oasis-tcs/sarif-spec/issues/235).

    1. [Issue #255](https://github.com/oasis-tcs/sarif-spec/issues/255): "State that sarifLog.version and externalizedProperty.version refer to the spec version"

        This replaces #254.

1. The formal spec language for the following issues was made available for review on the specified dates, and we will move their adoption in today's meeting:

    1. [Issue #217](https://github.com/oasis-tcs/sarif-spec/issues/217): "Consider adding a discrete 'id' object" -- made available on October 8th, 2018.

    1. [Issue #219](https://github.com/oasis-tcs/sarif-spec/issues/219): "Delete 'threadFlowLocation.step' property" -- made available on October 8th, 2018.
