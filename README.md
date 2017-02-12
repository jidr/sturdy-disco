# Sturdy Disco 
## Vinyl ~~Auto~~ Rewinder

A hack for [Stupid Hackathon Sweden](http://www.stupidhackathon.se)

    ________________ 
    < vinyl rewinder >
    ---------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||


## Gist

Wouldn't it be nice if you could rewind that vinyl you borrowed before returning it? Or if you could just play side a over and over again?

### Hardware
One Aiwa PX-E860<br>
Some switches<br>
[H-Bridge](https://www.pololu.com/product/713)
5V voltage regulator<br>
Breadboard and wires<br>
 - In retrospect, 840 holes was excessive

 
## Abbrevated build log
* Found a service manual.
* There are two switches internally, can we wire one to make it go backwards?
  * Nope they work in tandem to start the pickup and then play the record.
* Does the motor even work in reverse? Reverse polarity, yeah that works.
* [Ok, let's see if we can make it work manually.](/img/breadboard.jpg) (this one line entry took us hours to get right)
  * [Yup, that works.](https://youtu.be/JC7FB6oPfiM)
* Right, tidy it up.