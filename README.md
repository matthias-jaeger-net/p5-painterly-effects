# p5-painterly-effects
Write-up on simple effects to transform an input image in a abstract "painting" without using AI modles

## Pointilize
- ```[-] Image becomes oddly abstracted```
- ```[-] Highly depends on a good input image```
- ```[i] Canvas size must equal image size!```

```
Jump to a random point
Sample the color at that point from the image
Set the fill color to the sample
Draw a circle (or any other shape) on the canvas
Repeat unitl you are happy
```

## Sample grid
[-] A bit boring "tiled" effect

```
Jump to a random point
Sample the color at that point from the image
Set the fill color to the sample
Draw a circle (or any other shape) on the canvas
Repeat unitl you are happy
```

## Random walkers sampling position

## The lerp jump