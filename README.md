
# Home Assistant Sungrow Battery Charge/Discharge Time Calculator

This repository offers a scheduling tool to manage the charge and discharge times of a Sungrow battery storage system integrated with Home Assistant.




## Requirements

```bash
  1. ModBus integration by Mkaiser. (https://github.com/mkaiser/Sungrow-SHx-Inverter-Modbus-Home-Assistant)
  2. Home Assistant-Core version 2024.4.0b7 or newer
```



## Installation

```bash
  1. Paste the statistics_sensor.yaml in your configuration.yaml in Home Assistant.
  2. Paste the ENG_battery_calc.yaml or the GER_speicher_calc.yaml in your configuration.yaml.
  3. Adjust the parameters if you are not using the default settings.
  4. Save the adjustments and restart Home Assistant.
  5. Navigate to the ENG_template or GER_template folder and copy the code from the template file.
  6. Open your Home Assistant dashboard, click on the pencil icon in the top right corner, and then click on Add Card at the bottom right.
  7. Select any card, then click on SHOW CODE EDITOR in the bottom left corner, and replace the entire code with the copied one.
  8. Press SAVE
```

## Support

If you encounter any issues during installation or find an error, please create a new discussion, and I will respond as quickly as possible.

## Improvements

Please open a discussion if you have any suggestions for improvements, including code, design, or additional features.
I appreciate any suggestions.

## Screenshots

[![overview-battery.png](https://i.postimg.cc/DzjvFS4D/overview-battery.png)](https://postimg.cc/B8F9BQgc)



[![complete-overview.png](https://i.postimg.cc/bNc245hn/complete-overview.png)](https://postimg.cc/bdgJt3dY)



