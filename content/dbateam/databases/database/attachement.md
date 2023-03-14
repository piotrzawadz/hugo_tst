---
title: "Attachement - test"
menuTitle: "Attachement"
date: 2023-03-08T11:46:39+01:00
draft: false
---

# File to be presented:
# abcder

{{%attachments title="Related files"  sort="asc" style="info" color="grey" /%}}

---

{{%attachments title="Related files" pattern=".*\.(odt|txt)$" sort="asc" style="info" color="grey" /%}}

---

```mermaid { align="center" zoom="true" }
graph LR;
    If --> Then
    Then --> Else
```

---

{{< mermaid >}}
%%{init:{"fontFamily":"monospace", "sequence":{"showSequenceNumbers":true}}}%%
sequenceDiagram
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
{{< /mermaid >}}