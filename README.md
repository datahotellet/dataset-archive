# dataset-archive
Archive datasets previously distributed from the Datahotel ([hotell.difi.no](https://hotell.difi.no))

## Data format
All datasets are provided in CSV format, with UTF-8 encoding. The CSV files use semicolons (;) as column separators and double quotes (") as the escape character.

## Files
The following files are included in the dataset archive:

### Original files
As they were stored in the Data hotel
- `meta.xml`: Metadata file containing information about the dataset.
- `fields.xml`: XML file describing the fields in the dataset.
- `dataset.original.csv`: The main dataset file in CSV format.

### Generated files
- `dataset.csv`: The main dataset file in CSV format, generated from dataset.original.csv.
- `sample.csv`: A sample of the dataset with a reduced set of rows (max 50 kB file) and slightly different format in order for preview to work on GitHub.
- `fields.csv`: A CSV file describing the fields in the dataset. Generated from fields.xml.
- `README.md`: Documentation file describing the dataset and its contents, also has a human-readable timestamp of when the dataset was last updated (from unix timestamp in meta.xml)

### Difference between dataset.csv and original
The original (`dataset.original.csv`) is the unmodified dataset file as it was stored in the Data hotel, while `dataset.csv` is a processed version.

Make a table:
| Feature               | dataset.original.csv | dataset.csv          |
|-----------------------|----------------------|-----------------------|
| Encoding              | UTF-8                | UTF-8 with BOM        |
| Escape character      | \                    | "                     |

The original was formatted without BOM (Byte Order Mark), while the generated file includes a BOM for better compatibility with certain applications, for example opening in Excel and other spreadsheet software.