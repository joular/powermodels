# <a href="https://www.noureddine.org/research/joular/"><img src="https://raw.githubusercontent.com/joular/.github/main/profile/joular.png" alt="Joular Project" width="64" /></a> Power Models Database :zap:

[![License: ODbL v1.0](https://img.shields.io/badge/License-ODbLv1.0-blue)](https://opendatacommons.org/licenses/odbl/1-0/)

In each folder, you'll find a JSON file describing the power model of the device or component. Often a linear and a polynomial regression model.

## Computing Devices

### Raspberry Pi

| Model | Codename | Component | Model Variable |
|:--------------:|:---------------------:|:---------------------:|:---------------------:|
| Model Zero W (rev 1.1), 32-bit OS | rbpzw1.1 | CPU | CPU usage |
| Model 1 B (rev 2), 32-bit OS | rbp1b2 | CPU | CPU usage |
| Model 1 B+ (rev 1.2), 32-bit OS | rbp1b+1.2 | CPU | CPU usage |
| Model 2 B (rev 1.1), 32-bit OS | rbp2b1.1 | CPU | CPU usage |
| Model 3 B (rev 1.2), 32-bit OS | rbp3b1.2 | CPU | CPU usage |
| Model 3 B+ (rev 1.3), 32-bit OS | rbp3b+1.3 | CPU | CPU usage |
| Model 4 B (rev 1.1), 32-bit OS | rbp4b1.1 | CPU | CPU usage |
| Model 4 B (rev 1.1), 64-bit OS | rbp4b1.1-64 | CPU | CPU usage |
| Model 4 B (rev 1.2), 32-bit OS | rbp4b1.2 | CPU | CPU usage |
| Model 4 B (rev 1.2), 64-bit OS | rbp4b1.2-64 | CPU | CPU usage |
| Model 400 (rev 1.0), 64-bit OS | rbp4001.0-64 | CPU | CPU usage |
| Model 5 B (rev 1.0), 64-bit OS | rbp5b1.0-64 | CPU | CPU usage |

### Asus Tinker Board

| Model | Codename | Component | Model Variable |
|:--------------:|:---------------------:|:---------------------:|:---------------------:|
| Asus Tinker Board (S) | asustbs | CPU | CPU usage |

## Other Hardware

### Monitors

| Model | Codename | Component | Model Variable |
|:--------------:|:---------------------:|:---------------------:|:---------------------:|
| Dell P2722H | p2722h | Entire device | Brightness |
| HP P22H | p22h | Entire device | Brightness |

## Use Cases

These models are used and implemented in multiple projects and software, including:
- [PowerJoular](https://github.com/joular/powerjoular)
- [JoularJX](https://github.com/joular/joularjx)

## :newspaper: License

The power models and database are licensed under the Open Data Commons Open Database License (ODbL) v1.0 (ODbL-1.0).

Copyright (c) 2022-2023, Université de Pau et des Pays de l'Adour.

Initial models and approach of Raspberry Pi devices by Adel Noureddine and Houssam Kanso, and published in the journal article: [Automated Power Modeling of Computing Devices: Implementation and Use Case for Raspberry Pis](https://hal.science/hal-03912723v1).