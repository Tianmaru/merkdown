# merkdown

Author: Tianmaru

## What is merkdown?

- create presentations with Markdown
- no need to use a GUI
- generates tex, pptx or odp files

## How to use merkdown?

- git clone git@github.com:Tianmaru/merkdown.git
- cd merkdown
- pip install odpslides pptx
- python merkdown.py README.md

## How does it work?

- first # defines Presentation title
- author in line that starts with 'Author:'
- any other # creates a new slide
- bullet points are written onto the slide
	- intendation works too
- template.tex is used for tex export
- odpslides and pptx for PowerPoint and LibreOffice
