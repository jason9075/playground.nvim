# playground.nvim
a sample plugin for nvim

## Folders

- plugin/ : When nvim start, it will run thid folder code.
- lua/ : When we execute :lua require"playground", it will run that folder code.

## Local Test for Packer

add relative path in your packer.
```
use "path/to/project/playground.nvim"
```
then use
```
:PackerSync
```
