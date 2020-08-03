## Overview

Assuming you've got textures ready and just want to apply them to the Slink products you own, this is all you need to do:

1. Name the textures correctly. You can see what name the HUD expects on each of the buttons.
2. Hold the **control (or 'ctrl')** key and drag them from your inventory onto the area on the HUD.

If all goes well the indicator for that texture should turn green and you can apply it either by clicking on the appropriate button, or by clicking 'Apply All'

## How do I..?

### How do I create my own textures?

A complete tutorial on how to create your own textures is a bit out of the scope of this document, but assuming you've got Photoshop (or the Gimp, or Paint.NET, or another image editing program of your choice) ready to go, here are the UV maps that'll get you started:

* [Feet UV](https://s3.amazonaws.com/slink-assets/Feet+UV+template.png)
* [Hands UV](https://s3.amazonaws.com/slink-assets/Hands+UV+template.png)
* [Nails UV](https://s3.amazonaws.com/slink-assets/Nails+UV+template.png)
* [Head UV](https://s3.amazonaws.com/slink-assets/Slink+Visage+Face+UV.png)

To create stocking and tattoo appliers you do not need a separate UV, simply use the same texture that you use for the SL stocking layer.

Note some of the UVs have additional instructions on them to make your life easier. In particular, the feet and hands UV should **not** have nails painted on it, as they are provided separately in the mesh.

Make sure you save out the final texture you intend to use as a **24 bit Targa** file.

* **In Photoshop**: File / Save As / (set type to Targa) / select 24 bit in the next window
* **In Gimp**: First, flatten your image and then: File / Save As / Targa

#### Why 24 bit targa?

Feel free to skip this section if don't care about the nitty gritty details.

The reason to save as a 24 bit targa file is to make sure the texture is uncompressed (and thus of maximum quality) when uploading and that it does not have any alpha channel information. The reason the first bit is important is that SL compresses textures on the server side regardless of the format you upload them in, and compressing a texture twice is not good for the look of it. The second part (the alpha channel) is important because the SL lighting engine responds differently to textures with alpha channels, making it difficult to create a skin that looks vibrant and true to colour.

### How can I have different sets of personal textures?

The HUD is copyable for this reason. Feel free to create as many copies as you want, and set up a variety of looks!



## Something went wrong!

Something not working as intended? Have a look if the below explanations solve your problem.

### I try to drag the texture on the HUD as instructed, but the cursor remains a lock icon

Make sure you are holding the **control (or 'ctrl')** key on your keyboard as you drag the texture (on Macs this key is only present in the bottom left of your keyboard). Make sure you have **full** permissions to the texture you're trying to drop on the HUD. Also make sure you try to drop the texture on the area of the HUD designated for it.

If you are holding **control (or 'ctrl')**, the permissions are correct and you're in the right spot, the likely cause is lag. It can take Second Life a few seconds to realise what you're trying to do. Hold **control (or 'ctrl')**, hover the texture over the HUD and give SL a second or two to catch up.

### I get a &ldquo;Duplicate Texture&rdquo; error

#### How to fix

Use the _clear_ button on the HUD to remove all textures from it's inventory and drop only one texture of each type back.

#### Why does this happen?

To make life easier for you, the HUD doesn't care if you capitalise the texture names or not. This does mean that if you add _'feet-skin'_ and _'FEET-SKIN'_ to the HUD, it doesn't know which texture to pick.

It can also happen if you put a texture by the same name in the HUD twice.

### I get a &ldquo;No Permission&rdquo; error

#### How to fix

Use the _clear_ button to remove all textures from the HUD's inventory and drop a texture you have *full* permissions to onto the HUD.

#### Why does this happen?

The HUD cannot read textures unless you have full permissions to them. This shouldn't be a problem as the personal HUD is for use with your personal textures.

## Contact Us

If none of the above helped and you've still got a question or problem, feel free to get in touch with us in the following ways:

* [Email us](mailto:slinkhelp@gmail.com "Contact slink support") and we'll get back to you as soon as we can.
* Contact **Slink Resident** in-world to get help
