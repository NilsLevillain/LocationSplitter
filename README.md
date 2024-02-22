# LocationSplitter
Split Manhattan Active WMS 'Storage Location' data loaders for data ingestion, by taking an original file and splitting it in multiple files of 500 lines, for the tabs 'Location' and 'LocationUom'.

This allows a reduction of manual labor for the cutover tasks by several hours, multiplied by multiple times during the project (ingestion of storage location files should be done throughout different phases of the implementation of Manhattan Active WMS). 

This is a redundant task and error-prone, without any added-value, thus the birth of this tool !
