
## Instructions

1. **R Script**: The main analysis script can be found in the `R/` folder named `script.R`.
2. **Data**: Raw data is stored in the `data/` folder.
   - `EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb/`: EJScreen data.
   - `gbif-birds-LA/`: Bird observations data.
   - ...

## Results and Findings

### Part 1: Data Exploration

- Map of wastewater discharge in Los Angeles County.
- Percentage of low-income population in census block groups.
- Census block groups with high air pollution and low Superfund proximity.
- Mapping of HOLC grade designations for Los Angeles.

### Part 2: Data Analysis and Decision Making

- Bird observations from 2022 within HOLC grades.
- Percent of bird observations within each redlining category.
- Visualization of redlining areas and bird diversity index averages.

### Data structure
```{r}
.
└── Environmental_racism
    ├── data
    │   ├── EJSCREEN_2023_BG_Columns.xlsx
    │   ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
    │   │   ├── a00000001.freelist
    │   │   ├── a00000001.gdbindexes
    │   │   ├── a00000001.gdbtable
    │   │   ├── a00000001.gdbtablx
    │   │   ├── a00000001.TablesByName.atx
    │   │   ├── a00000002.gdbtable
    │   │   ├── a00000002.gdbtablx
    │   │   ├── a00000003.gdbindexes
    │   │   ├── a00000003.gdbtable
    │   │   ├── a00000003.gdbtablx
    │   │   ├── a00000004.CatItemsByPhysicalName.atx
    │   │   ├── a00000004.CatItemsByType.atx
    │   │   ├── a00000004.FDO_UUID.atx
    │   │   ├── a00000004.freelist
    │   │   ├── a00000004.gdbindexes
    │   │   ├── a00000004.gdbtable
    │   │   ├── a00000004.gdbtablx
    │   │   ├── a00000004.horizon
    │   │   ├── a00000004.spx
    │   │   ├── a00000005.CatItemTypesByName.atx
    │   │   ├── a00000005.CatItemTypesByParentTypeID.atx
    │   │   ├── a00000005.CatItemTypesByUUID.atx
    │   │   ├── a00000005.gdbindexes
    │   │   ├── a00000005.gdbtable
    │   │   ├── a00000005.gdbtablx
    │   │   ├── a00000006.CatRelsByDestinationID.atx
    │   │   ├── a00000006.CatRelsByOriginID.atx
    │   │   ├── a00000006.CatRelsByType.atx
    │   │   ├── a00000006.FDO_UUID.atx
    │   │   ├── a00000006.freelist
    │   │   ├── a00000006.gdbindexes
    │   │   ├── a00000006.gdbtable
    │   │   ├── a00000006.gdbtablx
    │   │   ├── a00000007.CatRelTypesByBackwardLabel.atx
    │   │   ├── a00000007.CatRelTypesByDestItemTypeID.atx
    │   │   ├── a00000007.CatRelTypesByForwardLabel.atx
    │   │   ├── a00000007.CatRelTypesByName.atx
    │   │   ├── a00000007.CatRelTypesByOriginItemTypeID.atx
    │   │   ├── a00000007.CatRelTypesByUUID.atx
    │   │   ├── a00000007.gdbindexes
    │   │   ├── a00000007.gdbtable
    │   │   ├── a00000007.gdbtablx
    │   │   ├── a00000039.freelist
    │   │   ├── a00000039.gdbindexes
    │   │   ├── a00000039.gdbtable
    │   │   ├── a00000039.gdbtablx
    │   │   ├── a00000039.horizon
    │   │   ├── a00000039.I49AREALAND_1.atx
    │   │   ├── a00000039.I49AREALAND.atx
    │   │   ├── a00000039.I49AREAWATER.atx
    │   │   ├── a00000039.I49ID.atx
    │   │   ├── a00000039.spx
    │   │   ├── EJSCREEN - Shortcut.lnk
    │   │   ├── gdb
    │   │   └── timestamps
    │   ├── ejscreen-tech-doc-version-2-2.pdf
    │   ├── gbif-birds-LA
    │   │   ├── gbif-birds-LA.dbf
    │   │   ├── gbif-birds-LA.prj
    │   │   ├── gbif-birds-LA.shp
    │   │   └── gbif-birds-LA.shx
    │   └── __MACOSX
    │       ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
    │       └── gbif-birds-LA
    ├── Env_racism_Biodiversity.html
    ├── Env_racism_Biodiversity.Rmd
    ├── Env_racism.Rproj
    └── README.md
```

## Recommendations

- The analysis suggests a strong correlation between historical redlining and current environmental issues.
- Policy makers should consider biodiversity implications when planning conservation efforts in low-graded areas.
- The project challenges the assumption that low-graded areas have low species diversity.

## Acknowledgments

- This project was inspired by research studies and datasets from various sources.
- Special thanks to the Digital Scholarship Lab at the University of Richmond for the Mapping Inequality project.


**Note:** the data associated with this assignment is too large to include in the GitHub repo. Instead, download data from [here](https://drive.google.com/file/d/1lcazRbNSmP8Vj9sH1AIJcO4D1d_ulJij/view?usp=share_link). Unzip the folder and all the contents and store in your directory as follows. Don't include data when you submit your assignment!

```
