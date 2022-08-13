# CFAR jargon flashcards

[Duncan posted](https://www.lesswrong.com/posts/fbv9FWss6ScDMJiAx/appendix-jargon-dictionary) a list of jargon from the [Center For Applied Rationality](https://en.wikipedia.org/wiki/Center_for_Applied_Rationality) Handbook, so I made an [Anki](https://en.wikipedia.org/wiki/Anki_(software%29) deck for anyone who wants to memorize it.

## Importing

Download [`jargon.apkg`](./jargon.apkg), open Anki, and press `Ctrl+Shift+I` to open an "Import" dialogue (you can also navigate to **File** → **Import...**). Select `jargon.apkg`. The flashcards should show up in the deck "CFAR".

## Editing and pull requests

The flashcards are written in the markdown file [`jargon.md`](./jargon.md) and translated into an Anki flashcard deck using the command `mdanki jargon.md --deck "CFAR" jargon.apkg`. To install `mdanki`, run `npm install mdanki`.

It would be nice if someone added images to these flashcards to make them easier to remember. For example, a diagram of the [80-20 rule](https://en.wikipedia.org/wiki/Pareto_principle). If you do, make sure the images are under a [CC-compatible license](https://en.wikipedia.org/wiki/Creative_Commons_license). The format for including an image in the markdown file is below.

```
## Word

This is the definition of the word.

![](./image.png)
```
