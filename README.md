# rehype-all-the-thumbs-manipulate
Supporting [`rehype-all-the-thumbs`](https://github.com/ericdmoore/rehype-all-the-thumbs) by adding the new thumbnails back to the DOM tree

## Overview

_Configuration_:
- ?? `srcs` ??

_Input_:
- a HAST tree
- vfile with `srcs` instructions
- vfile with added `newAssets` key added to the object

_Output_:
- updated HAST tree with source node added within a picture element
