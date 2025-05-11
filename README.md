# Urban Noise Data – Sonnenstraße, Munich
![证明声音不同的分析图](https://github.com/user-attachments/assets/617f47af-efc1-4719-8d45-95221199191d)

This repository contains measured urban noise data collected at multiple locations along **Sonnenstraße**, a major street in central Munich, Germany.

Each file corresponds to a specific location and contains time-series data of sound pressure level (SPL) measured in decibels (dB). The data was collected using the Phyphox app and post-processed using Python and pandas.

## 📂 File Description

| File Name                       | Description                     |
|--------------------------------|---------------------------------|
| `restaurant.xlsx`              | Near restaurant with public activity |
| `park_music.xlsx`              | Green area with music playing       |
| `quiet_tram_start.xlsx`        | Quiet tram start zone               |
| `subway_exit.xlsx`             | Subway exit area                    |
| `car_idle.xlsx`                | Idle vehicle by the curb            |
| `car_starting.xlsx`            | Car starting area                   |
| `busy_street.xlsx`             | Main traffic road segment           |
| `busy_street2.xlsx`            | Secondary traffic road              |
| `calm_sidewalk.xlsx`           | Quiet sidewalk without events       |
| `motorcycle_passing.xlsx`      | Motorcycle pass-by event            |
| `construction_site.xlsx`       | Active construction site            |
| `store_crowd.xlsx`             | Retail store with crowd             |
| `intersection_tram_arrival.xlsx` | Tram and car arrival at intersection |
| `tram_sound_source.xlsx`       | Tram source sound recorded directly |

## 📊 Columns in Each File

- `Time (s)`: Timestamp in seconds  
- `Sound pressure level (dB)`: SPL in decibels  
- (Post-processed files may also contain `Calibrated dB` after +90 dB offset correction)

## ⚠️ Notes

- All SPL values are relative and based on calibration using a quiet reference environment.
- A danger threshold of **68 dB** was applied to assess urban noise impact.
- Visualization scripts and annotated charts are available separately.

To see my analysis and diagramms, you have to download this source files and rename the address from |C/xxxx/xxxx/xxx|,which is mine, to your address

## 🛠 Tools Used

- Python (`pandas`, `matplotlib`, `seaborn`)
- Photoshop for visual styling
- [Phyphox](https://phyphox.org/) app for data acquisition

---

If you use this data or the visualizations, please cite accordingly or include attribution in your project.
