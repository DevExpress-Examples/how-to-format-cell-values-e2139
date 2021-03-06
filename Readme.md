<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/HowToCellFormat/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/HowToCellFormat/MainWindow.xaml))
<!-- default file list end -->
# How to: Format Cell Values


<p>This example demonstrates how to format values in a pivot grid cells. In this sample, it is illustrated how to format data that corresponds to <strong>Quantity</strong> and <strong>Extended Price</strong> data fields in a <strong>PivotGridControl</strong>.</p>


<h3>Description</h3>

<p>For the <strong>Quantity</strong> field the <strong>PivotGridField.CellFormat</strong> property is used to format data in a custom manner. The values that correspond to this field are enclosed with round brackets. The formatting settings specified by the <strong>PivotGridField.CellFormat</strong> property also affect the representation of total and grand total cells.</p><p>The <strong>Extended Price</strong> field is bound to a field that contains currency data. By default the cell values that correspond to such fields are formatted as currency amounts (the formatting settings are determined by the regional settings). For the &quot;English (United States)&quot; culture, the currency values are represented using two digits to the right of the decimal point. In the example, the <strong>PivotGridField.GrandTotalCellFormat</strong> property is used to format grand total cell values for the <strong>Extended Price</strong> field in a different manner. The data in these cells is formatted as integer currency values (without fractional portions).</p>

<br/>


