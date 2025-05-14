<div align="center">
  <h1>Tokyo Night Tmux Theme</h1>
  
  <h4>A Tokyo Night tmux theme forked from fabioluciano which has been directly inspired from Tokyo Night vim theme</h4>
    
    
</div>

## Features

- Transparency support

## Plugins

- **Datetime** - Show datetime;

## Install

Add plugin to the list of `TPM` plugins in `.tmux.conf`:

```
set -g @plugin 'juandrzej/tmux-tokyo-night'
```

Hit <kbd>prefix</kbd> + <kbd>I</kbd> to fetch the plugin and source it. You can now use the plugin.

## Available Configurations

| Configuration                       | Description                               | Avaliable Options                                                       | Default            |
| ----------------------------------- | ----------------------------------------- | ----------------------------------------------------------------------- | ------------------ |
| `@theme_variation`                  | The tokyo night theme variation to be use | `night`, `storm`, `moon`                                                | `moon`            |
| `@theme_active_pane_border_style`   |                                           |                                                                         | `#737aa2`          |
| `@theme_inactive_pane_border_style` |                                           |                                                                         | `#292e42`          |
| `@theme_left_separator`             |                                           |                                                                         | ``                |
| `@theme_right_separator`            |                                           |                                                                         | ``                |
| `@theme_window_with_activity_style` |                                           |                                                                         | `italics`          |
| `@theme_status_bell_style`          |                                           |                                                                         | `bold`             |
| `@theme_plugins`                    |                                           | `datetime`                                                              | `datetime`         |
| `@theme_disable_plugins`            | Disables plugins                          | `1`, `0`                                                                | `0`                |

## Plugins

### Datetime

> Prints informations about the current date and time.

| Configuration                              | Description | Avaliable Options | Default |
| ------------------------------------------ | ----------- | ----------------- | ------- |
| `@theme_plugin_datetime_icon`              |             | Any character 📅  | Nerd Font 'Calendar' icon        |
| `@theme_plugin_datetime_accent_color`      |             |                   |         |
| `@theme_plugin_datetime_accent_color_icon` |             |                   |         |
| `@theme_plugin_datetime_format`            |             |                   |         |

