## Diagram syntax

If you are new to mermaid, read the [Getting Started](n00b-gettingStarted.md) and [Overview](n00b-overview.md) sections, to learn the basics of mermaid.
Video Tutorials can be found at the bottom of the Overview Section.

Below is a list of diagram types supported by mermaid and how they can be defined.

## mermaid tag
These Diagram Definitions can be entered within a \<div class=mermaid> tag.
like so :
```html
<div class="mermaid">
     graph LR
      A --- B
      B-->C[fa:fa-ban forbidden]
      B-->D(fa:fa-spinner);
</div>
```
## Mermaid Live Editor
You can proofread or render and download your definitions in real-time with the [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor).
This would then offer you the following choices to download the diagram:

![Flowchart](./img/DownloadChoices.png)

**Note:** Copying the markdown will allow you to link to your unique diagram from anywhere online.

## Directives:
[Directives](./directives.md) allows the limited reconfiguration of a diagram just before it is rendered. It can alter the font style, color and other aesthetic aspects of the diagram.

## Theme Creation:
Mermaid allows you to change [Themes](./theming.md). This is also done using [Directives](./directives.md).


