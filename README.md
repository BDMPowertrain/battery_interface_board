<p align="center" width="100%">
  <img alt="Logo" width="33%" src="Logos/bdm_logo.png">
</p>

<h1 align="center">BATTERY_INTERFACE_BOARD</h1>
<p align="center">Battery Interface Board</p>
<p align="center"><em>This board interfaces with the cell tap connctons fusing them, and collecting them to one connector.</em></p>

<p align="center" width="100%">
  <a href="https://github.com/BDMPowertrain/battery_interface_board/actions/workflows/ci.yaml">
    <img alt="CI Badge" src="https://github.com/BDMPowertrain/battery_interface_board/actions/workflows/ci.yaml/badge.svg?branch=dev">
  </a>
</p>

<p align="center" width="100%">
    <img src="Logos/SAE_Electric_Logo.png" width="40%">
</p>

***

<p align="center">
  <img alt="3D Top Angled" src="Images/battery_interface_board-angled_top.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="3D Bottom Angled" src="Images/battery_interface_board-angled_bottom.png" width="45%">
</p>

***

## SPECIFICATIONS

| Parameter | Value |
| --- | --- |
| Dimensions | 0.0 × 0.0 mm |
| Company | Blue Devil Motor Sports |
| Designer | Aidan Brzezinski |
| Revision | + (Unreleased) |

***

## WORKING ON THIS BOARD

> This file is regenerated automatically on every CI run — don't edit it by
> hand. For the full contributor guide (setup, daily commands, commit
> conventions, PR etiquette, and what to do when something goes wrong), see
> the [board_template README](https://github.com/BDMPowertrain/board_template#readme).

**Change the variant** as the board moves through Design → Procurement →
Fabrication:

    ./configure.sh --variant

**Change board metadata** (title, description, designer, company):

    ./configure.sh

RELEASED is never set by hand — push a version tag and CI produces it
automatically:

    git tag 1.0.0
    git push origin 1.0.0
