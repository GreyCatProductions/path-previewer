A small HTML tool to display grids, paths, hints, and arrows for debugging grid-based logic.

## Usage

1. Open the HTML file in your browser.
2. Paste your lines (paths, hints, etc.) into the text box.
3. Press **Draw** to update the visualization.

## Format
first(X,Y) gets marked with a green dot 

final(X,Y) gets marked with a red dot

hint(X,Y,N) gets marked with a yellow dot and a number inside

path(X,Y,XT,YT) draws a line from (X,Y) to (XT,YT)

## Example

```
first(1,1).
final(3,3).

hint(2,1,2).
hint(2,2,2).

path(1,1,2,1) path(2,1,3,1) path(1,2,1,3) path(1,3,2,3) path(3,1,3,2) path(2,2,1,2) path(3,2,2,2) path(2,3,3,3)
```
