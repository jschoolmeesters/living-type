## Backlog
---
13-03-2026:
- [ ] Set up a minimal isolated diffusion project using bitmap instead of vector space
- [ ] Research/document different diffusion algorithms and their visual differences
- [ ] Have a working isolated diffusion project, using a set of points
- [ ] Test how walker/particle lifetime effects contrast
20-03-2016:
- [ ] See if you can find patterns of contrast in conventional typography based on the segments (straight line, curve) of a letter
- [ ] Apply these to points along the outline of existing fonts
Probably later:
- [ ] Apply these patterns to a [Hershey font](https://paulbourke.net/dataformats/hershey/) to create a typeface typeface **with** contrast
	- [ ] For now I can use a OTF version of a Hershey font called [Relief SingleLine](https://github.com/isdat-type/Relief-SingleLine/tree/main) to simulate what using an actual single line would look like
	- [ ] Requires converting individual Hershey font letters to SVG, and then into points
## Where I'm currently at
---
I finished a tool that lets me load any OTF/TTF font and obtain evenly spaced out points along the outlines of each letter. I can use these as starting points for the organic growth I want to simulate using [Diffusion Limited Aggregation (DLA)](https://en.wikipedia.org/wiki/Diffusion-limited_aggregation) (probably).
## Notes
---
- Should I generate for x amount of steps and then freeze the canvas? Or is it possible to keep animating the growth for a more organic look.
- DLA seems to produce somewhat thin branches/clusters, I want my branches to be full like [Lichen](https://en.wikipedia.org/wiki/Lichen).
