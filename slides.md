---
theme: field-manual
mdc: true
colorSchema: dark

date: JUNE 27, 2026
docNumber: DEMO NIGHT 4
classification: FOR DEMO USE ONLY
title: Planespotter

layout: cover
---

# Planespotter

---
layout: section
sectionNumber: "1"
---

## Inspiration

<template v-slot:descriptor>
How did we get here?
</template>

---
layout: two-images
sectionNumber: "1"

fig1Label: FlightAware
fig2Label: flightradar24
---

- I live within the flight path of the St. John's airport
- A **LOT** of stuff flies over my apartment
- Been an off-and-on user of air traffic tracking apps for a while now

<template v-slot:image1>
    <img src="./images/flightaware.png" alt="FlightAware" />
</template>

<template v-slot:image2>
    <img src="./images/flightradar24.png" alt="FlightRadar24" />
</template>

<style>
    .ti-image-frame img {
        object-fit: contain;
    }
</style>

---
layout: default
sectionNumber: "1"
---

## This has problems

- Requires me to hear something fly overhead -> open the app -> check what it is
  - Might not be able to hear it for any variety of reasons
  - Might be too busy to open the app
- Signal-to-noise ratio is _TERRIBLE_
  - Vast majority of what I hear is the same few Cougar / WestJet / Air Canada / Porter / etc. flights
  - I want to find out about the _interesting_ stuff

---
layout: section
sectionNumber: "2"
---

## The Technology

<template v-slot:descriptor>
There has <i>got</i> to be a better way.
</template>

---
layout: quote
sectionNumber: "2"

attribution: Automatic Dependent Surveillance–Broadcast
rank: Wikipedia
---

"Automatic Dependent Surveillance–Broadcast (ADS-B) is an aviation surveillance technology and form of electronic conspicuity in which an aircraft determines its position via satellite navigation or other sensors and periodically broadcasts its position and other related data, enabling it to be tracked."

---
layout: quote
sectionNumber: "2"

attribution: Pseudo-range multilateration
rank: Wikipedia
---

"Pseudo-range multilateration, often simply multilateration (MLAT) when in context, is a technique for determining the position of an unknown point, such as a vehicle, based on measurement of biased times of flight (TOFs) of energy waves traveling between the vehicle and multiple stations at known locations."

---
layout: image

image: /images/mlat.png
---

---
layout: end
---

<template v-slot:title>Questions?</template>

<template v-slot:contact>

<mdi-github/> `nint8835/planespotter`<br/>
<mdi-email/> `riley@rileyflynn.me`

</template>
