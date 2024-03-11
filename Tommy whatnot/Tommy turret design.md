---
excalidraw-plugin: parsed
tags: []
---

Designing a turret for Tommy's compound is not gonna be a simple task, however, it's probably one of the few compound defense designs I can feasibly do, since I lack an understanding of programming. This should be, in theory, more approachable as a whole. 


# The Big idea

The big idea is to create a turret shell (likely of sheet metal but really anything to cover up the internal mechanisms) that will house all the necessary parts of the turret, including room for cameras so we might track where the bad fellas are before we shoot them. 

The shell isn't the only thing though. Obviously we need some way to mount the gun in that protects the barrel from the elements, ideally increases accuracy, and holds the gun in place as the automated turret moves to aim at the target. 

The present idea in my head is as follows. Two prongs stick up from a swiveling plate controlled by a motor. These prongs will be connected at the top by two motors linked together software-side, and mechanically by their motor shafts. These will be attached to the actual turret housing containing infrared cameras, normal camera, motion detectors, etc. through a slot at the bottom. Above that will be a gun mount (or the fun mount, as I will be calling it) that adjusts to the size of the weapon by pushing it to the front and holding it in place from the sides (this may be done through straps, however the back, top, and bottom will almost certainly be done with a physical metal barrier being pushed up the the appropriate length) These barriers will likely be held in place by locking pins. The below image provides clarity. 

## Requirements 

- Secure turret housing that can face 135 degrees left and right from its installation angle (I'm presuming these will be mounted on the *corners* of compound walls) 
- Turret housing should be able to look directly up and basically completely up from its installation position
- Turret housing should support most any firearm, from AR's to pistols (but why would you)
- Turret housing has sufficient room for the camera equipment necessary for tracking raiders
- Mechanism ejecting an old magazine when gun is determined to be empty
- Spring loaded magazine feed that inserts a new mag when the old one is empty
- A mechanism to pull the trigger. 
## Nice to haves

- the protective barrel put onto the housing can be elongated and rifled specifically for the type of ammunition being shot. These will be easily screwed on and off when gun changes are necessary



# Prep - motors 

I've already run into a problem. Ya know that 135 degree movement? Also that direct up and down movement? That requires motors, and metal is heavy. An AR-15 weighs 7 pounds and the shell probably weighs far more, so I doubt a standard servo is fixing this problem. Before I can even begin research, I need to understand how to calculate the speed a motor can move different weights. 

Correction - I need to understand different motors capacity to move weight, and then I can calculate the speed at which it can do that and then factor in cost. 

This, however, all depend  s on what weight each motor needs to move. A preliminary design will determine that. Lets get started. 

# Preliminary design

I've taken the liberty of deciding that the longest gun we'll be encountering in this scenario is an AR-15. They're ~40 inches in length, which means we'll need a (slightly?) longer turret. presuming the smallest gun we're going to locate and use is that of a glock-19 (7inches), we'll presume that whatever mechanism we use to push the gun up to the barrel will accept 

[[fun mount rudamentary 1.excalidraw]]

