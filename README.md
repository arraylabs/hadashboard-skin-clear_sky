# Clear Sky Skin
Custom skin for HADashboard 2 Beta. This is a work in progress.

##Block Colors

To set individual blocks to different colors use the color variables on the widget_style line. For example:
```
smoke_basement:
  widget_type: sensor
  title: Smoke/CO
  title2: Basement
  widget_style: $red_background
  entity: sensor.smoke_co_basement
```
> Colors available: $red_background, $orange_background, $green_background, $black_background
