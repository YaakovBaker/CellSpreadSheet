# CellSpreadSheet

<p><a href = "https://github.com/YaakovBaker/CellSpreadSheet"><Strong>CellSpreadSheet</Strong></a>
  <br>•	Multi-file array-based spreadsheet written in Java. The <i>CellSpreadSheet</i> class implemented the <i>CellProvider</i> interface, and stores either a <i>FormulaCell</i> or <i>DoubleCell</i>, both implementing the <i>Cell</i> interface. The spreadsheet is constructed by passing in arguments into the <i>CellSpreadSheet</i> constructor specifying the row and column size of the spreadsheet. Afterwards the client can call a <i>setValue()</i> method to store data in the spreadsheet at the specified location. If the user wants a visualization of the spreadsheet then they can call <i>getSpreadSheetAsCSV(boolean)</i> by passing in true if they want it to show the formulas and false if they want the formulas to be calculated and then a spreadsheet in CSV format with those specifications is printed. A demo file can be found <a href = "https://github.com/YaakovBaker/CellSpreadSheet/blob/main/SpreadSheet/Assignment7Demo.java">here</a>.</P>
