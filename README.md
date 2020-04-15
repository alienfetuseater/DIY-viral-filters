# DIY viral filters

#### why were doing this

This repo is an attempt at developing an open source,3d printed viral filter intended to be used by paramedics to safely perform airway management on patients suspected of being contagious for infectious disease. The need for this product is being driven by the pandemic caused by the novel corona virus which causes the disease covid19. These viral filters are attachments to our airway equipment that have not been previously neeeded, and have overnight become an essential piece of equipment for saving the lives of patients. This is a need shared by every EMS department across the world the provides ALS services. Because of the sudden need for this equipment, access to purchasing these items is nonexistent.

#### what we are trying to make

The design is simply a device that attaches to our airway eqiupment at two different points. As depicted in the images below is a traditional viral filter connected to a prehospital ventillator (yellow) on one end, and the ventillator circuit on the other end (the tubing that connects the ventillator to the breathing tube placed in the patient's airway). The 3d printed device is a meant only to hold a viral filter. These filters also are not available, as such we will be substituting with a either HEPA vacuum cleaner bags which filter particles of .3 microns and larger at 98.5% efficiency and greater. Other potential substitutes would be sacrifical n100% masks in the event they were in abundance.

#### how to contribute

If you would like to contribute your own design, clone master and create your own branch. As of this writing there is [one branch](https://github.com/alienfetuseater/DIY*viral*filters/tree/threaded*filter*design) with a working build file for a prototype. Development for [that](https://github.com/alienfetuseater/DIY*viral*filters/tree/threaded*filter*design) branch has been using Fusion360. If you would like to make a contribution to that branch, clone that branch and make a pull request with your design contributions.

#### this is what the equipment looks like

this is a picture of the complete setup, showing the vent connected to the vent circuit, connected to capnography filter, which connects to the endotracheal tube, which is inserted into a patient's airway:

<img src="photos/completeSetup.jpg" width="100%" alt="picture of complete set up">

this is a closer up image of how the capnography filter connects to the vent circuit:

<img src="photos/capnoFilterToVentCircuit.jpg" width="100%" alt="capno filter connecting to vent circuit">

and this is a close up image showing how the vent circuit tubing connects to the ventilator itself:

<img src="photos/ventCircuitToVent.jpg" width="100%" alt="vent circuit connecting to ventilator">

this is an image of a traditional viral filter that is used in the hospitals. it is simply a connection between the vent circuit and the ventilator, forcing air that passes through to pass through the viral filter which is held inside the viral filter:

<img src="photos/viralFilter.jpg" width="100%" alt="image of a viral filter">

another image of the same viral filter:

<img src="photos/viralFilter2.jpg" width="100%" alt="image of viral filter">

this photo shows how a viral filter connects between the ventilator and the vent circuit tubing. we would like to also develop a second filter which would be attached between the endotracheal tube and the capnography filter line:

<img src="photos/ventToViralFilterToVentCircuit.jpg" width="100%" alt="viral filter attaching to vent circuit">

#### description of equipment

the airway equipment in question consists of

-   an _endotracheal tube_ (et tube), which is the tube that is placed into the patients anatomical airway,
-   the _vent circuit_, is the tubing that connects the et tube to the ventillator. the vent circuit connects directly to the ventillator on one end, by sliding over the attachment point on the ventillator. on the other end of the vent circuit, the circuit attaches to a intermediary attachment, by sliding over the external diameter of the attachment
-   _the attachment_ connects vent circuit to the et tube. the two sides are not of equal diameter. the side that attaches to the vent circuit is larger, and slides inside of the vent circuit. the side that attaches to the et tube (or the capno filter line) slides over the et tube's external diameter.
-   the _capno filter line_ is an optional piece of equipment. its not optional in our department, so it is always used. it is a device that ensures correct placement of the et tube in the pt's airway by monitored exhaled CO2.

##### measurements of the equipment we have that we work with

these are the measurements of our equipment i took, measurements taking with standard vernier calipers.

-   et tube (external diameter): 1.53cm
-   capnography filter
    -   et tube side (internal diameter): 1.55cm
    -   vent circuit side (external diameter): 1.54cm
-   vent circuit (internal diameter): 2.26cm
-   vent circuit attachment
    -   vent circuit side (external diameter): 2.3cm
    -   et tube/capno filter side (internal diameter): 1.55cm
-   ventilator (external diameter): 2.25cm

#### description of what we are designing

so what we are trying to get developed is two filters. one for inbetween the ventilator and the vent tubing. the dimensions for this filter will be, on the side that connects directly to the vent, have an internal diameter equal to that of the vent tubing. on the other side, the filter will have an external diameter equal to that of the vent.

the other filter will be the one that goes between the et tube and capnofilter (or the directly to the vent circuit attachment if the capnofilter wasnt being used, ill advised). so the measurements of this filter will be identical to the capnofilter then. on the side that slides over the et tube, it will have an internal diameter matching the corresponding side of the capnofilter. on the other side that attaches to the capnofilter, it will have an external diameter matching the external diameter of the et tube.

-   for between vent circuit to ventillator (as shown in photos)

    -   vent side (internal diameter): 2.26cm - 2.3cm
    -   vent circuit side (external diameter): 2.3cm

-   for between et tube and capnography filter line
    -   et tube side (internal diameter): 1.53cm - 1.55cm
    -   capnography filter line side (external diameter): 1.53cm
