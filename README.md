# Split-items-into-pages
Adobe Indesign Script.  Splits the selected items on a page into individual indesign pages matching their pixel dimensions.

#### Installation
1. Place script in:
      <br/>Mac: '~/Applications/Adobe InDesign CC#/Scripts/Scripts Panel/Custom'
      <br/>Win: 'C:\Program Files\Adobe\Adobe InDesign CC#\Scripts\Scripts Panel\Custom'
2. Restart Indesign

#### Use
1. Find the script in the InDesign/Window/Utilities/Scripts panel.
2. Select the items on the page you want to split starting from top to bottom.
    <br/>You can select individual items or groups.
    <br/>You can select multiple items at a time, the script will generally work from top to bottom in the order selected.
3. Double click the script.
4. A new page will be created at the bottom of the document for each item or group selected at the pixel dimensions of that item.

#### Notes
Useful for quickly splitting an InDesign document into pages that can export web-ready image files.
<br/> Previous versions had a resize function for pages outside the desired pixel dimension range, commented out in this version.
<br/> Previous versions had an `UnGroup` command at the end, but that lacked the ability to work on non-grouped objects as well.  Commented out in this version.
    
