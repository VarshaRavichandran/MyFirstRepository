# MyFirstRepository
testing out

- `Landing.js`:

This component is used to map all the components that are a part of project Vento. The Header is kept as a static content across pages and each page is mapped to the Sidebar, the component specific to it and the route that the page takes on the URL.
 
- `Assetlist.js`:

[MUI datatable for react](https://github.com/gregnb/mui-datatables) is used for the creation of an assets table. 

The operations supported in this table include global search, column-wise filtering and choosing the columns to be displayed. Additional operations provided as part of the toolbar like creation of assets and uploading asset information as CSV come under CustomToolbar.

On clicking any asset on the table, all other information pertaining to that particular asset can be viewed.


 ![image](/sample/assetlist.png "assetlist")


‘On row click’ features like deletion of assets(on selecting one or more rows) and editing an asset's information(on selecting strictly one row) are available in CustomToolbarSelect.

![image](/sample/editDelete.png "editDelete")