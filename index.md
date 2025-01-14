# THOREN: My humble keyboard
This is a small build log of my keyboard.

In early 2024 I've build my first split keyboard (slightly modified corne) and loved it.
I used boba u4 switches, end while they feel nice and barely make a sound, they felt somewhat heavy.
I wanted to try a smaller spaced low-profile keyboard, so I designed and ordered some PCBs. 
The layout is still very similar to corne, but the pinkie columns are slightly lower and I have an 
additional thumb key.


## Keyboard build
First step is soldering the hot swap sockets and diodes. 
After a first build I've found that the openings must be covered with e.g. electrical tape 
to prevent silicone from pouring in.
![Soldered pcb](./content/0-soldered.jpg)


After that, the silicone carcass is glued. I've used CA glue, however now I think
epoxy glue would be a much better choice. The surface is pretty big and the CA glue evaporates
quickly.
![Pcb with carcass](./content/1-glued.jpg)

To work with both V1 and V2 chocs I needed a button imitator.
First desgin was monolith, which proved to be a very bad desicion.
It tended to warp during printing and breaking a single pin would waste
the whole part. 
![Monolith button immitator](./content/2-bad-imitator.jpg)
A composit design with replacable individual parts for each button worked much better.
You can see a half-broken stem that to be replaced on the picture.
![Composit button immitator](./content/3-imitator.jpg)

Imitator is then installed and a first thin layer of silicone is poured.
![Pcb with immitator installed](./content/4-imitator-installed.jpg)
![Pcb after first layer pour](./content/5-first-pour.jpg)

Because the silicone carcass contains so many holes that trap air, and it will be 
covered to form a bottom surface, a vaccuum is needed to make a good pour before the cover is installed.
A first layer is needed to seal all of the through holes in the pcb, including
hot swap sockets. And if the holes in the sockets are not sealed 
during the vaccuumation, the experience shows that the silicone will get in :(
The first layer is not coverd, so any trapped air can be poked with a needle.

![Cover for the bottom surface](./content/6-cover.jpg)
The cover design took multiple iterations and proved that the carcass design is
suboptimal. Since there are only a few positioning holes for teh carcass, and multiple thin features, 
the dimensions of the carcass were slightly different and the cover would not make a prefrect fit.
The channels on the sides of the cover were made to ensure that the silicone can find a way out, but
are probably not required if the silicone is fresh. The silicone MUST be fresh and runny. If it's not fresh,
it is much more viscous and does not level under gravity well, which may cause bumps and uneven bottom surface.

To prevent silicone from running when it bubbles under vacuum, a temporary wall is installed.
![Pcb with side walls](./content/7-sides-installed.jpg)

After the silicone finished bubbling the side walls are removed and a cover is placed on top,
forcing the excess silicone out. I used office clamps to apply pressure, however in my case they sometimes 
applied too much force, which in combination with not perfect carcass/cover fit caused the cover to bend and 
form and uneven surface. Fortunately the silicone could be removed, allowing to repour again.
![Pcb pouring cover installed](./content/8-cover-installed.jpg)

Next, the cover and button immitator are removed.
![Pcb after second pour](./9-second-pour.jpg)
![Pcb after second pour](./10-imitator-removed.jpg)

Afterward, MCU sockets, buttons and battery are soldered. 
I find surface mounted sockets to be a great solution, they are easy to install, low-profile, and use
normal square pins, that can be easily bought and cut in length. My first split keyboard was built 
with thin round pins. I was unable to find where to buy fitting long pins without plastic spacer for a sane price.
The normal pins if cut flush under the plastic produce almost identical half-pins, reducing the work in half :)
![Pcb with mcu installed](./11-mcu-soldered.jpg)

Next the case and switches are installed.
The case is held in place entirely on the switches. I couldn't find a way to make a mounting solution that i liked,
but this proved to be good enough for me. The case is resing printed from an engineering resin.
![Keyboard without keycaps](./12-case-buttons.jpg)

When i bought switches, i did not realize that there are none commercial keycaps with 
compact spacing and mx stems (correct me if i'm wrong). I was going to use 3d printed ones anyways, but
a friend of mine was somewhat disappointed.  
To achieve the minimal thickess the keycaps also needed to be thin. The first iteration 
(now only used for 6th column) was super simple, 1mm thick keycaps, however it was almost impossible to
differentiate between keys. Later, when adding recess, i've entered 0.7mm depth cut, instead of 0.3mm. 
Surprisingly they printed, and the fingers felt perfect. This has bitten me later, when making thumb clusters.
Since the cut is longer, the super-thin 0.3mm part is also longer, and many, many keys were warped and craced after 
IPA cleaning ;(
![Keyboard with keycaps](./12-keycaps.jpg)
![Keyboard](./13-two-halves.jpg)
![Keyboard](./14-two-halves.jpg)
![Keyboard](./15-two-halves-top.jpg)
![ONLY 14 MM THICK](./16-thickness.jpg)

I am really happy that the whole board turned out to be only 14mm thick.

Now, to finish the project i wanted to make a carrying case. A simple FDM printed case with felt inlining.
![Empty case half](./17-empty-case.jpg)

A ribbon to extract the boards is glued in with dichloromethane.
![Emtpy case half with ribbon](./18-empty-case-ribbon.jpg)

Then a felt inline is glued, again with dicholoromethane.
![Case half with felt inline](./19-case-felt.jpg)

The second half has some 0.2mm thick covers to better hold the ribbon in place, 
since felt can be stretched easily (good thing i totally didn't make too many cases wihtout this feature)
![Second case half with ribbon](./20-case-second-half.jpg)

I tried using dichloromethane to glue the halves together, however it evaporated to quickly and even small 
smudges would make the side surfaces ugly. So i switched to epoxy glue to combine the halves togetner.
![Finished carrying case](./21-case-finished.jpg)


![Case with keyboard inside](./22-case-with-kb.jpg)
![Case with keyboard inside](./23-case-with-kb.jpg)
![Keyboard on desk](./24-on-desk.jpg)

Showcase video
![Showcase video](https://www.youtube.com/watch?v=WadnJnXvsTM)



















