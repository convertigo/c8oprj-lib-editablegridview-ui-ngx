


# lib_EditableGridView_ui_ngx

Convertigo NGX builder Project


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Library](#mobile-library)
    - [Shared Actions](#shared-actions)
        - [FullSyncAction](#fullsyncaction)
    - [Shared Components](#shared-components)
        - [agGridEditView](#aggrideditview)


## Installation

1. In your Convertigo Studio use `File->Import->Convertigo->Convertigo Project` and hit the `Next` button
2. In the dialog `Project remote URL` field, paste the text below:
   <table>
     <tr><td>Usage</td><td>Click the copy button</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_EditableGridView_ui_ngx=git@github.com:convertigo/c8oprj-lib-editablegridview-ui-ngx.git:branch=8.1.x
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_EditableGridView_ui_ngx=git@github.com:convertigo/c8oprj-lib-editablegridview-ui-ngx/archive/8.1.x.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_EditableGridView_ui_ngx__ project


## Mobile Library

Describes the mobile application global properties

### Shared Actions

#### FullSyncAction

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>action</td><td></td>
</tr>
<tr>
<td>data</td><td></td>
</tr>
<tr>
<td>database</td><td></td>
</tr>
</table>

### Shared Components

#### agGridEditView

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>accessibility</td><td>boolean: true (default) or false</td>
</tr>
<tr>
<td>addDataMode</td><td>add data with an inline 'form' or a 'modal' page, default is 'form'</td>
</tr>
<tr>
<td>ariaLabel</td><td></td>
</tr>
<tr>
<td>autoSizeColumns</td><td></td>
</tr>
<tr>
<td>class</td><td>One of the themes provided here :

https://www.ag-grid.com/javascript-grid-themes-provided/

Also be shure to add the theme in the Theme object as :

@import "../../node_modules/ag-grid-community/dist/styles/ag-theme-balham-dark/sass/ag-theme-balham-dark.scss";



</td>
</tr>
<tr>
<td>database</td><td>name of the fullsync database where data indexed by the EditableGridView design document</td>
</tr>
<tr>
<td>dataType</td><td>type of document too show, indexed by the EditableGridView design document</td>
</tr>
<tr>
<td>defaultColDef</td><td>default is {hide: false, editable: true, sortable: true, resizable: true, filter: true, checkboxSelection: false, singleClickEdit: false}</td>
</tr>
<tr>
<td>height</td><td>height is 'auto' or value in % or px</td>
</tr>
<tr>
<td>id</td><td>An Optional ID</td>
</tr>
<tr>
<td>maxBlocksInCache</td><td>How many blocks to keep in the store. Default is no limit, so every requested block is kept</td>
</tr>
<tr>
<td>overlayLoadingTemplate</td><td></td>
</tr>
<tr>
<td>overlayNoRowsTemplate</td><td></td>
</tr>
<tr>
<td>pagination</td><td>boolean: true (default) or false</td>
</tr>
<tr>
<td>paginationPageSize</td><td>integer: 10 by default</td>
</tr>
<tr>
<td>rowDeselection</td><td>boolean: true (default) or false</td>
</tr>
<tr>
<td>rowHeight</td><td>Height of the row in pixels as a string</td>
</tr>
<tr>
<td>rowModelType</td><td>Row model type</td>
</tr>
<tr>
<td>rowSelection</td><td>string: 'single' (default) or 'multiple'</td>
</tr>
<tr>
<td>suppressCellSelection</td><td></td>
</tr>
<tr>
<td>suppressRowClickSelection</td><td></td>
</tr>
<tr>
<td>width</td><td>width value in % or px</td>
</tr>
<tr>
<td>wrapperClass</td><td>Height of the row in pixels as a string</td>
</tr>
</table>

**events**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>CellClicked</td><td>Fired when a cell is clicked. Data will be the agGrid event</td>
</tr>
<tr>
<td>CellValueChanged</td><td>Fired when A Cell is edited changed. Data will be the agGrid event</td>
</tr>
<tr>
<td>GetRows</td><td>Fire when the RowModelType is 'infinite'. Excepts fromatted data into a agGridUpdateRows action</td>
</tr>
<tr>
<td>GridReady</td><td>Fired when the Grid is ready. Data will be the agGrid event</td>
</tr>
<tr>
<td>RowClicked</td><td>Fired when a row is clicked. Data will be the agGrid event</td>
</tr>
<tr>
<td>RowDataChanged</td><td>Fired when Row data changed. Data will be the agGrid event</td>
</tr>
<tr>
<td>RowDoubleClicked</td><td>Fired when A Cell is edited changed. Data will be the agGrid event</td>
</tr>
<tr>
<td>RowSelected</td><td>Fired when a row is selected. Data will be the agGrid event</td>
</tr>
<tr>
<td>SelectionChanged</td><td>Fired when selectionChange. Data will be the agGrid event</td>
</tr>
<tr>
<td>SortChanged</td><td>Fired when a a column is sorted. Data will be the agGrid event</td>
</tr>
</table>



