[![MIT license](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT) [![npm version](https://badge.fury.io/js/pokesprite-spritesheet.svg)](https://badge.fury.io/js/pokesprite-spritesheet) ![Updated for](https://img.shields.io/badge/Updated%20for-Pok%C3%A9mon%20Sword%2FShield%20(Isle%20of%20Armor%20DLC)-blue)

# PokéSprite - generated spritesheet

This repo contains a spritesheet build automatically from the [PokéSprite project](https://github.com/msikma/pokesprite). It's designed to make it easy to add Pokémon sprites to a website.

<p align="center"><img align="center" src="docs/banner_gen8_2x.png" alt="Pokésprite Gen 8 examples banner" width="726"></p>

See [the overview page](#) for a list of all supported sprites.

## Adding sprites to a page

Sprites are accessible by adding a `<span>` with the right class name:

<table>
<tr>
<th>HTML</th>
<th>Result</th>
</tr>

<tr>
<td>
<div class="highlight highlight-source-html">
<pre>
<span class="pl-kos">&lt;</span><span class="pl-ent">span</span> <span class="pl-c1">class</span>="<span class="pl-s">pokesprite pokemon bulbasaur</span>"<span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">span</span><span class="pl-kos">&gt;</span>
</pre>
</div>
</td>
<td>
<img src="https://raw.githubusercontent.com/msikma/pokesprite/master/pokemon-gen8/regular/bulbasaur.png" width="68" alt="Bulbasaur">
</td>
</tr>

<tr>
<td>
<div class="highlight highlight-source-html">
<pre>
<span class="pl-kos">&lt;</span><span class="pl-ent">span</span> <span class="pl-c1">class</span>="<span class="pl-s">pokesprite pokemon bulbasaur shiny</span>"<span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">span</span><span class="pl-kos">&gt;</span>
</pre>
</div>
</td>
<td>
<img src="https://raw.githubusercontent.com/msikma/pokesprite/master/pokemon-gen8/shiny/bulbasaur.png" width="68" alt="Bulbasaur (shiny)">
</td>
</tr>

<tr>
<td>
<div class="highlight highlight-source-html">
<pre>
<span class="pl-kos">&lt;</span><span class="pl-ent">span</span> <span class="pl-c1">class</span>="<span class="pl-s">pokesprite ball dusk</span>"<span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">span</span><span class="pl-kos">&gt;</span>
</pre>
</div>
</td>
<td>
<img src="https://raw.githubusercontent.com/msikma/pokesprite/master/items/ball/dusk.png" width="32" alt="Dusk ball">
</td>
</tr>

</table>

## License

The sprite images are © Nintendo/Creatures Inc./GAME FREAK Inc.

Everything else, and the programming code, is governed by the [MIT license](http://opensource.org/licenses/MIT).
