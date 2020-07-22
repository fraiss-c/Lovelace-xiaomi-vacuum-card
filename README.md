# Lovelace-xiaomi-vacuum-card
[![Buy Me A Coffee][buymeacoffee-image]][buymeacoffee-url]

Home Assistant Lovelace UI card made for Xiaomi Roborock vacuums (compatible with other vacuum robots).
The design is based on the Roborock S50 V2, but new backgrounds can be easily done.

![Xiaomi vacuum card preview](https://user-images.githubusercontent.com/16242137/88160973-aef3a400-cc0f-11ea-905b-b50c21d14ef0.PNG)

The icons on the card have the following behavior:\
![play](https://user-images.githubusercontent.com/16242137/88162994-54a81280-cc12-11ea-88cc-619d1808a6c6.png): Start cleaning.\
![stop](https://user-images.githubusercontent.com/16242137/88162928-40fcac00-cc12-11ea-89c9-0b013802eab6.png): Stop cleaning.\
![home](https://user-images.githubusercontent.com/16242137/88163120-7d300c80-cc12-11ea-8af6-cc8348690230.png): Return to base.\
![target](https://user-images.githubusercontent.com/16242137/88163189-95a02700-cc12-11ea-8fb3-8ade5e0c755a.png): Go to my `/vacuum` lovelace view where my floorplan is displayed to launch room cleaning.\
![bell-ring](https://user-images.githubusercontent.com/16242137/88163532-18c17d00-cc13-11ea-85b4-6dcf6550941f.png): Locate the vacuum.


## Installation

The card is made of 3 components:
- `sensor.yaml` file which contains the code needed to create the entities.
- `home.yaml` containing the code to add in your `ui-lovelace.yaml` file.
- `xiaomi_vacuum_card.png` the background image.

If you liked this card, you can buy me a ☕️:

<a href="https://www.buymeacoffee.com/gagooga" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>

[buymeacoffee-url]: https://www.buymeacoffee.com/gagooga
[buymeacoffee-image]: https://img.shields.io/badge/support-buymeacoffee-222222.svg?style=flat-square
