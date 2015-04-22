# Novena and Myriad RF Module Case and Cooling Kit

![A Novena board with Myriad RF Module fitted in a NRFC-01 case](/images/CompletedAssemblyISOPorts-DSC_1955.jpg)

The [NRFC-01 kit](http://abopen.com/NRFC-01) is a simple but elegant case based on the "[sick of beige](http://dangerousprototypes.com/docs/Sick_of_Beige_basic_case_v1)" design and includes a DC fan to keep the [Novena](http://www.kosagi.com/w/index.php?title=Novena_Main_Page) board cool. It can be bought from [Ground Electronics](http://groundelectronics.com).

## Repository contents

The case design is provided in the following formats:

* Adobe Illustrator (source)
* SVG
* PDF
* DXF

The case parts are laser cut from 3mm sheet acrylic.

## Bill of materials

In addition to the acrylic parts the NRFC-01 kit contains:

| Qty | Item                                |
| --- | ----------------------------------- |
|  1  | 25x25x8mm 5VDC fan                  |
|  1  | M3 x 5mm steel hex standoff         |
|  1  | M3 steel hex nut                    |
|  2  | M2.5 hex nut                        |
|  2  | Female crimp connector M20          |
|  1  | Crimp housing M20 SIL 2.54mm        |
|  1  | 1uF Through Hole Tantalum Capacitor |
|  12 | M3 x 8mm Steel Machine Screw        |
|  6  | M3 Nylon Nut                        |
|  4  | 3mm x 5mm Nylon Spacer              |
|  3  | M3 x 12mm Nylon Pan Head Screw      |
|  1  | M3 x 20mm Nylon Cheese Head Screw   |
|  3  | M3 x 16mm Nylon Cheese Head Screw   |
|  4  | M3 x 35mm Nylon HexStandoff F-F     |
|  2  | M2.5 x 12mm Steel Machine Screw     |
|  2  | M2.5 x 5mm Steel Hex Standoff       |
|  1  | 15 x 15 x 8mm Heatsink              |
|  4  | Self Adhesive Rubber Bumpers        |


## Fan Assembly

The fan sold with the kit has the tantalum capacitor, crimp connectors and housing already assembled for ease of build. If building from own parts you will need to solder the tantalum capacitor to the fan wires noting capacitor polarity, crimp the connectors on to the wires and insert the crimped ends into the crimp housing.

## Other hardware required

The NRFC-01 is designed to house a Novena Mainboard, MyriadRF Novena Module and a hard drive. Assembly instructions below assume you already have each of these parts available and to hand.

## Assembly

![Parts laid out](/images/allPartsLayout-DSC_1886.jpg)

- Lay out all of the parts and ensure you have everything listed in the B.O.M.

- Remove the protective backing from the acrylic parts. Note that this is likely to generate static electricity - be aware of this and careful not to do this near any electronic hardware that may be sensitive to static electricity. Wipe any clouding / marks from acrylic that may have occured during laser cutting.

![Fan attached](/images/FanMounted-DSC_1898.jpg)

- Take 3 x M3 x 16mm nylon screws and 3 x nylon nuts and attach the fan to the top acrylic panel. (Note a different fan requiring 4 mounts is shown in photographs)

- (Optional) Use wire cutters to trim the screws close to the nuts.

   ![TX + RX connectors](/images/RXTXCablesAndAcrylic-DSC_1905.jpg)

- Add the 2 SMA - U.FL Coaxial cable assemblies to the case part labelled 'TX RX'

![M2.5 Myriad Hardware](/images/M2-5HardwareAndNovenaArrows-DSC_1909.jpg)

- Add 2 x M2.5 x 12mm machine screw + M2.5 x 5mm spacers to Novena board as shown above. Take care to not overtighten these.

   ![Base panel with screws and circular spacers](/images/NovenaMountingHardwareCLOSEupDSC_1915.jpg )

- Take 3 x M3 x 12mm nylon machine screws + 1 x M3 x 20mm nylon machine screw and position in base, from bottom. Note 20mm long screw needs to be in lower right corner as shown in the photo above. Add a 3mm x 5mm nylon spacer to each screw.

- Add the Novena board to the base plate taking care that each nylon screw fits through the mounting holes in the corners.

- Add 3 x M3 nylon nuts - one to each short nylon mounting screw. Do not add a nylon nut to the longer mounting screw.

![M3 5mm spacer](/images/NovenaMountingHardwareM3-5mmSpacer-DSC_1918.jpg)

- Add the M3 5mm steel spacer to the 20mm long mounting screw.

- Add the MyriadRF Module board to the Novena board. Take care to not force it as the connector is very delicate. Ensure everything is correctly aligned before applying gentle pressure to push the module into place.

![MyriadRF Module Mounted](/images/NovenaMyriadMounted-DSC_1921.jpg)

- Add 2 x M2.5 nuts and 1 x M3 nut to secure the MyriadRF Module into place. Take care not to overtighten these nuts. Also take care to not knock or lever off any of the electronic components that are near the mounting holes.

![Additional Heatsink](/images/NovenaMyriadHeatsinkCLOSE-DSC_1925.jpg)

- Take the additional heatsink and peel off the backing from the adhesive pad. Take note of alignment of fins (to maximise airflow through heatsink) before sticking to the FPGA chip. Only small amount of pressure is needed here - do not press too hard or damage may be caused to the chip.

![Corner Standoffs](/images/M3-8mmM3Spacers-A-DSC_1929.jpg)

- Take 4 x M3 x 8mm steel machine screws and 4 x M3 35mm nylon standoffs and add them to the corners of the base assembly.

![HDD mounting plates](/images/AssemblyWithHDDSides-DSC_1932.jpg)

- Add the two acrylic parts that will hold the hard drive in place. Ensure each part is correctly oriented - see photo. Slots are closer to base than the top.

- Slot the hard drive into place, connecting it to the connector on the Novena board. Take care to not move the hard drive around too much to avoid placing unnecessary force on the connectors.

- Add 4 x M3 x 8mm steel machine screws to the hard drive, again taking care to move the drive as little as possible.

![HDD mounting alignment](/images/AssemblyHDDSideOnStraightCheck-DSC_1936.jpg)

- Check the hard drive is flat and correctly aligned with the board connector before gently tightening up each mounting screw.

![TX + RX Connector piece](/images/AddTXRXSide-A-DSC_1938.jpg)

- Add the TX RX connector piece to the base assembly.

![TX + RX Connector connection](/images/ConnectTXRXCables-DSC_1940.jpg)

- Plug the U.FL cable ends to the MyriadRF Module. CAUTION: These connectors are extremely delicate and rated for minimal amount of connections/disconnections. Also take care that the MyriadRF Module will flex a little whilst mounted to the Novena board. If you are having difficulty it may be advantageous to remove the MyriadRF board to facilitate the connection of these U.FL cables.

![Add long blank side](/images/AddLongBlankSide-DSC_1943.jpg)

- Add the long blank side piece to the assembly.

![Add port side](/images/AddPortSide-DSC_1944.jpg)

- Add the port side piece.

![Plug in fan](/images/GetTopPlugFanIn-DSC_1946.jpg)

- Take the top panel and place it next to the base assembly. Connect the fan power connector to the pins on the MyriadRF module ensuring polarity is correct.

![Add top panel](/images/CompletedISOTXRX-DSC_1950.jpg)

- Now add the top panel. Start by aligning the tabs at the port endand gently lowering the top panel down. Ensure all tabs align with holes in the top plate - you may need to reposition the side panels before it fits together.

- Add 4 x M3 x 8mm steel machine screws to hold the top panel in place.

![Add top panel](/images/AddBumperBase-DSC_1956.jpg)

- Turn the assembly over and stick the 4 x self adhesive rubber bumpers to the base.

##Notes

- Note that if disassembly is required, or the top panel is removed it should be noted that removal of the fan power connector is advised.

- Similarly is is advised that caution is taken when disassembling to the point of hard drive removal - care must be taken to remove the drive along with mounting screws in such a fashion as to not apply unwanted force on the hard drive connector.

- The NRFC-01 case includes PEEK-array compatible hole spacing for easy addition of modules and hardware should you wish to exapnd your system. Note that we used 3mm holes to allow for use of M3 hardware and avoid the need for extra threaded push-fit parts.


## Changelog

| Version | Date     | Summary
|---------|----------|--------------------


## Licence

Novena and Myriad RF Module Case and Cooling Kit copyright 2015 [AB Open Ltd](http://abopen.com).

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Thanks

Bunnie and all involved with the Novena project
 
