# system

[![Build Status](https://cloud.drone.io/api/badges/machippie/system/status.svg)](https://cloud.drone.io/machippie/system)

Ansible role to configure system

## Table of content

* [Default Variables](#default-variables)
  * [system_always_keeps_windows](#system_always_keeps_windows)
  * [system_auto_download](#system_auto_download)
  * [system_auto_update](#system_auto_update)
  * [system_available_languages](#system_available_languages)
  * [system_computer_sleep](#system_computer_sleep)
  * [system_critical_update](#system_critical_update)
  * [system_display_sleep](#system_display_sleep)
  * [system_enable_ntp](#system_enable_ntp)
  * [system_font_smoothing](#system_font_smoothing)
  * [system_harddisk_sleep](#system_harddisk_sleep)
  * [system_hostname](#system_hostname)
  * [system_locale](#system_locale)
  * [system_login_admin_host_info](#system_login_admin_host_info)
  * [system_login_disable_autologin](#system_login_disable_autologin)
  * [system_login_guest_enabled](#system_login_guest_enabled)
  * [system_login_restart_disabled](#system_login_restart_disabled)
  * [system_login_retries_until_hint](#system_login_retries_until_hint)
  * [system_login_show_input_menu](#system_login_show_input_menu)
  * [system_login_show_user_list](#system_login_show_user_list)
  * [system_login_shutdown_disabled](#system_login_shutdown_disabled)
  * [system_login_user_switching](#system_login_user_switching)
  * [system_measurement_unit](#system_measurement_unit)
  * [system_metric_unit](#system_metric_unit)
  * [system_notification_banner_time](#system_notification_banner_time)
  * [system_quarantine](#system_quarantine)
  * [system_quit_printer](#system_quit_printer)
  * [system_restart_freeze](#system_restart_freeze)
  * [system_show_scrollbars](#system_show_scrollbars)
  * [system_siri_enabled](#system_siri_enabled)
  * [system_siri_hotkey_tag](#system_siri_hotkey_tag)
  * [system_siri_language](#system_siri_language)
  * [system_siri_visible](#system_siri_visible)
  * [system_siri_voice_feedback](#system_siri_voice_feedback)
  * [system_smart_caps](#system_smart_caps)
  * [system_smart_dashes](#system_smart_dashes)
  * [system_smart_period](#system_smart_period)
  * [system_smart_quotes](#system_smart_quotes)
  * [system_spelling_check](#system_spelling_check)
  * [system_text_replacement](#system_text_replacement)
  * [system_timezone](#system_timezone)
  * [system_user](#system_user)
  * [system_using_networktime](#system_using_networktime)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### system_always_keeps_windows

Always keep windows open on quit

#### Default value

```YAML
system_always_keeps_windows: false
```

### system_auto_download

Enable auto download

#### Default value

```YAML
system_auto_download: true
```

### system_auto_update

Enable auto update

#### Default value

```YAML
system_auto_update: true
```

### system_available_languages

List of available system languages

#### Default value

```YAML
system_available_languages:
  - en_US
  - en
  - de_DE
  - de
```

### system_computer_sleep

Define computer sleep time

#### Default value

```YAML
system_computer_sleep: 20
```

### system_critical_update

Enable critical update

#### Default value

```YAML
system_critical_update: true
```

### system_display_sleep

Define system sleep time

#### Default value

```YAML
system_display_sleep: 10
```

### system_enable_ntp

Enable networktime client

### system_font_smoothing

Apple font smoothing level

#### Default value

```YAML
system_font_smoothing: 2
```

### system_harddisk_sleep

Define disk sleep time

#### Default value

```YAML
system_harddisk_sleep: Never
```

### system_hostname

Define host, computer, local and netbios name

#### Default value

```YAML
system_hostname: '{{ ansible_hostname }}'
```

### system_locale

Define active system locale

#### Default value

```YAML
system_locale: en_US@currency=EUR
```

### system_login_admin_host_info

Admin host info

#### Default value

```YAML
system_login_admin_host_info: HostName
```

### system_login_disable_autologin

Disable auto login

#### Default value

```YAML
system_login_disable_autologin: true
```

### system_login_guest_enabled

Guest login enabled

#### Default value

```YAML
system_login_guest_enabled: false
```

### system_login_restart_disabled

Disable restart on login

#### Default value

```YAML
system_login_restart_disabled: true
```

### system_login_retries_until_hint

Retries until hint

#### Default value

```YAML
system_login_retries_until_hint: 0
```

### system_login_show_input_menu

Show input menu

#### Default value

```YAML
system_login_show_input_menu: true
```

### system_login_show_user_list

Show login userlist

#### Default value

```YAML
system_login_show_user_list: false
```

### system_login_shutdown_disabled

Disable shutdown on login

#### Default value

```YAML
system_login_shutdown_disabled: true
```

### system_login_user_switching

Login user switching

#### Default value

```YAML
system_login_user_switching: 1
```

### system_measurement_unit

Define system measurement unit

#### Default value

```YAML
system_measurement_unit: Centimeters
```

### system_metric_unit

Enable metric measurement unit

#### Default value

```YAML
system_metric_unit: true
```

### system_notification_banner_time

Notification banner duration

#### Default value

```YAML
system_notification_banner_time: 3
```

### system_quarantine

Enable system quarantine

#### Default value

```YAML
system_quarantine: false
```

### system_quit_printer

Quit printer queue when jobs finished

#### Default value

```YAML
system_quit_printer: true
```

### system_restart_freeze

Restart on system freeze

#### Default value

```YAML
system_restart_freeze: true
```

### system_show_scrollbars

Show scrollbars behavior

#### Default value

```YAML
system_show_scrollbars: Always
```

### system_siri_enabled

Enable siri assistant

#### Default value

```YAML
system_siri_enabled: true
```

### system_siri_hotkey_tag

Define siri hotkey tag

#### Default value

```YAML
system_siri_hotkey_tag: 2
```

### system_siri_language

Define siri language

#### Default value

```YAML
system_siri_language: en-US
```

### system_siri_visible

Enable siri status menu visibility

#### Default value

```YAML
system_siri_visible: true
```

### system_siri_voice_feedback

Use device speaker for TTS

#### Default value

```YAML
system_siri_voice_feedback: 3
```

### system_smart_caps

Enable smart capitalization

#### Default value

```YAML
system_smart_caps: false
```

### system_smart_dashes

Enable smart dash substitution

#### Default value

```YAML
system_smart_dashes: false
```

### system_smart_period

Enable smart period substitution

#### Default value

```YAML
system_smart_period: false
```

### system_smart_quotes

Enable smart quote substitution

#### Default value

```YAML
system_smart_quotes: false
```

### system_spelling_check

Eanble automatic spelling correction

#### Default value

```YAML
system_spelling_check: false
```

### system_text_replacement

Enable automatic text replacement

#### Default value

```YAML
system_text_replacement: false
```

### system_timezone

Define system timezone

#### Default value

```YAML
system_timezone: Europe/Berlin
```

### system_user

User to run user-specific commands, defaults to homebrew_user

### system_using_networktime

#### Default value

```YAML
system_using_networktime: true
```

## Dependencies

None.

## License

Apache-2.0

## Author

Thomas Boerger
