# esp_lcd_SSD1322
SSD1322 driver for ESP-IDF
# ESP SSD1322 driver

Implementation of the SSD1322 OLED/PLED controller with esp_lcd component. 

| LCD controller | Communication interface | Component name | Link to datasheet |
| :------------: | :---------------------: | :------------: | :---------------: |
| SSD1322        | SPI/i80                 | esp_lcd_SSD1322| [Newhaven Display International, Inc.](https://support.newhavendisplay.com/hc/en-us/articles/4414477846679-SSD1322) |

## Add to project

Create `idf_component.yml`. More is in [Espressif's documentation](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-guides/tools/idf-component-manager.html).

## Usage

For detailed usage, please go to [LCD documentation](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/peripherals/lcd.html).

## Example initialization
(todo)

## Rotation and LVGL usage

For using this LCD display with LVGL or when you want to use rotation (only with LVGL), please use [`esp_lvgl_port`](
https://github.com/espressif/esp-bsp/tree/master/components/esp_lvgl_port) component.
