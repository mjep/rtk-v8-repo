Extention of Minimal Reproduction of https://github.com/mui/mui-x/issues/17503

This repo mimics the basic structure of our project hosted through firebase 
with the latest versions of @mui/material, @mui/x-data-grid-pro and parcel. The react version is 18.3.1.

Steps to reproduce:

1. Clone repo
2. `npm install`
3. Set up firebase hosting
4. `firebase init`
5. Choose hosting
6. Choose a project
7. Choose default options
8. `npm build`
9. `firebase serve`
10. View site and see error in console:

Uncaught Error: MUI X: Could not find the Data Grid context. It looks like you rendered your component outside of a DataGrid, DataGridPro or DataGridPremium parent component. This can also happen if you are bundling multiple versions of the Data Grid.
    useGridApiContext useGridApiContext.js:13
    GridPanel GridPanel.js:50
    React 11
    workLoop scheduler.development.js:266
    flushWork scheduler.development.js:239
    performWorkUntilDeadline scheduler.development.js:533
 useGridApiContext.js:13:10
Uncaught Error: MUI X: Could not find the Data Grid private context. It looks like you rendered your component outside of a DataGrid, DataGridPro or DataGridPremium parent component. This can also happen if you are bundling multiple versions of the Data Grid.
    useGridPrivateApiContext useGridPrivateApiContext.js:15
    useGridAriaAttributes useGridAriaAttributes.js:16
    useGridAriaAttributes useGridAriaAttributes.js:5
    GridMainContainer GridMainContainer.js:39
    React 11
    workLoop scheduler.development.js:266
    flushWork scheduler.development.js:239
    performWorkUntilDeadline scheduler.development.js:533
 useGridPrivateApiContext.js:15:10
Uncaught Error: MUI X: Could not find the Data Grid context. It looks like you rendered your component outside of a DataGrid, DataGridPro or DataGridPremium parent component. This can also happen if you are bundling multiple versions of the Data Grid.
    useGridApiContext useGridApiContext.js:13
    GridFooter GridFooter.js:23
    React 11
    workLoop scheduler.development.js:266
    flushWork scheduler.development.js:239
    performWorkUntilDeadline scheduler.development.js:533
 useGridApiContext.js:13:10
Uncaught Error: MUI X: Could not find the Data Grid context. It looks like you rendered your component outside of a DataGrid, DataGridPro or DataGridPremium parent component. This can also happen if you are bundling multiple versions of the Data Grid.
    useGridApiContext useGridApiContext.js:13
    GridPanel GridPanel.js:50
    React 12
    workLoop scheduler.development.js:266
    flushWork scheduler.development.js:239
    performWorkUntilDeadline scheduler.development.js:533
 useGridApiContext.js:13:10
Uncaught Error: MUI X: Could not find the Data Grid private context. It looks like you rendered your component outside of a DataGrid, DataGridPro or DataGridPremium parent component. This can also happen if you are bundling multiple versions of the Data Grid.
    useGridPrivateApiContext useGridPrivateApiContext.js:15
    useGridAriaAttributes useGridAriaAttributes.js:16
    useGridAriaAttributes useGridAriaAttributes.js:5
    GridMainContainer GridMainContainer.js:39
    React 12
    workLoop scheduler.development.js:266
    flushWork scheduler.development.js:239
    performWorkUntilDeadline scheduler.development.js:533
 useGridPrivateApiContext.js:15:10
Uncaught Error: MUI X: Could not find the Data Grid context. It looks like you rendered your component outside of a DataGrid, DataGridPro or DataGridPremium parent component. This can also happen if you are bundling multiple versions of the Data Grid.
    useGridApiContext useGridApiContext.js:13
    GridFooter GridFooter.js:23
    React 12
    workLoop scheduler.development.js:266
    flushWork scheduler.development.js:239
    performWorkUntilDeadline scheduler.development.js:533







