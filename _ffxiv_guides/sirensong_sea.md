---
layout: guide_post
title:  "The Sirensong Sea"
date:   2017-04-09 18:00:14 -0300
image:
    - url: "/assets/img/dungeons/sirensong_sea.jpg"
    - urlSmall: "/assets/img/dungeons/small/sirensong_sea.jpg"
patchNumber: 4.0
patchName: "Stormblood"
plvl: "61"
instanceType: "dungeon"
mtqvid: "https://youtu.be/2ma65teviMM"
bosses:
  - title: "Lugat"
    attacks:
      - title: "Amorphous Applause"
        phases:
          - phase: 01
        roles:
          - role: "Everyone"
        tags:
          - tag: "Area AoE"
        notes:
          - note: "This attack targets a single player and hits with a 180 degree area AoE - run behind the boss to avoid taking damage."
      - title: "Hydroball"
        phases:
          - phase: 01
        roles:
          - role: "Everyone"
        tags:
          - tag: "Stack"
        notes:
          - note: "A player will be marked with a stack marker - the group should pull in to soak damage."
      - title: "Sea Swallows All & Concussive Oscillation"
        phases:
          - phase: 01
        combo:
          - title: "Sea Swallows All"
            roles:
              - role: "Everyone"
            tags:
              - tag: "Pull"
            notes:
              - note: "This attack will pull all players in to the boss and immediately follow up with Concussive Oscillation."
          - title: "Concussive Oscillation"
            roles:
              - role: "Everyone"
            tags:
              - tag: "Circular AoE"
            notes:
              - note: "This attack follows Sea Swallows All and places multiple circular AoEs in a pattern on the arena."
      - title: "Overtow"
        phases:
          - phase: 01
        roles:
          - role: "Everyone"
        tags:
          - tag: "Knockback"
        notes:
          - note: "This attack will knock a single player back and is often followed up by Hydroball - be sure to return to the group to soak damage."
    sequence:
      - phase: 01
        attacks:
          - attack: "Amorphous Applause"
          - attack: "Hydroball"
          - attack: "Sea Swallows All & Concussive Oscillation"
          - attack: "Overtow"
        alerts:
          - alert: "This boss has a few attacks that will push and pull players - be ready to move out of AoEs."
  - title: "The Governor"
    attacks:
      - title: "Shadowflow"
        phases:
          - phase: 01
        roles:
          - role: "Everyone"
        tags:
          - tag: "Radial Cone AoE"
        notes:
          - note: "Shadowflow will spawn alternating cone AoE and safe zones."
          - note: "Stand in between the AoE zones to avoid damage."
      - title: "Bloodburst"
        phases:
          - phase: 01
        roles:
          - role: "Healer"
        tags:
          - tag: "Raid Wide AoE"
        notes:
          - note: "Healers should keep an eye out for this attack and heal everyone up as needed."
      - title: "Enter Night"
        phases:
          - phase: 01
        roles:
          - role: "Everyone"
        tags:
          - tag: "Tether"
        notes:
          - note: "This attack will pull the player in and tether them with a grey/purple smoke-like tether - players should immediately run away from the boss to break the tether and avoid the stacking debuffs they will receive."
      - title: "Shadowsplit & Shadowflow"
        phases:
          - phase: 01
        combo:
          - title: "Shadowsplit"
            roles:
              - role: "Everyone"
            tags:
              - tag: "Circular AoE"
            notes:
              - note: "The boss will spawn multiple Shadowsplit adds that will drop circular pools within the typical safe zones of Shadowflow - watch their pattern of movement to determine where they will drop."
          - title: "Shadowflow"
            roles:
              - role: "Everyone"
            tags:
              - tag: "Radial Cone AoE"
            notes:
              - note: "Shadowflow will spawn alternating cone AoE and safe zones."
              - note: "Stand in between the AoE zones to avoid damage."
    sequence:
      - phase: 01
        attacks:
          - attack: "Shadowflow"
          - attack: "Bloodburst"
          - attack: "Enter Night"
          - attack: "Shadowsplit & Shadowflow"
        alerts:
          - alert: "Healer should watch out for raid wide damage."
          - alert: "Players should pay attention too the movement of Shadowsplit adds to determine where the safe zones will be during the following Shadowflow."
  - title: "Lorelei"
    attacks:
      - title: "Ill Will"
        phases:
          - phase: 01
        roles:
          - role: "Tank"
          - role: "Healer"
        tags:
          - tag: "Auto Attack"
        notes:
          - note: "This attack is relatively heavy hitting - tanks and healers should pay attention to health during the fight."
      - title: "Headbutt"
        phases:
          - phase: 01
        roles:
          - role: "Tank"
          - role: "Healer"
        tags:
          - tag: "Tankbuster"
        notes:
          - note: "This is the boss' true tankbuster - heal and cooldown as necessary."
      - title: "Virgin Tears"
        phases:
          - phase: 01
        roles:
          - role: "Everyone"
        tags:
          - tag: "Circular AoE"
        notes:
          - note: "This attack places blue circular AoE puddles around the room that apply a bleed debuff to players who enter them."
          - note: "Expect the patterns for these AoEs to increase in difficulty over the course of the fight."
      - title: "Morbid Advance & Morbid Retreat"
        phases:
          - phase: 01
        combo:
          - title: "Morbid Advance"
            roles:
              - role: "Everyone"
            tags:
              - tag: "Mechanic"
            notes:
              - note: "This attack will cause all players to run forward in the direction they are facing for a short time."
              - note: "Be sure to position yourself in a way that allows you to run forward without hitting an AoE."
          - title: "Morbid Retreat"
            roles:
              - role: "Everyone"
            tags:
              - tag: "Mechanic"
            notes:
              - note: "This attack will cause all players to turn around and run in the direction they were facing away from for a short time."
              - note: "Be sure to position yourself in a way that allows you to run backwards without hitting an AoE."
      - title: "Somber Melody"
        phases:
          - phase: 01
        roles:
          - role: "Healer"
        tags:
          - tag: "Raid Wide AoE"
        notes:
          - note: "Healers should keep an eye out for this raid wide AoE and heal the group as necessary."
      - title: "Void Water III"
        phases:
          - phase: 01
        roles:
          - role: "Everyone"
        tags:
          - tag: "Circular AoE"
        notes:
          - note: "The boss will telegraph a relatively large circular AoE amongst the Virgin Tear AoE puddles already on the arena - be wary of other mechanics."
    sequence:
      - phase: 01
        attacks:
          - attack: "Ill Will"
          - attack: "Headbutt"
          - attack: "Virgin Tears"
          - attack: "Morbid Advance & Morbid Retreat"
          - attack: "Somber Melody"
          - attack: "Void Water III"
        alerts:
          - alert: "This fight demands a lot of attention regarding player position and AoE avoidance."
          - alert: "Morbid Advance & Morbid Retreat will both take control of your character and force them to run forward or backwards respectively - be sure to position yourself out of harm's way before these are cast."
---
