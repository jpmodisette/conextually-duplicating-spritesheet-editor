Contextually-Duplicating Spritesheet Editor

If you have a spritesheet with a bunch of pixel art images of the same character in different frames, you might want to make
some simple change like adding horns.  This app lets you make the edit once and have it appear everywhere where the image
looks like it did around where you edited.  If your sprites are very close together, you might want to separate them so
the context doesn't get pulled from adjacent sprites - my intent is that the context will just be pixels from the part of
the image you're modifying, which hopefully are exactly duplicated between all of the sprite members.  If you need to
spread out the sprites in your spritesheet to avoid context overlap, you can use 
https://jpmodisette.github.io/spritesheet-spreader-outer/

The size of matching context required is controlled by the slider bar.

Editing is currently limited to setting pixels to one of the colors in the original palette, or "undo all".

This app was vibe-coded with ChatGPT-5.
