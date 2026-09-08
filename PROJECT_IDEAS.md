# Computer Architecture Project Ideas

## Idea 1: Mini Environment Monitoring Station

This project will use various sensors to detect conditions in the local enviroment such as:

- temperature
- sound levels
- light levels
- humidity
- atmospheric pressure
- colors
- UV index

Several different sensors would be needed to measure these different conditions.

| Measurement | Sensor   |
| ----------- | -------- |
| Temperature | BME280   |
| Humidity    | BME280   |
| Pressure    | BME280   |
| Sound       | MAX4466  |
| Light       | BH1750   |
| Colors      | TCS34725 |
| UV Index    | VEML6075 |

Depending on how many different things we want to measure or how many sensors we want to buy, we can remove features. However, with the BME280 measuring temperature, humidity, and pressure, those three will be there to stay.

## Idea 2: Smart Calendar Syrnchronized Alarm

This project will be an actual alarm clock which will synchronize to your calendar app and will wake you up according to your schedule and your preferences.

The dev board can handle the physical alarm aspect of the project, whilst another computer/service can handle the calendar integration.

Some stuff from a simple hardware kit will cover a lot of my needs.

- Push buttons for Set/Disable functions
- Buzzer for alarm sound
- LEDS for visual alarm

Additionally, a DS3231 can keep time independently, so it may be important: I don't want my alarm to depend on the network.
