# TTS Invisibility

Utility for turning objects invisible in [Tabletop Simulator](https://www.tabletopsimulator.com/).

## Installation

* Download the [workshop mod]()
* Copy the `onObjectCollisionEnter` function in `global.ttslua` to `global.ttslua` of the destination save
* Spawn the object contained in the workshop save into the destination save

## Usage

* Drop an object onto invisibility infinite stack to initialize it (allow it to be invisible)
* Grab invisibility token from infinite stack
* Drop invisibility token onto an initialized object to toggle between invisible/visible
* The object will only be visible to the GM (Black)
