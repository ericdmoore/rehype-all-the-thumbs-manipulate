# rehype-all-the-thumbs-manipulate
Supporting [`rehype-all-the-thumbs`](https://github.com/ericdmoore/rehype-all-the-thumbs) by adding the new thumbnails back to the DOM tree

> rehype-👍🏿👍🏼👍🏽👍🏻👍🏾 (Change the input file to include the newly created assets)

## Overview

_Configuration_:
- ?? `srcs` ??

_Input_:
- a HAST tree
- vfile with `srcs` instructions
- vfile with added `newAssets` key added to the object

_Output_:
- updated HAST tree with source node added within a picture element

## Pairs Well With:

- [rehype-all-the-thumbs](https://github.com/ericdmoore/rehype-all-the-thumbs) ...like putting on velcro shoes
- [rehype-all-the-thumbs-curate](https://github.com/ericdmoore/rehype-all-the-thumbs-curate) (DOM -> data.srcs)
- [rehype-all-the-thumbs-create](https://github.com/ericdmoore/rehype-all-the-thumbs-create) (data.srcs -> data.newAssets)
- [rehype-all-the-thumbs-obviate](https://github.com/ericdmoore/rehype-all-the-thumbs-obviate) (data.newAssets.filter -> data.newAssets)
- [vfile-newAssets-generate](https://github.com/ericdmoore/vfile-newAssets-generate) (data.newAssets -> Side Effect Funtion to create the file)
