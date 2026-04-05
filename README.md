<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 520" width="700" height="455">
  <style>
    .trunk { fill: none; stroke: #8B7340; stroke-width: 2; }
    .branch { fill: none; stroke: #8B7340; stroke-width: 1.5; stroke-linecap: round; }
    .twig { fill: none; stroke: #9E8A5A; stroke-width: 1; stroke-linecap: round; }
    .leaf { fill: #7A8C4E; opacity: 0.8; }
    .leaf-alt { fill: #5C6E3A; opacity: 0.7; }
    .root { fill: none; stroke: #8B7340; stroke-width: 1.5; stroke-linecap: round; }
    .knot { fill: none; stroke: #8B7340; stroke-width: 1.8; stroke-linecap: round; stroke-linejoin: round; }
    .title-text { font-family: Georgia, 'Times New Roman', serif; fill: #6B5B3A; font-size: 36px; letter-spacing: 6px; }
    .subtitle-text { font-family: Georgia, 'Times New Roman', serif; fill: #8B7340; font-size: 14px; letter-spacing: 4px; font-style: italic; }
    .ornament { fill: none; stroke: #B8A66E; stroke-width: 1; }
    .ornament-dot { fill: #B8A66E; }
    .border-line { fill: none; stroke: #C9B97A; stroke-width: 0.5; opacity: 0.6; }
    @media (prefers-color-scheme: dark) {
      .trunk, .branch, .knot { stroke: #C9A84C; }
      .twig, .root { stroke: #B8975A; }
      .leaf { fill: #8FA85E; opacity: 0.75; }
      .leaf-alt { fill: #6E8544; opacity: 0.65; }
      .title-text { fill: #D4C088; }
      .subtitle-text { fill: #C9A84C; }
      .ornament { stroke: #C9A84C; }
      .ornament-dot { fill: #C9A84C; }
      .border-line { stroke: #A08840; opacity: 0.4; }
    }
  </style>

  <!-- Outer border - double line -->
  <rect x="20" y="15" width="760" height="490" rx="8" class="border-line"/>
  <rect x="26" y="21" width="748" height="478" rx="6" class="border-line"/>

  <!-- Corner ornaments -->
  <!-- Top left -->
  <circle cx="38" cy="33" r="3" class="ornament-dot"/>
  <path d="M 38 40 Q 38 33 45 33" class="ornament"/>
  <path d="M 38 48 Q 38 33 53 33" class="ornament"/>
  <!-- Top right -->
  <circle cx="762" cy="33" r="3" class="ornament-dot"/>
  <path d="M 762 40 Q 762 33 755 33" class="ornament"/>
  <path d="M 762 48 Q 762 33 747 33" class="ornament"/>
  <!-- Bottom left -->
  <circle cx="38" cy="487" r="3" class="ornament-dot"/>
  <path d="M 38 480 Q 38 487 45 487" class="ornament"/>
  <path d="M 38 472 Q 38 487 53 487" class="ornament"/>
  <!-- Bottom right -->
  <circle cx="762" cy="487" r="3" class="ornament-dot"/>
  <path d="M 762 480 Q 762 487 755 487" class="ornament"/>
  <path d="M 762 472 Q 762 487 747 487" class="ornament"/>

  <!-- ====== THE TREE ====== -->
  <!-- Main trunk -->
  <path d="M 400 340 C 398 300, 395 280, 392 250 C 390 230, 394 210, 396 190 C 397 175, 395 160, 394 145" class="trunk"/>
  <path d="M 400 340 C 402 305, 406 285, 408 255 C 410 235, 406 215, 404 195 C 403 178, 406 162, 406 148" class="trunk"/>

  <!-- Celtic knotwork on trunk -->
  <path d="M 396 310 C 390 300, 410 290, 404 280" class="knot"/>
  <path d="M 404 310 C 410 300, 390 290, 396 280" class="knot"/>
  <path d="M 397 275 C 392 265, 408 258, 403 248" class="knot"/>
  <path d="M 403 275 C 408 265, 392 258, 397 248" class="knot"/>

  <!-- Major branches - left -->
  <path d="M 394 200 C 375 185, 340 170, 300 155" class="branch"/>
  <path d="M 392 220 C 365 205, 330 200, 280 195" class="branch"/>
  <path d="M 393 175 C 380 155, 355 140, 320 120" class="branch"/>
  <path d="M 394 160 C 388 140, 370 115, 350 95" class="branch"/>

  <!-- Major branches - right -->
  <path d="M 406 200 C 425 185, 460 170, 500 155" class="branch"/>
  <path d="M 408 220 C 435 205, 470 200, 520 195" class="branch"/>
  <path d="M 407 175 C 420 155, 445 140, 480 120" class="branch"/>
  <path d="M 406 160 C 412 140, 430 115, 450 95" class="branch"/>

  <!-- Crown top -->
  <path d="M 395 148 C 393 130, 388 110, 380 90" class="branch"/>
  <path d="M 405 148 C 407 130, 412 110, 420 90" class="branch"/>
  <path d="M 400 145 C 400 125, 400 105, 400 80" class="branch"/>

  <!-- Twigs left -->
  <path d="M 340 170 C 330 160, 315 155, 295 150" class="twig"/>
  <path d="M 310 195 C 295 188, 275 185, 255 185" class="twig"/>
  <path d="M 350 140 C 340 130, 325 118, 305 108" class="twig"/>
  <path d="M 320 120 C 308 108, 290 100, 270 92" class="twig"/>
  <path d="M 280 195 C 265 190, 248 192, 235 200" class="twig"/>
  <path d="M 300 155 C 285 148, 268 145, 250 148" class="twig"/>
  <path d="M 380 90 C 368 78, 352 72, 335 70" class="twig"/>
  <path d="M 350 95 C 340 82, 325 72, 308 68" class="twig"/>

  <!-- Twigs right -->
  <path d="M 460 170 C 470 160, 485 155, 505 150" class="twig"/>
  <path d="M 490 195 C 505 188, 525 185, 545 185" class="twig"/>
  <path d="M 450 140 C 460 130, 475 118, 495 108" class="twig"/>
  <path d="M 480 120 C 492 108, 510 100, 530 92" class="twig"/>
  <path d="M 520 195 C 535 190, 552 192, 565 200" class="twig"/>
  <path d="M 500 155 C 515 148, 532 145, 550 148" class="twig"/>
  <path d="M 420 90 C 432 78, 448 72, 465 70" class="twig"/>
  <path d="M 450 95 C 460 82, 475 72, 492 68" class="twig"/>

  <!-- Leaves - left side (small ellipses) -->
  <ellipse cx="290" cy="148" rx="5" ry="3" transform="rotate(-30 290 148)" class="leaf"/>
  <ellipse cx="270" cy="90" rx="5" ry="3" transform="rotate(-20 270 90)" class="leaf-alt"/>
  <ellipse cx="252" cy="146" rx="4" ry="2.5" transform="rotate(-45 252 146)" class="leaf"/>
  <ellipse cx="255" cy="183" rx="5" ry="3" transform="rotate(-15 255 183)" class="leaf-alt"/>
  <ellipse cx="235" cy="198" rx="5" ry="3" transform="rotate(-40 235 198)" class="leaf"/>
  <ellipse cx="305" cy="106" rx="4" ry="2.5" transform="rotate(-25 305 106)" class="leaf"/>
  <ellipse cx="295" cy="150" rx="4" ry="3" transform="rotate(-55 295 150)" class="leaf-alt"/>
  <ellipse cx="335" cy="68" rx="5" ry="3" transform="rotate(-10 335 68)" class="leaf"/>
  <ellipse cx="308" cy="66" rx="4" ry="2.5" transform="rotate(-30 308 66)" class="leaf-alt"/>
  <ellipse cx="248" cy="150" rx="4" ry="2.5" transform="rotate(15 248 150)" class="leaf"/>
  <ellipse cx="275" cy="185" rx="4" ry="3" transform="rotate(-60 275 185)" class="leaf-alt"/>

  <!-- Leaves - right side -->
  <ellipse cx="510" cy="148" rx="5" ry="3" transform="rotate(30 510 148)" class="leaf"/>
  <ellipse cx="530" cy="90" rx="5" ry="3" transform="rotate(20 530 90)" class="leaf-alt"/>
  <ellipse cx="548" cy="146" rx="4" ry="2.5" transform="rotate(45 548 146)" class="leaf"/>
  <ellipse cx="545" cy="183" rx="5" ry="3" transform="rotate(15 545 183)" class="leaf-alt"/>
  <ellipse cx="565" cy="198" rx="5" ry="3" transform="rotate(40 565 198)" class="leaf"/>
  <ellipse cx="495" cy="106" rx="4" ry="2.5" transform="rotate(25 495 106)" class="leaf"/>
  <ellipse cx="505" cy="150" rx="4" ry="3" transform="rotate(55 505 150)" class="leaf-alt"/>
  <ellipse cx="465" cy="68" rx="5" ry="3" transform="rotate(10 465 68)" class="leaf"/>
  <ellipse cx="492" cy="66" rx="4" ry="2.5" transform="rotate(30 492 66)" class="leaf-alt"/>
  <ellipse cx="552" cy="150" rx="4" ry="2.5" transform="rotate(-15 552 150)" class="leaf"/>
  <ellipse cx="525" cy="185" rx="4" ry="3" transform="rotate(60 525 185)" class="leaf-alt"/>

  <!-- Leaves - top -->
  <ellipse cx="400" cy="78" rx="4" ry="3" transform="rotate(0 400 78)" class="leaf"/>
  <ellipse cx="390" cy="85" rx="5" ry="3" transform="rotate(-15 390 85)" class="leaf-alt"/>
  <ellipse cx="410" cy="85" rx="5" ry="3" transform="rotate(15 410 85)" class="leaf"/>
  <ellipse cx="382" cy="75" rx="4" ry="2.5" transform="rotate(-25 382 75)" class="leaf-alt"/>
  <ellipse cx="418" cy="75" rx="4" ry="2.5" transform="rotate(25 418 75)" class="leaf"/>

  <!-- ====== ROOTS ====== -->
  <path d="M 400 340 C 395 355, 380 370, 360 385 C 345 395, 320 400, 290 405" class="root"/>
  <path d="M 400 340 C 405 355, 420 370, 440 385 C 455 395, 480 400, 510 405" class="root"/>
  <path d="M 398 340 C 392 360, 375 380, 350 400 C 335 410, 310 418, 280 425" class="root"/>
  <path d="M 402 340 C 408 360, 425 380, 450 400 C 465 410, 490 418, 520 425" class="root"/>
  <path d="M 399 342 C 397 365, 400 390, 400 415 C 400 430, 398 440, 395 450" class="root"/>
  <path d="M 401 342 C 403 365, 400 390, 402 415 C 403 430, 406 440, 410 450" class="root"/>

  <!-- Small root tendrils -->
  <path d="M 290 405 C 278 408, 265 405, 255 410" class="twig"/>
  <path d="M 510 405 C 522 408, 535 405, 545 410" class="twig"/>
  <path d="M 280 425 C 268 428, 258 432, 248 430" class="twig"/>
  <path d="M 520 425 C 532 428, 542 432, 552 430" class="twig"/>
  <path d="M 395 450 C 388 455, 380 452, 372 458" class="twig"/>
  <path d="M 410 450 C 417 455, 425 452, 432 458" class="twig"/>

  <!-- ====== TEXT ====== -->
  <text x="400" y="490" text-anchor="middle" class="subtitle-text">GARDENER · TOOLMAKER · CHRONICLER</text>

  <!-- Horizontal ornament lines flanking subtitle -->
  <line x1="160" y1="488" x2="258" y2="488" class="ornament"/>
  <line x1="542" y1="488" x2="640" y2="488" class="ornament"/>
  <circle cx="155" cy="488" r="2" class="ornament-dot"/>
  <circle cx="645" cy="488" r="2" class="ornament-dot"/>

</svg>

</div>

---

<div align="center">

### ✦ &nbsp; The Works & Wanderings of Alun &nbsp; ✦

</div>

&nbsp;

> *Here are set down the works and paths of one who, though no botanist by training, has long tended the garden where plant science meets the wider world — sixteen years and counting at the crossroads of code and chlorophyll.*

&nbsp;

**[Botany One](https://botany.one)** · *The chief work.* A plant science website where research meets readership. News, commentary, tools, and games — all in service of making botany a little more visible in the world.

**[Natur Wyllt](https://alunsalt.github.io/natur-wyllt/)** · *Y prosiect natur.* A Welsh-language nature observation project, recording the wild things found close to home.

**[Y Blog Cymraeg](https://bywyd.mymagic.page)** · *Ysgrifennu yn Gymraeg.* A personal blog in Welsh — written by a learner, for the practice of it, and for the love of the language.

&nbsp;

<div align="center">

✦

</div>

&nbsp;

<div align="center">

[Mastodon (Toot Wales)](https://toot.wales/deck/@alun) &nbsp;·&nbsp; [Bluesky](https://bsky.app/profile/alunsalt.bsky.social) &nbsp;·&nbsp; [LinkedIn](www.linkedin.com/in/alun-salt-6a3653104)

</div>

&nbsp;

<div align="center">

---

<sub>✧ &nbsp; *Every tree has its enemy, few have an advocate.* - Tolkien &nbsp; ✧</sub>

</div>
