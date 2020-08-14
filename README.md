# PCB-Component-Libraries

This repository contains UBC Solar's shared component libraries for PCB design.

Libraries of the following component types are included:
- Resistors
- Capacitors
- Inductors
- Diodes
- Transistors
- ICs
- Indication/control (switches, LEDs, buttons)
- Connectors
- Relays/transformers
- Fuses/holders
- Crystals
- Buck converters/regulators

Please see the team's Altium tutorial at https://sites.google.com/ubcsolar.com/project-management/tutorials/altium for more information on PCB design for the team.

## Using this library set

When starting a new project, you can pull the GitHub repository and direct Altium to that folder using the following steps:
1. Pull the repo to a directory of your choosing
2. Create your Altium project
3. Right click the .PrjPCB file in the project folder and select "Add existing to project"
4. Find the github repo that you pulled, and select all symbol and footprint library files. Click Open.

You should now have all the shared libraries within your project libraries folder.

## Making Modifications and Additions

**Please Do NOT edit or delete existing symbols or footprints.** Those files are shared among all the team's PCBs, and altering the libraries will affect them all. Notify the electrical lead if a change needs to be made to an existing file.

If you need to **add** components (symbols or footprints):
1. Make a new symbol and/or footprint library titled `*YourFirstName*_*YourLastName*_*DateDDMMYY*`, and save it to your GitHub repo folder
2. Add those new schematics to a commit and push the repo
3. Inform the electrical lead of your push, and they will merge everyone's individual library sets
4. When your library additions are added to the main master libraries, the electrical lead will notify all electrical subteams and library will be deleted from the repo.
    - If edits are made to existing footprints or symbols at the same time, this will also be included in the notification.
    - It is advised that you always update your schematic and PCB components as soon as you pull the latest library repo, regardless of whether the changes made are related.
