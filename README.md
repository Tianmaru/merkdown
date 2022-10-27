# merkdown

Author: Tianmaru

## What is merkdown?

- create presentations with Markdown
- no need to use a GUI
- generates tex, pptx or odp files

## How to use merkdown?

- git clone git@github.com:Tianmaru/merkdown.git
- cd merkdown
- pip install odpslides python-pptx
- python merkdown.py README.md --aspect 16:9

## How does it work?

- first # defines Presentation title
- author in line that starts with 'Author:'
- any other # creates a new slide
- bullet points are written onto the slide
	- intendation works too
- template.tex is used for tex export
- odpslides and python-pptx for other exports

## Limitations and missing features

- right now, merkdown does not support:
	- ordered lists
	- images and links
	- text resizing / continous slides
	- solic color backgrounds for pptx and odp

## Alternatives

- after finishing this prototype, I searched for alternatives
- you might want to consider marp
	- comes with a handy vscode extension
	- more features
- (I am not associated in any way with marp)
- however, marp does not offer markdown to tex export
