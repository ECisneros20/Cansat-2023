# Cansat 2023

## Description

This repository contains the necessary scripts for the operation of the satellite and ground station for the Cansat USA 2023 competition.

## Installation

To clone the latest stable version:

	git clone https://github.com/ECisneros20/Cansat-2023.git

To clone the latest version:

	git clone -b testing https://github.com/ECisneros20/Cansat-2023.git

## Usage

First, you must have all the prerequisite libraries:

	pip install -r requirements.txt

Then, run the following script in the cansat computer:

	<command> cansat.<type>

Finally, run the following script in the ground station computer:

	python ground-station.py

In case, you want to check programming functionality without sensors usage:

	<command> cansat-no-sensors.<type>

## Next steps

1. Define 2 work teams: 1 for the cansat programming and the other one for the ground station programming.

2. Prepare a sketch for the cansat-no-sensors.<type> script

3. Prepare a sketch for the ground-station.py script

4. Prepare a sketch for the cansat.<type> script

## License

MIT License
