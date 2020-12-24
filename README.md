# Tactical 6502/portable

My 2020 project.

Let me call it #6502portable.

It closes the loop between my starting point in 1986 and now. Like a Terminator time line, just backwards.

It's an Atari 800XL on a USB powerbank, video output captured into a Raspi on a 2nd powerbank.

Visuals inspired by Alien movie where computers look like they should. Released in 1979, the year of Atari 800.

I have rarely felt more satisfied.

#retrocomputing
#retrohardware
#atari8bit
#cyberdeck

## Atari 800XL in a box, portable

![](img/small-20201224_133731x-primary.jpg?raw=true)

![](img/small-20201224_132756x-primary.jpg?raw=true)

![](img/small-20201224_133119x-primary.jpg?raw=true)

![](img/small-20201224_132726x-primary.jpg?raw=true)

## Goal

Work on the Atari with the real feeling. But be independent of the
place in the living room.

## The idea

Two epiphanies: there is an Atari 800XL power cord to be fed with USB
on the other side. Power bank anyone? And there are video grabbers to
provide captured video as USB device readable by VLC. The rest is
history. Display on a Raspi. Put everything into a mobile suitcase.

## Challenges

1. Power support via USB is fragile when fed from a power bank. Every
   additional USB hub or cable makes it worse. Especially when driving
   raspi and display from a single powerbank.

1. Cable routing in limited space. Big respect to the first laptop builders.

## Where's the punk?

If this is cyber then where is the punk, I hear you ask.

My grandfather was a carpenter grandmaster. When he tried to teach me
when I was 10 he quickly gave up - I was not qualified. Carving the
front plate from wood anyway nearly 40 years later - that's my punk.

## VLC cmd line

> vlc --crop=444x271+20+52 --video-wallpaper --aspect-ratio=4:3 --no-video-title-show v4l:///dev/video0

## Open topics

1. No sound yet. Does the monitor output it, too?

1. GPIO not yet accessible at the front plate.

1. The video sometimes glitches. Interferences? Weak power? Looks great but irritates real work.

## Diary in pictures

![Power from USB](img/small-20200913_130039.jpg?raw=true)

![Monitor to s-video](img/small-20200913_131031.jpg?raw=true)

![Video grabber](img/small-20200913_131210.jpg?raw=true)

![Raspi 3B+ and 7-inch touchscreen](img/small-20200913_131343.jpg?raw=true)

![Atari 800XL](img/small-20200913_131920.jpg?raw=true)

![](img/small-20200913_131955.jpg?raw=true)

![](img/small-20200913_132049.jpg?raw=true)

![](img/small-20200913_132103.jpg?raw=true)

![](img/small-20200913_132109.jpg?raw=true)

![Powerbank](img/small-20200913_132319.jpg?raw=true)

![Sio2sd from Lotharek, SD card with disk images](img/small-20200913_132546.jpg?raw=true)

![](img/small-20200913_133207.jpg?raw=true)

![](img/small-20200913_133313.jpg?raw=true)

![](img/small-20200913_133349.jpg?raw=true)

![Raspi 3B durign prototyping, later 3B+](img/small-20200913_134218.jpg?raw=true)

![](img/small-20200913_145723.jpg?raw=true)

![](img/small-20200913_151214.jpg?raw=true)

![syslog video grabber](img/small-20200913_161941.jpg?raw=true)

![/dev/video](img/small-20200913_162149.jpg?raw=true)

![VLC](img/small-20200913_162327.jpg?raw=true)

![](img/small-20200913_162400.jpg?raw=true)

![Proof of concept](img/small-20200913_162414.jpg?raw=true)

![](img/small-20200913_162744.jpg?raw=true)

![ATMAS-II booting](img/small-20200913_182011.jpg?raw=true)

![ATMAS-II](img/small-20200913_182059.jpg?raw=true)

![](img/small-20201007_093419.jpg?raw=true)

![Suitcase](img/small-20201118_142718.jpg?raw=true)

![](img/small-20201118_142811.jpg?raw=true)

![](img/small-20201118_142932.jpg?raw=true)

![](img/small-20201118_143040.jpg?raw=true)

![](img/small-20201118_143134.jpg?raw=true)

![](img/small-20201118_150324.jpg?raw=true)

![](img/small-20201118_151641.jpg?raw=true)

![](img/small-20201118_152242.jpg?raw=true)

![](img/small-20201118_160745.jpg?raw=true)

![](img/small-20201118_162930.jpg?raw=true)

![](img/small-20201118_163006.jpg?raw=true)

![](img/small-20201118_175802.jpg?raw=true)

![](img/small-20201118_181158.jpg?raw=true)

![](img/small-20201121_131843.jpg?raw=true)

![Front plate, initial max size](img/small-20201121_133653.jpg?raw=true)

![](img/small-20201121_135625.jpg?raw=true)

![](img/small-20201122_175221.jpg?raw=true)

![](img/small-20201122_183450.jpg?raw=true)

![](img/small-20201122_184813.jpg?raw=true)

![](img/small-20201122_220738.jpg?raw=true)

![](img/small-20201122_220838.jpg?raw=true)

![Front plate, shrunk for deeper position](img/small-20201128_164330.jpg?raw=true)

![](img/small-20201128_172726.jpg?raw=true)

![](img/small-20201128_175234.jpg?raw=true)

![](img/small-20201128_183017.jpg?raw=true)

![](img/small-20201206_114325.jpg?raw=true)

![Screews to wood, glue to plastics](img/small-20201206_143323.jpg?raw=true)

![](img/small-20201206_143403.jpg?raw=true)

![](img/small-20201206_144725.jpg?raw=true)

![](img/small-20201206_144856.jpg?raw=true)

![](img/small-20201213_145247.jpg?raw=true)

![Heavy Metal, we are in space after all](img/small-20201213_145321.jpg?raw=true)

![](img/small-20201213_151841.jpg?raw=true)

![](img/small-20201213_160527.jpg?raw=true)

![](img/small-20201213_160533.jpg?raw=true)

![](img/small-20201213_160621.jpg?raw=true)

![Foam nearly ruined from too many experimenting](img/small-20201213_162407.jpg?raw=true)

![](img/small-20201213_162533.jpg?raw=true)

![](img/small-20201213_164418.jpg?raw=true)

![](img/small-20201213_165249.jpg?raw=true)

![](img/small-20201213_170112.jpg?raw=true)

![](img/small-20201213_170520.jpg?raw=true)

![Protect the innocent](img/small-20201213_170927.jpg?raw=true)

![](img/small-20201213_203421.jpg?raw=true)

![](img/small-20201213_203759.jpg?raw=true)

![Wear a mask](img/small-20201213_205440.jpg?raw=true)

![](img/small-20201220_183610.jpg?raw=true)

![](img/small-20201221_141609.jpg?raw=true)

![Thin foam base](img/small-20201221_142027.jpg?raw=true)

![](img/small-20201221_170721.jpg?raw=true)

![If in doubt use the big powerbank that normally starts The Last V8](img/small-20201222_112538.jpg?raw=true)

![Stencils](img/small-20201222_114536.jpg?raw=true)

![](img/small-20201222_115518.jpg?raw=true)

![Inner usb hub, soldered switch to be shut off devices](img/small-20201222_132401.jpg?raw=true)

![Big switch to disconnect inner usb hub (where video grabber), eg. for power saving](img/small-20201222_133757.jpg?raw=true)

![GPIO prepared, but not yet outside](img/small-20201222_135153.jpg?raw=true)

![](img/small-20201222_135227.jpg?raw=true)

![The Switch](img/small-20201222_151413.jpg?raw=true)

![](img/small-20201222_151420.jpg?raw=true)

![](img/small-20201222_180220.jpg?raw=true)

![ATMAS-II](img/small-20201222_180230.jpg?raw=true)

![](img/small-20201222_180236.jpg?raw=true)

![](img/small-20201222_180245.jpg?raw=true)

![Additional keyboard mountable for longer Raspi work](img/small-20201222_180430.jpg?raw=true)

![](img/small-20201222_180841.jpg?raw=true)

![](img/small-20201222_180849.jpg?raw=true)

![](img/small-20201222_180939.jpg?raw=true)

![](img/small-20201222_180943.jpg?raw=true)

![](img/small-20201222_180945.jpg?raw=true)

![](img/small-20201222_183402.jpg?raw=true)

![Cutting stencils manually](img/small-20201222_185648.jpg?raw=true)

![](img/small-20201222_190606.jpg?raw=true)

![](img/small-20201222_194139.jpg?raw=true)

![](img/small-20201222_195158.jpg?raw=true)

![](img/small-20201223_100622.jpg?raw=true)

![](img/small-20201223_100854.jpg?raw=true)

![](img/small-20201223_100905.jpg?raw=true)

![](img/small-20201223_102642.jpg?raw=true)

![](img/small-20201223_102746.jpg?raw=true)

![](img/small-20201223_103208.jpg?raw=true)

![](img/small-20201223_103433.jpg?raw=true)

![](img/small-20201223_103915.jpg?raw=true)

![](img/small-20201223_103936.jpg?raw=true)

![](img/small-20201224_113913.jpg?raw=true)

![](img/small-20201224_113934.jpg?raw=true)

![](img/small-20201224_114013.jpg?raw=true)

![Blutooth mini keyboard place](img/small-20201224_114037.jpg?raw=true)

![](img/small-20201224_114236.jpg?raw=true)

![DATA, POWER, USB OFF](img/small-20201224_132726x-primary.jpg?raw=true)

![](img/small-20201224_132756x-primary.jpg?raw=true)

![](img/small-20201224_132814.jpg?raw=true)

![](img/small-20201224_132829.jpg?raw=true)

![](img/small-20201224_133000.jpg?raw=true)

![](img/small-20201224_133024.jpg?raw=true)

![](img/small-20201224_133049.jpg?raw=true)

![](img/small-20201224_133059.jpg?raw=true)

![](img/small-20201224_133119x-primary.jpg?raw=true)

![](img/small-20201224_133140.jpg?raw=true)

![](img/small-20201224_133155.jpg?raw=true)

![](img/small-20201224_133247.jpg?raw=true)

![](img/small-20201224_133533.jpg?raw=true)

![](img/small-20201224_133731x-primary.jpg?raw=true)

![](img/small-20201224_133842.jpg?raw=true)

![](img/small-20201224_133905.jpg?raw=true)

![Mig Alley Ace](img/small-20201224_134748.jpg?raw=true)

## License

(c) 2020 ![eiZen](https://mastodon.social/@eiZen)

Instructions, text and images can be used freely.

Attribution 4.0 International - [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
