# Vindriktning-Card
Vindriktning Lovelace Card for Home Assistant


# Card
Create a Custom Card and paste this into the 'Code Editor'
````
type: vertical-stack
cards:
  - type: picture-entity
    entity: sensor.vindriktning_color
    show_name: false
    show_state: false
    state_image:
      green: /local/AQI-green.png
      yellow: /local/AQI-yellow.png
      red: /local/AQI-red.png
  - type: entities
    entities:
      - entity: sensor.air_quality_index_vindriktning_pm2_5
        name: Indoor Air Quality
    show_header_toggle: false
    state_color: false
````


## :camera: Screenshots and Pictuers
### Card Screenshot
![Card](docs/vindriktning-screenshot.png)
