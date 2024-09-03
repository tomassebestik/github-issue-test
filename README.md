# Test GH issues syntax

## Task list

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

## Footnotes

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]:
    To add line breaks within a footnote, prefix new lines with 2 spaces.
    This is a second line.

### SUP/SUB GitHUB

This is a <sub>subscript</sub> text
This is a <sup>superscript</sup> text

### SUP/SUB Gitlab

The formula for water is H<sub>2</sub>O
while the equation for the theory of relativity is E = mc<sup>2</sup>.

## Alerts GitHUB

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Alerts GITLAB

> NOTE:
> This is something to note.

> WARNING:
> This is something to be warned about.

> DISCLAIMER:
> This page contains information related to upcoming products, features, and functionality.
> It is important to note that the information presented is for informational purposes only.
> Please do not rely on this information for purchasing or planning purposes.
> The development, release, and timing of any products, features, or functionality may be subject to change or delay and remain at the
> sole discretion of GitLab Inc.

## Gitlab TABS

::Tabs

:::TabTitle Tab One

Here's some content in tab one.

:::TabTitle Tab Two

Here's some other content in tab two.

::EndTabs

## Emoji

:smile:

## Multiline blockquote (GL)

> > > If you paste a message from somewhere else

that spans multiple lines,

you can quote that without having to manually prepend `>` to every line!

> > >

## Codeblock GH

```python copy
import six

print("hello")
```

## Codeblock GL

```python
import six

print("hello")
```

## Collapsed section GH

<details>
<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section.

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>

## Diagrams GH

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## GeoJSON GH

```geojson
{
	"type": "FeatureCollection",
	"features": [
		{
			"type": "Feature",
			"id": 1,
			"properties": {
				"ID": 0
			},
			"geometry": {
				"type": "Polygon",
				"coordinates": [
					[
						[
							-90,
							35
						],
						[
							-90,
							30
						],
						[
							-85,
							30
						],
						[
							-85,
							35
						],
						[
							-90,
							35
						]
					]
				]
			}
		}
	]
}
```

## Images resize

![](docs/LedStripSquare.jpg)

![](docs/LedStripSquare.jpg){: width="30%"}

![](docs/LedStripSquare.jpg){: width=300"}
