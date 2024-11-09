# Simple CSV Editor

Simple CSV Editor is a simple application for viewing, editing, and saving CSV (Comma-Separated Values) files. This user-friendly tool allows you to perform common operations on CSV files with ease.
Remember that in order to Edit a world of warcraft DBC you need DBCUtill so that you could convert it to CSV and do the edit.
I know there is plenty of tools that does editing, but I made it for a specified reason which to modify all rows for a specified column.

![Screenshot](https://github.com/JadaDev/SimpleCSVEditor/blob/main/SimpleCSVEditorLogo.png?raw=true)

## Features

- Load CSV files.
- View and edit CSV data in a tabular format.
- Save changes back to the original file.
- Modify a specified column for all rows.
- User-friendly graphical interface.

## Getting Started

### Requirements

- DBCUtill to Convert DBC to CSV

### Installation

1. Download from JadaDev Github.
2. Run the Simple CSV Editor executable (`.exe`).

### Usage

1. **Load CSV File**:
   - Click on the "Load CSV" menu option.
   - Select the CSV file you want to edit.

2. **View and Edit Data**:
   - Data from the loaded CSV file will be displayed in a tabular format.
   - You can manually edit cell values by double-clicking on them.

3. **Save CSV File**:
   - Click on the "Save CSV" menu option to save your changes back to the original file.

4. **Modify a Column**:
   - Enter the column index and the new value in the provided fields.
   - Click the "Modify Column" button to update the specified column for all rows.

### Usage-Info

1. After using Modify a column it actually modify even the type so you'll need to rewrite it back if it was int or float.


### Screenshots

![Screenshot](https://github.com/JadaDev/SimpleCSVEditor/blob/main/Simple%20CSV%20Editor%20SS.png?raw=true)

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## In Order to change TrinityCore Spells to Scale for 255 server you'd need to edit column 38 & 39 with new value = 255

# You can use wow parsper convert spell.dbc to csv and edit with this tool ( New Value = 255 ) & ( Column 38 ) & ( Column 39 )
# Than you'd have to change the first row from 255 to int, int.
