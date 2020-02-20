
## Default Variables

### system_always_keeps_windows

Always keep windows open on quit

#### Default value

```yaml
system_always_keeps_windows: false
```

### system_auto_download

Enable auto download

#### Default value

```yaml
system_auto_download: true
```

### system_auto_update

Enable auto update

#### Default value

```yaml
system_auto_update: true
```

### system_available_languages

List of available system languages

#### Default value

```yaml
system_available_languages:
  - en_US
  - en
  - de_DE
  - de
```

### system_computer_sleep

Define computer sleep time

#### Default value

```yaml
system_computer_sleep: 20
```

### system_critical_update

Enable critical update

#### Default value

```yaml
system_critical_update: true
```

### system_display_sleep

Define system sleep time

#### Default value

```yaml
system_display_sleep: 10
```

### system_enable_ntp

Enable networktime client

### system_font_smoothing

Apple font smoothing level

#### Default value

```yaml
system_font_smoothing: 2
```

### system_harddisk_sleep

Define disk sleep time

#### Default value

```yaml
system_harddisk_sleep: Never
```

### system_hostname

Define host, computer, local and netbios name

#### Default value

```yaml
system_hostname: '{{ ansible_hostname }}'
```

### system_locale

Define active system locale

#### Default value

```yaml
system_locale: en_US@currency=EUR
```

### system_login_admin_host_info

Admin host info

#### Default value

```yaml
system_login_admin_host_info: HostName
```

### system_login_disable_autologin

Disable auto login

#### Default value

```yaml
system_login_disable_autologin: true
```

### system_login_guest_enabled

Guest login enabled

#### Default value

```yaml
system_login_guest_enabled: false
```

### system_login_restart_disabled

Disable restart on login

#### Default value

```yaml
system_login_restart_disabled: true
```

### system_login_retries_until_hint

Retries until hint

#### Default value

```yaml
system_login_retries_until_hint: 0
```

### system_login_show_input_menu

Show input menu

#### Default value

```yaml
system_login_show_input_menu: true
```

### system_login_show_user_list

Show login userlist

#### Default value

```yaml
system_login_show_user_list: false
```

### system_login_shutdown_disabled

Disable shutdown on login

#### Default value

```yaml
system_login_shutdown_disabled: true
```

### system_login_user_switching

Login user switching

#### Default value

```yaml
system_login_user_switching: 1
```

### system_measurement_unit

Define system measurement unit

#### Default value

```yaml
system_measurement_unit: Centimeters
```

### system_metric_unit

Enable metric measurement unit

#### Default value

```yaml
system_metric_unit: true
```

### system_notification_banner_time

Notification banner duration

#### Default value

```yaml
system_notification_banner_time: 3
```

### system_quarantine

Enable system quarantine

#### Default value

```yaml
system_quarantine: false
```

### system_quit_printer

Quit printer queue when jobs finished

#### Default value

```yaml
system_quit_printer: true
```

### system_restart_freeze

Restart on system freeze

#### Default value

```yaml
system_restart_freeze: true
```

### system_screensaver_ask_for_password

Screensaver requires login password

#### Default value

```yaml
system_screensaver_ask_for_password: 1
```

### system_show_scrollbars

Show scrollbars behavior

#### Default value

```yaml
system_show_scrollbars: Always
```

### system_siri_enabled

Enable siri assistant

#### Default value

```yaml
system_siri_enabled: true
```

### system_siri_hotkey_tag

Define siri hotkey tag

#### Default value

```yaml
system_siri_hotkey_tag: 2
```

### system_siri_language

Define siri language

#### Default value

```yaml
system_siri_language: en-US
```

### system_siri_visible

Enable siri status menu visibility

#### Default value

```yaml
system_siri_visible: true
```

### system_siri_voice_feedback

Use device speaker for TTS

#### Default value

```yaml
system_siri_voice_feedback: 3
```

### system_smart_caps

Enable smart capitalization

#### Default value

```yaml
system_smart_caps: false
```

### system_smart_dashes

Enable smart dash substitution

#### Default value

```yaml
system_smart_dashes: false
```

### system_smart_period

Enable smart period substitution

#### Default value

```yaml
system_smart_period: false
```

### system_smart_quotes

Enable smart quote substitution

#### Default value

```yaml
system_smart_quotes: false
```

### system_spelling_check

Eanble automatic spelling correction

#### Default value

```yaml
system_spelling_check: false
```

### system_text_replacement

Enable automatic text replacement

#### Default value

```yaml
system_text_replacement: false
```

### system_timezone

Define system timezone

#### Default value

```yaml
system_timezone: Europe/Berlin
```

### system_user

User to run user-specific commands

#### Default value

```yaml
system_user | default(homebrew_user) | default(ansible_user_id)
```

### system_using_networktime

#### Default value

```yaml
system_using_networktime: true
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
