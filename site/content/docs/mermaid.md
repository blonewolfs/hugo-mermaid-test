---
title: Mermaid Example
date: "2022-11-15"
tags:
  - hugo
  - bootstrap
  - css
  - scss
  - docsy
---
## Built-in Mermaid example
```mermaid
graph TD
  Start --> Need{"Hugo version >= 0.93.0"}
  Need -- No --> Off["Set params.mermaid.enable = true"]
  Off --> Author
  Need -- Yes --> Author[Insert mermaid codeblock]
```

## Custom Mermaid shortcode example
{{< mermaid align="center" theme="neutral" >}}
graph TD
  Start --> Need{"Hugo version >= 0.93.0"}
  Need -- No --> Off["Set params.mermaid.enable = true"]
  Off --> Author
  Need -- Yes --> Author[Insert mermaid codeblock]
{{< /mermaid >}}