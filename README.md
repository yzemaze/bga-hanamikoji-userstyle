# bga-hanamikoji-userstyle
Userstyle/CSS for Hanamikoji on BGA.

## Features
- reduced whitespace/margins (cf. <a href="https://boardgamearena.com/bug?id=86955">bug 86955</a>)
- a fixed spot for waiting_card_zone (cf. <a href="https://boardgamearena.com/bug?id=86954">bug 86954</a>)

## Prerequisites
<a href="https://github.com/openstyles/stylus#readme">Stylus</a> or some other way to apply a .user.styl or css to websites.

## Notes
It should work fine on windows/screens 1280px or wider and with "Player area position" set to "Above". Some margins are pretty tight. So in some edge cases cards overlap other graphics slightly (e.g. 5*5).

<a href="https://boardgamearena.com/archive/replay/230419-1000/?table=369789824&player=1259869&comments=1259869;">test-game</a> (choose 1 out of 3 as 1st play from opponent)

Remove `regexp("https://boardgamearena.com/archive/replay/.*")` from moz-doc after testing.

## Screenshots
… with exactly the same dimensions. (Please just ignore the grey background. I use it everywhere on BGA.)

Beta published on BGA 2023/04/23
![screenshot_beta](/BGA_Hanamikoji.png?raw=true)

With my .user.styl activated:
![screenshot_userstyle](/BGA_Hanamikoji_CSS.png?raw=true)
