# Library-Tools

This project is a UiPath tools library.

## Language
C#

## Contents
1. File_ReadExcelToTable
1. File_ReadWorkbookToTable

### File_ReadExcelToTable
This workflow reads a worksheet in a Microsoft Excel document by using the Excel activities and returns a data table.

##### Arguments
1. String in_FilePath - The file path to the Microsoft Excel document.
2. String in_Worksheet - The worksheet name.
3. Boolean in_WorksheetHasHeaders - If the worrksheet has a header row.
4. String in_WorksheetRange
5. DataTable out_Dt_Data

### File_ReadWorkbookToTable

| Type | Argument | Annotation |
| -------- | ------- | ------- |
| String | in_FilePath | The file path to the Microsoft Excel document. |
| String | in_Worksheet | The worksheet name. |
| Boolean | in_WorksheetHasHeaders | If the worrksheet has a header row. |
| String | in_WorksheetRange | The range of the worksheet.  The entire sheet will be read if the worksheet range is blank.
| DataTable | out_Dt_Data | The data table containing the worksheet data.
