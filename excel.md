# copy and paste for multiple/merged cells

## both unmerged
### one to one
cell size doesn't matter
### many to many
cell size doesn't matter

## both merged
### one to one
works fine, regardless of how many numbers of cells are merged for source and destination merged cells
### many to many
- behave as merged to unmerged
- destination merged cells will unmerge first

## unmerged to merged
### one to one
works
### many to many
- works if the number of the unmerged does match the number of cells of the merged if it were unmerged; in this case, the merged cells automatically unmerge
- **doesn't work** if the number of the unmerged doesn't match the number of cells of the merged if it were unmerged
- note the **exception**: **we can't do that to a merged cell**

## merged to unmerged
### one to one
- works
- unmerged destination cells will *automatically merge*
### many to many
- works
- unmerged destination cells will *automatically merge*
