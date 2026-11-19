# Power selection and constraints

## 1. Amplifier options

My HiFi is currently housed in a Parker cabinet,

![Cabinet and speakers](images/cabinet-speakers.jpg)

For domestic harmony, I need to maintain or improve the look of the lounge room.

I haven't found a better alternate so the amplifier must go in the existing Parker cabinet.

The DiyAudio forums contain many cautions about placing Wolverine amplifiers in cabinets, and comments on the unpredictability of cooling depending on the exact placement.

The cabinet has an open back, but airflow is restricted so the Wolverine amplifier variant selected must be of relatively low heat output.

## 2. Power match with VAF i91 speaker

I am upgrading to a Wolverine in search of improved sound quality rather than volume. 

My VAF signature i91 mk1 speakers have nominal impedance 6Ω, and sensitivity 88 dB/W/m, max 150W.

My 40W per channel Exposure Super VX integrated amp drives these with ample volume for me; I listen at modest levels.

All Wolverine listed options are 100W or more, so I will have more than enough sound level (volume) capability. 

I'm upgrading for hoped gains in sound quality, not sound level (volume).  The reason to have a bit more is headroom for dynamics.


## 3. Selection of Wolverine EF3-n model and rail voltage

The Wolverine amplifier comes in variants EF3-3, EF3-4 and EF-3-5.  I select the **EF3-3** variant as it generates the least heat.

I also must select rail voltage.  Higher rail voltages increase output capability, but also generate more heat.

The build guide gives this advice for 2 channels at 4 ohms  (rearranged and culled to ignore high power variants)

| DC rail| Typical VA | 8Ω power W | AC V |
|--------|------------|------------|------|
|   49   |     500    |   100      |  35  |
|   49   |     600    |   120      |  35  | 
|   54   |     600    |   120      |  38  |
|   54   |     700    |   150      |  38  |
|   57   |     700    |   150      |  40  |
|   57   |     800    |   160      |  40  |
|   59   |     800    |   160      |  42  |

But 50V DC / 36 V AC with 600 VA seems enough.  

However, I note that the Toroidy 800vA is the same size as the 600vA, so I might pick **36 V AC with 800 VA**

One complexity is deciding what voltage of primary should be specified, based on my mains supply.
I've been measuring my mains supply for the past week, at different times of day.  
So far, it ranges from 230V AC to 240V AC. 
Mornings 230V, evenings 240V. 
I believe this is on the lower end of typical for Australian supply.
So my choices for spec'ing the tranformer primary are 230V, 240V or a custom 235V.
I'll get slightly different resulting actual rail voltages depending on which I choose.

I also have to pick the configuration, stereo, dual mono with 2 transformers in a single chassis, or 2 monoblocs

The pre-build guide says:

- For most builders, a conventional two-channel stereo amplifier in one chassis with one power supply is the best starting point. It is cheaper, simpler, easier to package, and fully adequate for normal home hi-fi. 
- Dual mono is worth considering if you specifically want stronger channel separation, have the chassis space and budget, and are comfortable planning two supply systems inside one enclosure. 
- Monoblocks are best reserved for builders who deliberately want separate amplifiers, have room for two chassis, and accept the extra cost and duplicated mains wiring. 
- If this is your first large amplifier build, choose a conservative configuration. Avoid high rail voltages, unnecessarily complex dual mono layouts, ... A clean, moderate, standard build is much more likely to succeed ...

Monoblocs are marginal in the cabinet regarding remaining gap for ventilation.

Dual mono is complex, but I like the idea of the better channel separation, and don't mind the extra cost, so I think I'll try that despite it being my first amplifier.
It better fits the objective of getting the best out of my VAF i91's, as far as practicable.

If I go for a dual mono with shared transformer, I'd pick 1 x 800 VA.
If I go for 2 independent transformers, I'd go for 2 x 400 VA.


## Mitigation for systemic overheating - Wolverine

I've decided to sell my turntable (Linn LP12 with SME IV arm), as I'm no longer using it.  
This gives more ventilation space in the cabinet (which has an open back)

I will build the preamp as a half width unit, so it can go in the turntable space with my half-width streamer.
This leaves a bigger free space for the power amplifier below.

Other things I might try if needed are:

- Move the cabinet forward to increase the gap at the wall from 65mm to something bigger.
- Moving the cabinet door forwards by putting the hinges on pads, to create a 10 mm perimeter gap.
- Removing the cabinet's glass door. (subject to the domestic harmony test)
- Fan blowing upwards from the base of the cabinet past the amplifiers (last resort)


# Preamp Power Requirements

I plan to build a standard "10 years after" Mezmerize.  

This is designed to run at 200mA and the official Salas BOM nominates a 50vA , 2 x 15 V transformer. 

The intended placement in the turntable area has limited ventilation.  If it gets too hot, the cabinet top lid gap can be increased. 