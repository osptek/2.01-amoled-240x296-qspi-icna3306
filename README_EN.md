# 2.01" 240×296 AMOLED QSPI module (ICNA3306) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 2.01-inch **AMOLED** panel, **240×296** resolution |
| Interface | **QSPI** |
| Driver IC | **ICNA3306** |
| Spec ID | **`2.01-amoled-240x296-qspi-icna3306`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, interface and initialization documentation |
| `examples/` | **Sample projects** grouped by feature |

### `examples/` layout

| Location | Description |
|:--|:--|
| `examples/` root | **LVGL8 / LVGL9** with **esp-lvgl-adapter** (no standalone LVGL8 baseline project in this bundle) |
| `with-te/` | Display sync and tear-related samples using **TE** |
| `with-te-sw-rotate-90/` | **TE**-based flow plus **90° software rotation** |

### Sample project paths

#### Baseline and esp-lvgl-adapter

| Description | Path |
|:--|:--|
| esp-lvgl-adapter + LVGL8 | `examples/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl8/` |
| esp-lvgl-adapter + LVGL9 | `examples/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl9/` |

#### with-te

| Description | Path |
|:--|:--|
| esp-lvgl-adapter + LVGL8 + AMOLED with TE | `examples/with-te/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/` |
| esp-lvgl-adapter + LVGL9 + AMOLED with TE | `examples/with-te/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/` |

#### with-te-sw-rotate-90

| Description | Path |
|:--|:--|
| LVGL8 + AMOLED with TE + 90° software rotation | `examples/with-te-sw-rotate-90/esp32s3-idf5_icna3306-qspi_lvgl8_amoled-with-te/` |
