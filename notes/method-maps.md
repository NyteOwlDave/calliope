<style>
@import url("https://nyteowldave.neocities.org/style.css");
</style>

<style>
@import url("http://dave-omega/demo/style/sce-hud.css");
</style>

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->

[me-omega]:
<http://dave-omega/calliope/notes/method-maps.html>
"Omega Edition"

[calliope]:
<http://dave-omega/calliope/>
"Calliope ~ Omega"

[calliope-notes]:
<http://dave-omega/calliope/notes/>
"Calliope's Notes ~ Omega"

----------------------------------------------------------------

# `{}` Method Maps

> [`🔴` Calliope][calliope]
> [`🔴` Notes][calliope-notes]
> [`🔴` Primary][me-omega]

> [`?` File System](./)

<!-- [ 🟢 ] -->

----------------------------------------------------------------

## `⏩` Media Control

| Decal | Typical Action | Typical Method Name |
|-------|----------------|---------------------|
| ⬆️     | Scroll Up      | scroll_up           |
| ➡️     | Scroll Right   | scroll_right        |
| ⬇️     | Scroll Down    | scroll_down         |
| ⬅️     | Scroll Left    | scroll_left         |
| ◻️     | Zoom In        | scale_magnify       |
| ▫️     | Zoom Out       | scale_reduce        |
| ⏮️    | Home / First   | move_first          |
| ⏪    | Previous Page  | move_prev           |
| ⏩    | Next Page      | move_next           |
| ⏭️    | End / Last     | move_last           |
| ✅     | Accept Changes | accept              |
| ❎     | Reject Changes | reject              |
| 🔄    | Swap / Exchange | swap               |
| ⤵️    | Copy Down      | copy_down           |
| ⤴️    | Copy Up        | copy_up             |
| 💠     | Full Screen    | zoom               |
| 🗑️    | Clear          | clear              |

----------------------------------------------------------------

## NOTE

Some apps are already using the __Method Map__ parardigm.

These apps create buttons dynamically, using only inner text
comprised of decals separated with a vertical bar `"|"`.

### Example

```html
<div id="menu">
⏮️| ⏪ | ⏩ | ⏭️
</div>
```

----------------------------------------------------------------

<header id="messages"></header>

<footer id="footer">
  <input id="footer_input" onchange="perform(event)" />
</footer>

<textarea id="sce" class="hud hide" wrap="off">
</textarea>

----------------------------------------------------------------

<script>
; iwm = Object.keys( window ).sort()
</script>

<script>
;
; doc = document
; doc . title
= doc . querySelector( "H1" )
. textContent
;
</script>

<script>
; cls =()=> console.clear()
</script>

<script>
; loc = location
; veer  =( h )=> ( loc.hostname = ( h ) )
; again =(   )=> ( loc.reload() )
</script>

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->

<script src="https://nyteowldave.github.io/std/api/gems/prolog-beta.js"></script>
<script src="http://dave-omega/demo/web/api/hud.js"></script>
<script src="http://dave-omega/demo/web/gems/interpreter-lite.js"></script>
<script src="http://dave-omega/demo/web/gems/houdini.js"></script>

<!-- [ NOTE ]
 replace-anchor-decals.js should be located in Web Demo Gems
-->


<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->

<script>
footer_input.value = "hud()";
</script>

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->

