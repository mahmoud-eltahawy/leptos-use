# Changelog

## 0.1.10

#### Braking Changes
- `watch` doesn't accept `immediate` as an argument anymore. This is only provided by the option variant.

#### New Functions
- `use_local_storage`
- `watch_debounced`
- `watch_throttled`
- `watch_pausable`

#### Other Changes

- `watch` has now variant `watch_with_options` which allows for debouncing and throttling.

## 0.1.8/9

- Fixed documentation and doc tests running for functions behind `#[cfg(web_sys_unstable_apis)]`

## 0.1.7

#### New Function
- `use_element_size`

## 0.1.6

- Fixed documentation so all feature are documented

## 0.1.5

#### New Functions
- `use_floor`
- `use_max`
- `use_min`

#### Other Changes
- New feature: `math` that has to be activated in order to use the math functions.

## 0.1.4

#### New Functions
- `use_supported`
- `use_resize_observer`
- `watch`
- `use_mouse`

#### Other Changes
- Use the crate `default-struct-builder` to provide ergonimic function options.

## 0.1.3

#### New Functions
- `use_scroll`
- `use_debounce_fn`

#### Other Changes
- Better and more beautiful demo integration into the guide.