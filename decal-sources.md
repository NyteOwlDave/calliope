<style>
@import url( "./style/every-page.css" );
</style>

<style>
li {
    cursor : pointer;
}
</style>

----------------------------------------------------------------

# Decal Sources

> ( `RAM Disk Decals` )

> ( `Calliope` )

----------------------------------------------------------------

# Calliope Repo

- [Omega](http://dave-omega/app/calliope/www/calliope/)
- [Tower](http://dave-tower/app/calliope/www/calliope/)

----------------------------------------------------------------

# Notes

- Add URLs to Calliope G-Site
- Check Raindrop
- Check Browser Menus
- Check Browser Stores
- Check Decal Wizard Volumes
- Check Calliope Volumes
- Check Probook Pubs
- Check Media Volumes
- Check All Cloud Stores
- Check All NAS Shares
- Check All Spreadsheets
- Check All Notebooks
- Check All Sites
- Locate Emoji Warehouse Site (Swill? Commands?)

----------------------------------------------------------------

+ Calliope Site
@ https://sites.google.com/view/ncs-calliope/home
| # Add Sources Here

----------------------------------------------------------------

+ GitHub Repo
@ https://github.com/NyteOwlDave/calliope

----------------------------------------------------------------

+ Jarvis Decals
@ http://dave-omega/app/jarvis/decals/decals-menu.html

----------------------------------------------------------------

+ Calliope Notebook
@ ???

----------------------------------------------------------------

+ Idea Flip
@ https://ideaflip.com/b/sv99ag69aj8f/

----------------------------------------------------------------

+ G-Drive
@ https://drive.google.com/drive/folders/1AYei8tBQxtEckheFcA-_ApfJ8qopbMCJ

----------------------------------------------------------------

+ D-Drive
@ ( pending )

----------------------------------------------------------------

+ M-Drive
@ ( pending )

----------------------------------------------------------------

+ I-Drive
@ ( pending )

----------------------------------------------------------------

+ Neo
@ Pending

----------------------------------------------------------------

+ Emoji Keyboard (Browser Stores)
@ https://emojigraph.org/copy-keyboard/

----------------------------------------------------------------

+ Complex Math Decals
@ https://docs.google.com/spreadsheets/d/1RWnirEml0mwf1ZaCgU7o5NvP1tShjQ-5VBOvP8Sxk5A/edit?gid=1454662175#gid=1454662175

----------------------------------------------------------------

+ Alphanumerics
@ http://dave-omega/ncsem/ncsem/Alphanumerics.html

----------------------------------------------------------------

+ Emoji Town
@ https://docs.google.com/spreadsheets/d/1mjEPxbb0hd35WhazL7IVFR93jdRu9gCla43k2V9hhQM/edit?gid=2093494326#gid=2093494326

----------------------------------------------------------------

+ Coding Emojis
@ http://dave-omega/ncsem/pubs/ncsem/Coding-Emojis.html

----------------------------------------------------------------

+ Reaction Emojis
@ https://dreamyguy.github.io/react-emojis/

----------------------------------------------------------------

+ Special Tokens
@ http://dave-omega/ncsem/pubs/ncsem/Special-Tokens.html

----------------------------------------------------------------

+ Compart Unicode
@ https://www.compart.com/en/unicode

----------------------------------------------------------------

+ Chrome Menu
@ http://dave-omega/ncsem/pubs/chrome-menu.html

----------------------------------------------------------------

+ Doc-Type Emojis
@ http://dave-omega/ncsem/pubs/doc-emojis.html

----------------------------------------------------------------

+ Game Pieces
@ http://dave-omega/ncsem/pubs/game-pieces.html

----------------------------------------------------------------

+ Kowabunga
@ http://dave-omega/ncsem/pubs/kowabunga.html

----------------------------------------------------------------

+ Tarzan's Critters
@ ( pending )

----------------------------------------------------------------

+ OS Decals
@ http://dave-omega/ncsem/pubs/os.html

----------------------------------------------------------------

+ Random Fun
@ http://dave-omega/ncsem/pubs/random-fun.html

----------------------------------------------------------------

+ Response Emojis
@ http://dave-omega/ncsem/pubs/response-emoji.html

----------------------------------------------------------------

+ Standard Theme Sets
@ http://dave-omega/ncsem/pubs/std-theme-sets.html

----------------------------------------------------------------

+ Vehical Decals
@ http://dave-omega/ncsem/pubs/vehicle-emojis.html

----------------------------------------------------------------

+ Weather Decals
@ http://dave-omega/ncsem/pubs/weather-emojis.html

----------------------------------------------------------------

+ Theme Sage Notebook
@ https://onedrive.live.com/personal/a698f7622548fa93/_layouts/15/Doc.aspx?sourcedoc={2548fa93-f762-2098-80a6-983202000000}

----------------------------------------------------------------

+ Werk Decals (Old)
@ http://dave-omega/ncsem/pubs/werk-emojis-old.html

----------------------------------------------------------------

+ Werk Decals
@ http://dave-omega/ncsem/pubs/werk-emojis.html

----------------------------------------------------------------

+ NCSEM
@ http://dave-omega/ncsem/
| Host := dave-omega

----------------------------------------------------------------

<script>
; doc = document
; doc . title = ( `Decal Sources` )
</script>

<script>
function mine( ev ) {
    ev.preventDefault();
    ev.stopPropagation();
}
</script>

<script>
function minnie( event ) {
    const ge = event.target;
    if ( ge.nodeName !== "LI" ) {
        return;
    }
    mine( event );
    if ( event.ctrlKey ) {
        prompt( "Item Content" , ge.textContent );
        return;
    } else {
        alert( "Hold Down Control to View" );
        return;
    }
}
</script>

<script>
addEventListener( "click", minnie );
</script>
