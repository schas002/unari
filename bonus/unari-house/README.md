# unari-house

A Minetest house wherein the entrance is from the chimney.

* * *

[![Well, it's *meant* to be like this but is not.](the-entries/008.png)](the-entries/008.png)

*Entry No. 8 '[House](the-entries/008.png)'*

* * *

## Install

Unfortunately, this is a [WorldEdit](https://github.com/Uberi/Minetest-WorldEdit) schematic. Installation is involved enough.

First, clone the WorldEdit repository to your Minetest playground at `mods/worldedit`:

```sh
$ git clone https://github.com/Uberi/Minetest-WorldEdit.git ~/.minetest/mods/worldedit
```

Next, enable WorldEdit in the Minetest mod settings for the world you want to place the house in.

Now, unzip `unari-house.we.gz` to the world's `schems` folder, somewhere at `worlds/someplace/schems` in your Minetest playground.

```sh
$ gzip -dc unari-house.we.gz > ~/.minetest/worlds/someplace/schems/unari-house.we
```

## Usage

You need the `worldedit` privilege.

Set a starting position, allocate and then load the schematic:

```
//p set1
//allocate unari-house
//load unari-house
```

Voila voila :/

## License

*<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.*
