# Cockpit Sensors

module that displays all data reported by lm-sensors

# Usage

* Install lm-sensors (version 3.5 or newer) and rum sensors-detect for list ao sensor of the machine.
* Download the lastest [Sensors release](https://github.com/ocristopfer/cockpit-sensors/releases) 
* Extract the content of dist folder to /usr/share/cockpit/sensors
* Check if Sensors tools is show on menu

* Installation script provided by [@subz390](https://github.com/subz390): 

        wget https://github.com/ocristopfer/cockpit-sensors/releases/latest/download/cockpit-sensors.tar.xz && \
        tar -xf cockpit-sensors.tar.xz cockpit-sensors/dist && \
        mv cockpit-sensors/dist /usr/share/cockpit/sensors && \
        rm -r cockpit-sensors && \
        rm cockpit-sensors.tar.xz

# Prints
![alt text]([https://i.ibb.co/KbbXQ0H/cockpit-sensors.png](https://i.ibb.co/426KMGk/cockpit-sensors.jpg))


# Module created using Starter Kit
    
* [Starter Kit](https://github.com/cockpit-project/starter-kit)
