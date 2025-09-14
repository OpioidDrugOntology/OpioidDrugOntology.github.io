# ODO Website (Opioid Drug Ontology Data  Portal)


This repository hosts the GitHub Pages site for the Opioid Drug Ontology (ODO) Data Portal:       
👉 https://opioiddrugontology.github.io

The official ODO Data Portal is available at:  
👉 https://opioiddrugontology.org

The site provides access to curated datasets, database schema, and user interface (UI) specifications that support the ODO Data Portal.

---
📊 Available Downloads
---
You can download the following resources directly:

ODO Dataset Statistics (CSV)

Summary statistics for the curated ODO dataset.

ODO SQL Tables (CSV)

Entity–relationship tables that define the ODO database schema.

ODO UI Columns and Filters (CSV)

Column names and main filtering views for the ODO Data Portal user interface.

---
🔎 UI Search and Filtering
---
The ODO Data Portal provides flexible search and filtering options to help users explore the dataset efficiently:

Pre-aligned views
Data can be browsed through pre-configured views based on assay format (biochemical, cell-based, tissue-based, or organism-based). Each view highlights metadata most relevant to that format (e.g., cell line for cell-based assays, organism strain for organism-based assays).

Custom filtering
Within each view, users can refine searches using available metadata fields such as compound identifiers, protein targets, endpoints, and units.

Download options
Any filtered view can be exported for offline use. For maximum flexibility, the complete dataset with all metadata columns is available as a download, while the interactive UI is limited to ~20 visible columns at a time.

For details on available columns and filter options, see odo_ui_columns_and_filters.csv in the GitHub repository

---
📂 Repository Structure
---
```pre
OpioidDrugOntology.github.io/
├─ index.html                  # Website homepage
├─ images/
│  └─ odo_logo.png             # Portal logo
├─ data/
│  ├─ odo_dataset_statistics.csv
│  ├─ odo_sql_tables.csv
│  └─ odo_ui_columns_and_filters.csv
└─ README.md
```

---
📑 Notes
---
The Opioid Drug Ontology (ODO) terms are not maintained as a standalone ontology.

Instead, selected ODO metadata categories and terms are being incorporated directly into the BioAssay Ontology (BAO) on an ongoing basis.

This ensures alignment with a widely adopted ontology and allows metadata generated from the ODO Data Portal to be FAIR, interoperable, and reusable without introducing redundant schema.

All term requests, mappings, and ontology discussions are tracked through the BAO GitHub repository, with references documented in this portal for transparency.

