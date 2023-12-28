## 👋 Hello there! My name is
```Javascript
┌────┐┌─┐ __┌─┐┌─┐ ┌───┐┌───┐┌────┐
│  ──┤│ │/ /│ └┘ │ │ │ ││ │ ││  ──┤
├──  ││   < \___ │ │ │ ││ ┌─┘├──  │
└────┘│_│\_\ |___/ └───┘└─┘  └────┘
```
here on github 

Also named SkyHops, Skyia or Enkyia

## Currently working on:
- Web games prototypes; client side only is just temp.
- Javascript modules; canvas overlay editor tool stats graphic.
- Mouse pointer and cursors; file format png gif cur ani.

## Portfolio
Current broken website upload was for test of a game project.

[skyops117.github.io](https://skyops117.github.io/)

## Game mod page

 <strong>Was</strong> or <strong>might continue</strong> making Fallout 76 interface mods . . .
 
🔗 My nexus mod profile: [![BunnyHopsIn](https://images.nexusmods.com/favicons/ReskinOrange/favicon-16x16.png)](https://www.nexusmods.com/users/4382192?tab=user+files) 

🔥 ~ ~ ~ ~ ~ B̦͊-̜̬̳̾̂̏̾ͯ̎R͔̺̜̥̹͕̂̌̇ͭ̿̃̾͐-͚̞̜͚̫̞͉͍̯̐̔ͪ͂ͥ̂͂ͮ̓̚O͇̦̪̩͕̞̞̗̳̞̠̥͊ͬ͋̇̓͑ͣ̐ͦ̐-̗͎̞̺̤͚̯̣̟̗̦̮̪̮̯͌̍ͦ̏͛ͧ͗̆ͮ̔K̥͈͓̮̞̬̤̥̝̺̳͉͉̝͓̖̝̤͋̾̈̎̇͗ͧ̇͐͂-̱̖̬̞͙̤̠͖̦̦͕̻̭̯̙̫̤͉̘̈́̾͒̿͒̔͗͛ͨͩͅͅḚ̺̱͎̮̣̖̻͇̳̩͙͈͍͙̹̯͖̘̞͙̫͔̆̂͐͊̓̓͂̓͂-̖̪̻̟̞̬̳̲̲̝͓̪̮̹̙̗͖͈͕͇͚̮͖̻̊ͪ̍̃ͫ͌́ͅͅN̰̟͈̮͕̰͕̱̬̙͉͈̞̭̹̳̪̞̠̻͉̭̤̮̘͈̼͕̋̀̐̀ͤͅ-̜̮̼̫̤̬̰̳͓̗͙̼̞̠̥͙̞͙̝̭͍̩̰̪̰̗̭̝̟̽͂ͣ́͗H̲͖͇̲̻̥̜̻̬̼̺̩̝̘͕͈̪̬̘͇̙̫͕͔̰͚̃̈ͩ̉ͬ̐͂-̹̭̝̗̥̰̫̫̦̲̗̣̭͍̙̞̺̥̘̝͖̝͑̆͆͋͋́̂ͣ͑ͅE̠͇̞̦̥̙̤̟̺͍͙͓͖͓͍͈͙̞͚̞̯͛̍͐̓ͬͩ̆ͧ̃̚-̲͕̲̟̞̱̭̙̼̼͈̟̥̰̳̮͙ͭ͐̊̔ͫ̽ͧ̿ͤͥͅA̯̜̟̘̲̯̦͉̖͍̫̼̲̙͉ͬ̑̋ͬ̆̂̐̐̍̍-͖̬͎̫̠̻͚̗͕̩̟ͯ̾̌ͪͪ́͊̿̿̒ͅR͚͔̠̟̟͎̱̤̣͛͗̍̉ͬͩͨ̾̎ͣ-͕͇̪̙̮͍̽ͭ̎͊̓͊̾͗T̹̦̞͛̄͒ͦͤͩ ~ ~ ~ ~ ~ ~ =>

### diacritical example with accents

When not handled properly, diacritrical characters can make leak effects outside it's container

<br><br><br>

## My customization of an SVG example

After the SVG edit, we can convert them to popular rasterized formats.

<img src="./png/github-octocat-diff-preview.png" alt="" />

## Animated SVG

<img src="https://raw.githubusercontent.com/SkyOps117/SkyOps117/main/retro.svg" alt=""/> 

## Javascript example

```Javascript
//  _____                              
// |  ___| __ __ _ _ __ ___   ___ 
// | |_ | '__/ _` | '_ ` _ \ / _ \
// |  _|| | | (_| | | | | | |  __/
// |_|  |_|  \__,_|_| |_| |_|\___|
//  ____       _       
// |  _ \ __ _| |_ ___ 
// | |_) / _` | __/ _ \
// |  _ < (_| | ||  __/
// |_| \_\__,_|\__\___|
//
// ╔═══════════════════════════════╗ 
// ║ Frames per second  statisticz ║
// ║    Javascript module class    ║
// ║         By SkyOps117          ║
// ╚═══════════════════════════════╝
// fps.js
// Frames per second class
// Author: SkyHops
export default class FPS {
  startTime; value; frames;
  // Init attributes to 0 and set startTime
  constructor() {
    this.startTime = performance.now();
    this.value = 0; // float milliseconds value
    this.frames = 0; // Milliseconds
  }
  // Update class attributes value and return fps value as a String
  update() {
    // Get current total time
    const t = performance.now();
    // Get delta time
    const dt = t - this.startTime;
    // Reset frames at 1 second delta time
    if (dt > 1000) {
      this.value = Math.floor(this.frames * 1000 / dt);
      this.frames = 0;
      this.startTime = t;
    } 
    else {
      this.frames++;
    }
    // Return condition
    return (this.value <= 0) ? this.frames : this.value;
  }
}
```
Keyboard text art

```
  _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____________ 
 || # ||| 1 ||| 2 ||| 3 ||| 4 ||| 5 ||| 6 ||| 7 ||| 8 ||| 9 ||| 0 ||| - ||| = |||     ⟵    ||
 ||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___________||
 |/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___________\|
  _______ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ ___________ 
 || tab ||| Q ||| W ||| E ||| R ||| T ||| Y ||| U ||| I ||| O ||| P ||| [ ||| ] |||    \    ||
 ||_____|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||_________||
 |/_____\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/_________\|
  __________ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ ______________ 
 ||  caps  ||| A ||| S ||| D ||| F ||| G ||| H ||| J ||| K ||| L ||| ; ||| ` |||    enter   ||
 ||________|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||____________||
 |/________\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/____________\|
  _____________ _____ _____ _____ _____ _____ _____ _____ _____ _____ _____ _________________ 
 ||   shift   ||| Z ||| X ||| C ||| V ||| B ||| N ||| M ||| ' ||| . ||| / |||     shift     ||
 ||___________|||___|||___|||___|||___|||___|||___|||___|||___|||___|||___|||_______________||
 |/___________\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/___\|/_______________\|
  ________ ______ _______ ____________________________________ _______ ______ ______ ________ 
 || ctrl ||| 🗔 ||| alt |||                ____              ||| alt ||| fn ||| 🖺 ||| ctrl ||
 ||______|||____|||_____|||__________________________________|||_____|||____|||____|||______||
 |/______\|/____\|/_____\|/__________________________________\|/_____\|/____\|/____\|/______\|
```
<!-- 
### My profile description as svg into the markdown as test.
<img src="./README.svg" alt="" />
-->
