# 🌍 Africa Ethnic Groups — Shapefile Dataset

![QGIS](https://img.shields.io/badge/QGIS-3.x-93b023?style=for-the-badge&logo=qgis&logoColor=white)
![ArcGIS](https://img.shields.io/badge/ArcGIS-Compatible-2C7AC3?style=for-the-badge&logo=arcgis&logoColor=white)
![Format](https://img.shields.io/badge/Format-Shapefile-FF6F00?style=for-the-badge)
![License](https://img.shields.io/badge/License-Open_Data-blue?style=for-the-badge)
![Continent](https://img.shields.io/badge/Region-Africa-green?style=for-the-badge)
![GIS](https://img.shields.io/badge/GIS-Geospatial-purple?style=for-the-badge)
![Made With](https://img.shields.io/badge/Made_With-❤️-ff69b4?style=for-the-badge)
![GitHub Stars](https://img.shields.io/github/stars/Heed725/Africa_Ethnic_Groups?style=for-the-badge&logo=github)

---

<p align="center">

  <a href="https://github.com/Heed725/Africa_Ethnic_Groups/archive/refs/heads/main.zip">
    <img src="https://img.shields.io/badge/⬇️_DOWNLOAD_ZIP-All_Files-2ea44f?style=for-the-badge" alt="Download ZIP"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/Heed725/Africa_Ethnic_Groups/raw/main/Africa_Ethnicity_Shapefile.shp">
    <img src="https://img.shields.io/badge/⬇️_Download-.SHP-orange?style=for-the-badge" alt="Download SHP"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/Heed725/Africa_Ethnic_Groups/raw/main/Africa_Ethnicity_Shapefile.dbf">
    <img src="https://img.shields.io/badge/⬇️_Download-.DBF-orange?style=for-the-badge" alt="Download DBF"/>
  </a>

</p>

<p align="center">

  <a href="https://github.com/Heed725/Africa_Ethnic_Groups/raw/main/Africa_Ethnicity_Shapefile.shx">
    <img src="https://img.shields.io/badge/⬇️_Download-.SHX-blue?style=flat-square" alt="Download SHX"/>
  </a>
  &nbsp;
  <a href="https://github.com/Heed725/Africa_Ethnic_Groups/raw/main/Africa_Ethnicity_Shapefile.prj">
    <img src="https://img.shields.io/badge/⬇️_Download-.PRJ-blue?style=flat-square" alt="Download PRJ"/>
  </a>
  &nbsp;
  <a href="https://github.com/Heed725/Africa_Ethnic_Groups/raw/main/Africa_Ethnicity_Shapefile.cpg">
    <img src="https://img.shields.io/badge/⬇️_Download-.CPG-blue?style=flat-square" alt="Download CPG"/>
  </a>
  &nbsp;
  <a href="https://github.com/Heed725/Africa_Ethnic_Groups/raw/main/Africa_Ethnicity_Shapefile.qmd">
    <img src="https://img.shields.io/badge/⬇️_Download-.QMD-blue?style=flat-square" alt="Download QMD"/>
  </a>
  &nbsp;
  <a href="https://github.com/Heed725/Africa_Ethnic_Groups/raw/main/Africa_Ethnicity_QML.qml">
    <img src="https://img.shields.io/badge/⬇️_Download-.QML_Style-9C27B0?style=flat-square" alt="Download QML"/>
  </a>

</p>

> **💡 Recommended:** Use the **Download ZIP** button above to get all files at once. All shapefile components must be in the same folder to work correctly.

---

## 📋 Overview

A geospatial dataset mapping **ethnic groups across the African continent** as an ESRI Shapefile, bundled with a QGIS style file (`.qml`) for ready-to-use cartographic visualization. This dataset provides polygon boundaries delineating the spatial distribution of ethnic groups throughout Africa.

---

## 📁 Repository Contents

| File | Extension | Description |
|------|-----------|-------------|
| `Africa_Ethnicity_Shapefile.shp` | `.shp` | **Geometry file** — contains the polygon shapes for each ethnic group boundary |
| `Africa_Ethnicity_Shapefile.shx` | `.shx` | **Shape index** — spatial index for quick geometry lookup |
| `Africa_Ethnicity_Shapefile.dbf` | `.dbf` | **Attribute table** — stores attribute data (ethnic group names, properties) |
| `Africa_Ethnicity_Shapefile.prj` | `.prj` | **Projection file** — defines the coordinate reference system (CRS) |
| `Africa_Ethnicity_Shapefile.cpg` | `.cpg` | **Code page file** — specifies character encoding for the `.dbf` file |
| `Africa_Ethnicity_Shapefile.qmd` | `.qmd` | **QGIS metadata** — layer metadata for QGIS |
| `Africa_Ethnicity_QML.qml` | `.qml` | **QGIS style file** — pre-configured symbology with categorized colors per ethnic group |

> ⚠️ **Important:** All shapefile components (`.shp`, `.shx`, `.dbf`, `.prj`, `.cpg`) must be kept in the **same directory** for the data to load correctly. Never separate these files.

---

## 🖥️ Requirements

| Software | Minimum Version | Notes |
|----------|----------------|-------|
| **QGIS** | 3.x+ | Free & open source — recommended |
| **ArcGIS Pro** | 2.x+ | Commercial alternative |
| **ArcMap** | 10.x+ | Legacy Esri desktop |
| **GDAL/OGR** | 3.x+ | Command-line tools |
| **GeoPandas** | 0.9+ | Python scripting |

---

## 📥 How to Download

### Option 1 — Clone the Repository

```bash
git clone https://github.com/Heed725/Africa_Ethnic_Groups.git
```

### Option 2 — Download as ZIP

1. Click the green **Code** button at the top of the repository
2. Select **Download ZIP**
3. Extract the ZIP to your desired folder

### Option 3 — Download Individual Files

Click on any file in the repository, then click the **Download raw file** button (⬇️ icon).

> Remember to download **all** shapefile components together.

---

## 🗺️ How to Import

### In QGIS

#### Method 1 — Drag and Drop (Fastest)

1. Open **QGIS**
2. Navigate to the folder containing the shapefile in your file manager
3. **Drag** `Africa_Ethnicity_Shapefile.shp` directly into the QGIS **map canvas**
4. The layer loads instantly

#### Method 2 — Add Vector Layer

1. Open QGIS
2. Go to **Layer** → **Add Layer** → **Add Vector Layer** (or press `Ctrl+Shift+V`)
3. Click **Browse (...)** and navigate to `Africa_Ethnicity_Shapefile.shp`
4. Click **Add** → **Close**

#### Method 3 — Browser Panel

1. In the QGIS **Browser Panel** (left sidebar), navigate to the folder
2. Expand the folder to see the `.shp` file
3. Double-click `Africa_Ethnicity_Shapefile.shp` to add it to the map

### In ArcGIS Pro

1. Open ArcGIS Pro and create/open a project
2. In the **Catalog Pane**, navigate to the folder containing the shapefile
3. Drag `Africa_Ethnicity_Shapefile.shp` onto the map, or right-click → **Add to Current Map**

### In Python (GeoPandas)

```python
import geopandas as gpd

# Load the shapefile
ethnic_groups = gpd.read_file("Africa_Ethnicity_Shapefile.shp")

# Preview the data
print(ethnic_groups.head())
print(f"Total features: {len(ethnic_groups)}")
print(f"CRS: {ethnic_groups.crs}")

# Quick plot
ethnic_groups.plot(column="NAME", legend=False, figsize=(12, 12))
```

### In R

```r
library(sf)

ethnic_groups <- st_read("Africa_Ethnicity_Shapefile.shp")
summary(ethnic_groups)
plot(ethnic_groups["NAME"])
```

### Using GDAL Command Line

```bash
# View layer info
ogrinfo -so Africa_Ethnicity_Shapefile.shp Africa_Ethnicity_Shapefile

# Convert to GeoJSON
ogr2ogr -f "GeoJSON" output.geojson Africa_Ethnicity_Shapefile.shp
```

---

## 🎨 How to Apply the QML Style

The included `.qml` file provides **categorized symbology** with distinct colors for each ethnic group, so you don't have to style the layer manually.

### Automatic Loading

If `Africa_Ethnicity_QML.qml` is in the **same folder** as the shapefile and shares the same base name, QGIS may load it automatically.

### Manual Loading

1. Right-click the loaded layer in the **Layers Panel** → **Properties**
2. Go to the **Symbology** tab
3. Click the **Style** button (bottom-left) → **Load Style...**
4. Browse to `Africa_Ethnicity_QML.qml`
5. Click **Load Style** → **OK**

### Save as Default

To make the style load automatically every time:

1. Apply the style (steps above)
2. Click **Style** → **Save as Default**
3. Now the style loads whenever you open this shapefile

---

## 💡 Use Cases

- **Ethno-linguistic Research** — Map and analyze the distribution of ethnic and linguistic groups across Africa
- **Historical Studies** — Understand pre-colonial and post-colonial ethnic boundaries
- **Demographic Analysis** — Overlay with population, census, or migration data
- **Conflict Studies** — Correlate ethnic boundaries with conflict zones
- **Education** — Teaching African geography, cultural diversity, and GIS techniques
- **Urban & Regional Planning** — Support culturally sensitive development planning

---

## 📐 Shapefile Format Reference

For those new to shapefiles, here's what each component does:

```
Africa_Ethnicity_Shapefile/
│
├── .shp    ← The actual geometry (polygons, lines, points)
├── .shx    ← Index linking geometries to attributes (required)
├── .dbf    ← Attribute data table (names, codes, etc.)
├── .prj    ← Coordinate Reference System definition
├── .cpg    ← Character encoding (UTF-8, etc.)
└── .qmd    ← QGIS-specific metadata (optional)
```

The **mandatory trio** is `.shp` + `.shx` + `.dbf`. Without all three, the file won't open. The `.prj` is technically optional but critical for correct geographic positioning.

---

## 🔧 Troubleshooting

| Problem | Solution |
|---------|----------|
| Layer won't load | Ensure all shapefile components (`.shp`, `.shx`, `.dbf`) are in the same folder |
| Layer appears in wrong location | Check that the `.prj` file is present; reproject if CRS doesn't match your project |
| Attribute text shows garbled characters | Verify the `.cpg` file is present (it defines encoding) |
| QML style doesn't apply | Manually load the style via **Properties → Symbology → Style → Load Style** |
| "Layer is not valid" error | Re-download all files; one may be corrupted or incomplete |
| Empty attribute table | The `.dbf` file may be missing or damaged — re-download it |

---

## 🤝 Contributing

Contributions are welcome! If you have corrections, additional data, or improvements:

1. **Fork** the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m "Add improvement"`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a **Pull Request**

---

## 📝 License

This dataset is shared for educational and research purposes. Please check the original data source for specific licensing terms before using in commercial projects.

---

## 🔗 Related Repositories

| Repository | Description |
|------------|-------------|
| [Tanzania_Ethnicity_Shapefile](https://github.com/Heed725/Tanzania_Ethnicity_Shapefile) | Ethnic group shapefile for Tanzania |

---

## 🔗 Related Resources

- [QGIS Official Documentation](https://docs.qgis.org/)
- [GREG — Geo-referencing of Ethnic Groups (ETH Zurich)](https://icr.ethz.ch/data/greg/)
- [Africa GeoPortal](https://www.africageoportal.com/)
- [openAFRICA Data Portal](https://open.africa/)

---

> **Tip:** For best results, use QGIS with the included `.qml` style file — it provides instant, publication-ready visualization of all ethnic group boundaries with categorized colors. ⭐
