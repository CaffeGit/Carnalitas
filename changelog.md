# Carnalitas v1.3

## New Features

### Birth Control

* Added a game rule that allows you to enable birth control for male and female rulers. This is a togglable modifier that reduces your fertility chance but also drains your income and piety slightly.

### Slavery System Update

* Added a mass enslave character interaction, available by right-clicking yourself.
* Added UI buttons for enslave and mass enslave interactions to the prison view. This overwrites `window_court.gui` and `buttons_icons.gui`.
* `carn_enslave_interaction_effect` has been turned into a scripted effect to make the new mass enslave interaction work.

### Body Part Traits

* Added character flags: `carn_seed_tits_big_1` through `carn_seed_tits_big_3` and so on for all the body part traits. If a historical character has these flags, or if a character is spawned with these flags, they will be force seeded with the corresponding trait if the body part trait game rule is active.

### Futanari

* Added character flag `carn_seed_futa` which functions similarly to body part trait character flags above.

### Miscellaneous

* Added possible doctrine parameters `naked_females_active` and `naked_males_active` to our is_naked_trigger overwrite. This effectively makes the framework compatible with Nudity Laws.

New on_actions for modders:
* `carn_on_start_birth_control`
* `carn_on_stop_birth_control`
* `carn_on_start_working_as_prostitute`
* `carn_on_stop_working_as_prostitute`

## Compatibility

* Harem Doctrines GUI is now integrated with Carnalitas, so you can expand the list of your spouses and concubines if you have more than 3.

## Tweaks

* Carnalitas's new religious doctrines now add no additional piety cost to convert or create a new faith if you leave them unchanged. This is to maintain balance with vanilla CK2.

## Bug Fixes

* Fixed being unable to see your rivals if you have too many slaves.