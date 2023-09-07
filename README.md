# Voron2.4r2-350mm
Voron 2.4r2 350mm Klipper Setup

This repository contains the Klipper configuration files for my Voron 2.4r2 350mm 3D printer. These files are essential for the operation, tuning, and management of the printer.

Table of Contents

    Installation
    Configuration Files
    Contributing
    License

Installation

Clone this repository into your preferred directory.

    git clone https://github.com/Etienneg93/Voron2.4r2-350mm.git

Follow the Klipper installation guide and link the appropriate configuration files.

Configuration Files

Here's a brief overview of what each file in the repo does:

    macro/: Folder containing various custom macros.
    .moonraker.conf.bkp: Backup for Moonraker configuration.
    DUMP_VARIABLES.cfg: Configuration for dumping variables.
    GET_VARIABLE.cfg: Configuration for retrieving variables.
    KlipperScreen.conf: Configuration for the KlipperScreen interface.
    Parking.cfg: Configuration for parking the print head.
    TEST_SPEED.cfg: Configuration for testing print speeds.
    adaptive_mesh.cfg: Configuration for adaptive mesh bed leveling.
    fluidd.cfg: Configuration for the Fluidd interface.
    heatsoak.cfg: Configuration for heat soaking the printer.
    moonraker.conf: Moonraker configuration.
    nevermore.cfg: Nevermore V5 Fan configuration.
    pauseresume.cfg: Configuration for pause and resume functionality.
    picoadxl.cfg: Configuration for the Pico ADXL345 sensor.
    printer.cfg: Main Klipper configuration file.
    stealthburner_led_nowhite.cfg: LED configuration without white color.
    stealthburner_leds.cfg: LED configuration.

Contributing

Feel free to submit PRs or issues if you find a bug or think a feature could be added.
License

MIT License
