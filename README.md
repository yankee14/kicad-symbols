# kicad-symbols
Fork of the official KiCad schematic symbol library.

### Description:

The official kicad-symbols library is organized by part function instead of by manufacturer. We reorganize the library by manufacturer, and reduce clutter by only committing parts which we are considering using in a design. All the official symbols are still here, they've just been moved into '.official/'.

### Repository Guidelines:

1. This remote 'master' will be kept clean and up to date with official kicad-symbols remote 'master', in case we want to create a pull request on the official kicad-symbols repository.
    * In other words, NEVER MERGE YOUR OWN CODE INTO 'master'!
2. This remote 
2. Bring 'master' up to date with the official kicad-symbols repository 'master' before committing your own symbols
2. Only add symbols that you are considering using in a project.
    * Unless you are creating a pull request for the official kicad-symbols repository
3. If you need to use a symbol that already exists in '.official/', then copy that symbol into the appropriate manufacturer lib.
