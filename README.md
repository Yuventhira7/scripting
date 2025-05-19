# Board Games Data Analysis

This project contains three shell scripts (`empty_cells`, `preprocess`, and `analysis`) designed to process and analyze a dataset of board games.

## Scripts

### `empty_cells`

This script takes a text file  and a separator character as input. It outputs a list of the column titles (headers) along with the number of empty cells found in each column.

**Usage:**

```bash
./empty_cells <input_file> <separator>
```

---

### `preprocess`

This script takes a text file as input and outputs a cleaned version of the file. It performs necessary preprocessing steps such as standardizing headers, removing non-printable characters, and assigning new IDs if needed.

**Usage:**

```bash
./preprocess <input_file>
```

---

### `analysis`

This script uses the cleaned dataset to answer four research questions based on board game attributes. It performs analysis such as computing correlations, identifying popular game, and most game domain.

**Usage:**

```bash
./analysis <cleaned_data_file>
```
