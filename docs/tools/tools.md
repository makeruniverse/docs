Tools at the HPI Maker Universe. Talk to our [experts](../team/team.md) for help. <br />

## Maker Studio Tools

### Modeler Workstation

The Modeler Workstation is our stationary computer in the Maker Studio that allows to create digital models. It includes [slicer software](tools.md/#orca-slicer-software), [modeling software](tools.md/#autodesk-fusion), and access to our [label printer](tools.md/#label-printer-ql-820nwbc).

### Orca Slicer Software

Orca Slicer is your best option to prepare 3D prints.

- [ ] import model in OrcaSlicer
- [ ] use "auto orient" to position model
- [ ] select textured PEI plate for PLA
- [ ] check if model needs support structure
- [ ] assign filament
- [ ] print on one of our printers
- [ ] tag printer with your name

??? "Alternative: Use Orca Slicer on your Laptop"
    https://github.com/SoftFever/OrcaSlicer

    Install with brew: `brew install orcaslicer`
    AUR: `orca-slicer`
The easiest way to use the printers is sending files remotely. Upon installation you will be asked if you want to install the network plugin. We recommend to do this. The login credentials are:

User: makeruniverse@hpi.de
PW: Freezable-Scoured3-pigment

### Autodesk Fusion

Parametric CAD software with a powerful CAM module.
Full version free to use with educational autodesk account.

### Blender

Blender is a versatile and powerful 3D modeling, animation, and rendering software known for its robust feature set and open-source nature.
we offer blender introduction workshops regularly at makeruniverse. If you want to get into 3d-modelling and don't tie yourself to commercial software this is our first recommendation. [download blender](https://www.blender.org/download/)

### Printer/Plotter

### Label Printer QL-820NWBc

This QL-820NWBc can print up to 62mm in width. If wider: You might change the orientation of the label in the software to fit the label on the printer.

You can use the printer via Wi-Fi (hpi-studios) and via USB. You can find the software on our Modeler Workstation.

??? "Software for our Label Printer"

    MacOS: https://apps.apple.com/de/app/brother-p-touch-editor/id1453365242?mt=12
    Windows: https://support.brother.com/g/s/es/inst/de/index.htm?c=de&lang=de&navi=off&comple=on&redirect=on

### 3D Printer Workstation

Our workstation includes a access to [slicer software](tools.md/#orca-slicer-software) and a variety of 3D printers, e.g., 2x [Bambu A1 Mini](./tools.md/#bambu-a1-mini-2x), [2x Bambu X1](./tools.md/#bambu-x1-2x), 2x [Creality K1](tools.md/#creality-k1-2x), and the mighty [Prusa XL](tools.md/#prusa-xl).

??? "3D Print Online Ressources"

    https://www.printables.com/ <br />
    https://www.thingiverse.com/ <br />
    https://thangs.com/ <br />
    https://makerworld.com/

### Bambu A1 Mini (2x)

Use Bambu a1 Mini when you print small objects with a single filament.

### Bambu X1 (2x)

Use Bambu X1x when you print larger objects or objects with up to four different types or filaments.

The Bambu Lab X1c has a build volume of 256 x 256 x 265 mm and usually uses a 0.4mm nozzle.

    The Bambu has a Snakehouse Fan Duct, which is a bit too close to the bed, on the left of the enclosure. If thin/fragile parts are located on the left side of the bed, near to the edge, they might warp due to the fan blowing on it. If that happens disable the AUX Fan and print with open enclosure. ![OrcaSlicer AUX Fan Settings](../3D_Printing/img/auxfan-orca.png)
    
### Creality K1 (2x)

Creality K1 has a build volume of 300 x 300 x 300 mm usually one of them is equipped with a 0.4mm nozzle and the other one with a 0.6mm nozzle.

??? "Print large objects"

    The Creality printers use Klipper firmware [Official Documentation] (https://www.klipper3d.org/Overview.html)
    You can access the printers via webinterface.
    IP left printer (0.8 nozzle): https://172.22.0.254:4408 
    IP right printer (0.4 nozzle) https://172.22.3.249:4408

??? "Connect OrcaSlicer to Creatly K1"

    You can get the IP address of your Creatly K1 by going to the printer menu and selecting `Settings` and then `Network`.
    Make sure your PC is connected to `hpi_studio` WiFi.
    Enter the IP Address like shown in the image above and click `Test`. If the test is successful you can click `Connect` and start printing. After slicing you can click `Print` to start printing.

??? "Creality K1 Web Interface"

    Make sure your PS is connected to `hpi_studio` WiFi.
    Select `Settings` and then `Network`. Then enter the IP Address in your browser. Make sure to append `4408` as port. Example: ![http://172.22.0.254:4408](http://172.22.0.254:4408)

### Prusa XL

Use Prusa XL when you print large objects and / or objects with multiple filament types.

To use all features of the Prusa XL we recommend to use [Download: Prusa Slicer](https://www.prusa3d.com/en/page/prusaslicer_424/)
You can send jobs remotely with [prusa connect](https://connect.prusa3d.com/)

Login credentials:
User: makeruniverse@hpi.de
PW: UEH6zvg2ecm.vwe3nad

If you want to use various nozzle widths in one print, you need to use simplify 3d for slicing.
we have a profile for Prusa XL here:

??? "Printing with Vector Files"

    It's possible to import SVG files into the slicing software, give them a thickness (extrude) and 3d print them.
    This works in Pruse SLicer, Orca Slicer & Bambu Studio.

    Import your SVG file, the printer will directly show an extruded version with a height of 10mm.
    For creating small signs set Z-height to 2mm (uncheck uniform scale) and adjust XY scale as needed.

### Laser Cutter Workstation

The Laser Cutter Workstation is located in the small Maker Studio next to the Trotec Laser Cutter.

Please contact our team to participate for a mandatory introduction in the machine and the software. The succesful participation allows you to use the laser cutter afterwards.


### Electronic Workstation

The Electronic Workstation offers two working tables with various tools [solder components](tools.md/#soldering-station), and to do precise electronic [measurements](tools.md/#multimeter). The workstation is also stacked with [electronic components](tools.md/#electronic-components) and [materials](tools.md/#electronic-materials) that are free to use.

### Soldering Station

We have 6 soldering stations you can use after a mandatory introduction.

### Multimeter

### Microscope

### Electronic Components

### Electronic Materials

Podcasting, video recording, photo shootings, AI generation, visualizations, sound designs. The opportunities are vast.

Visit our Media Studio in House K and get in contact with our Head of Media Studios to get support for your project [@markus.wutzlhofer](../team/team.md/#markus-wutzlhofer)

## Media Tools

Our Media Tools are located in the Media Studio. They serve various use case to produce and edit media content.

### Media Workstation  

The Media Workstation consists of two powerful computers with access to AI applications, media editing software, and modeler software.

??? "AI tools"

    [Stable Diffusion](tools.md/#stable-diffusion) <br /> 
    [HeyGen](tools.md/#heygen) <br />
    [Chat GPT](tools.md/#chat-gpt)<br />
    [Project Runway](tools.md/#project-runway)<br />
    [DaVinci Resolve](tools.md/#davinci-resolve)<br />
    [Adobe Firefly](tools.md/#adobe-firefly)<br />
    [Eleven Labs](tools.md/#eleven-labs)<br />
    [Photoshop Retouche4me](tools.md/#photoshop-retouche4me)
 
??? "Media Editing Software"

    [Izotope RX10](tools.md/#izotope-rx10) <br />
    [Ableton Live 11](tools.md/#ableton-live-11)

??? "Modeler Software"
    [Blender](tools.md/#blender)<br />
    [Shaper Trace](tools.md/#shaper-trace)<br />
    [Orca Slicer](tools.md/#orca-slicer-software)<br />
    [Shapr 3D](./tools.md/#shapr-3d)<br />
    [Kyub](./tools.md/#kyub)

### Stable Diffusion

### HeyGen

### Chat GPT

### Project Runway

### DaVinci Resolve

### Adobe Firefly

### Eleven Labs

Above that, the workstations offer media editing software.

### Photoshop Retouche4me

### Izotope RX10

### Ableton Live 11

The worstations also allow to create models which can be printed or laser cut in the Maker Studio.

### Shaper Trace

### Shapr 3D

### Kyub

## Film Studio Workstation

Our Studio Workstation allows for professional [photo shootings](tools.md/#canon-slrt-photoshootings) and [video recordings](tools.md/#video-recordings) as well as [podcast recordings](tools.md/#podcasting).

??? "How to get access"

    The studio is available and can be used without prior registrations. We can support you in setting up the space for a professional shooting. Our colleague [Markus Wutzlhofer](../team/team.md) is managing the studio and can help you.

### Canon SLRT Photoshooting

### Video Recordings

### Podcasting Setup

## UX Workstation

Our UX Workstation allows for professional video recordings for various kinds of user studies.

The **setup** comprises 4 PTZ cameras, a Shure audio panel, a recording workstation, and a coffee table with two chairs.

??? "UX Case Study Examples"
    - User Interviews
    - UX / Usabiltiy Tests
    - Standardized Questionnaires
    - Field Observations
    - Prototype User Tests

??? "How to get Access"

    Get in contact with our colleague [Jan](../team/team.md) to plan your UX-project or leave a message in our Slack Channel #contact-our-team.

## Superposition Workstation

Project teams of up to four people can book our Super Position setup to work in parallel by sharing their screens with each other.

The four screens are connected to the [KVM Matrix-Switcher](https://kvm-switch.de/de/4-x-4-hdmi-2-0-multiview-seamless-matrix-switch-mit-video-wall-funktion-uniclass-rh-244.html){target="_blank"}. An [AirServer](https://www.airserver.com/connect-3){target="_blank"} (screens 1, 2 and 3) and an HDMI cable (screen 4) act as feeders. A connection via AirPlay 2, Google Cast and Miracast is possible via the AirServer.


??? "How does the connection and the display work?"

    First, the entire setup must be switched on using the foot switch (lights up blue).

    ![Superposition Switch On-Off](../mediaassets/tools/superposition_switch.jpg){: style="width:25%;"} <br />

    As soon as the first device connects to the AirServer, it is routed to the first screen. If a second device follows via a wireless connection, it is played on the second screen and so on.

    ![Superposition Switch On-Off](../mediaassets/tools/superpositionA.png){: style="width:25%;"} <br />

    This is the default setup after switching on and can be reset at any time by first pressing the RECALL button and then the A button.

    ![type:video](../mediaassets/tools/superposition_recalla.mp4)

    If a single screen is to be displayed on all four screens, RECALL must be pressed first and then the button for the corresponding input (1-4).

    ![Superposition Switch On-Off](../mediaassets/tools/superposition1-4.png){: style="width:25%;"} <br />

    ![type:video](../mediaassets/tools/superposition_recall1.mp4)

 
