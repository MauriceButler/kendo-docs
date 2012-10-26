---
title: comboBox
slug: comboBox
tags: api, java
publish: true
---

# <kendo:comboBox>
A JSP tag representing Kendo ComboBox.

## Configuration Attributes


### autoBind `boolean`

Controls whether to bind the widget to the DataSource on initialization.

#### Example
    <kendo:comboBox autoBind="autoBind">
    </kendo:comboBox>
    

### cascadeFrom `String`

Use it to set the Id of the parent DropDownList.

#### Example
    <kendo:comboBox cascadeFrom="cascadeFrom">
    </kendo:comboBox>
    

### dataTextField `String`

Sets the field of the data item that provides the text content of the list items.

#### Example
    <kendo:comboBox dataTextField="dataTextField">
    </kendo:comboBox>
    

### dataValueField `String`

Sets the field of the data item that provides the value content of the list items.

#### Example
    <kendo:comboBox dataValueField="dataValueField">
    </kendo:comboBox>
    

### delay `float`

Specifies the delay in ms after which the ComboBox will start filtering dataSource.

#### Example
    <kendo:comboBox delay="delay">
    </kendo:comboBox>
    

### enable `boolean`

Controls whether the ComboBox should be initially enabled.

#### Example
    <kendo:comboBox enable="enable">
    </kendo:comboBox>
    

### filter `String`

Defines the type of filtration. If "none" the ComboBox will not filter the items.

#### Example
    <kendo:comboBox filter="filter">
    </kendo:comboBox>
    

### height `float`

Define the height of the drop-down list in pixels.

#### Example
    <kendo:comboBox height="height">
    </kendo:comboBox>
    

### highlightFirst `boolean`

Controls whether the first item will be automatically highlighted.

#### Example
    <kendo:comboBox highlightFirst="highlightFirst">
    </kendo:comboBox>
    

### ignoreCase `String`

Defines whether the filtration should be case sensitive.

#### Example
    <kendo:comboBox ignoreCase="ignoreCase">
    </kendo:comboBox>
    

### index `float`

Defines the initial selected item.

#### Example
    <kendo:comboBox index="index">
    </kendo:comboBox>
    

### minLength `float`

Specifies the minimum characters that should be typed before the ComboBox activates

#### Example
    <kendo:comboBox minLength="minLength">
    </kendo:comboBox>
    

### placeholder `String`

A string that appears in the textbox when the combobox has no value.

#### Example
    <kendo:comboBox placeholder="placeholder">
    </kendo:comboBox>
    

### suggest `boolean`

Controls whether the ComboBox should automatically auto-type the rest of text.

#### Example
    <kendo:comboBox suggest="suggest">
    </kendo:comboBox>
    

### template `String`

Template to be used for rendering the items in the list.

#### Example
    <kendo:comboBox template="template">
    </kendo:comboBox>
    

### text `String`

Define the text of the widget, when the autoBind is set to false.

#### Example
    <kendo:comboBox text="text">
    </kendo:comboBox>
    

### value `String`

Define the value of the widget

#### Example
    <kendo:comboBox value="value">
    </kendo:comboBox>
    

## Event Attributes

### change `String`

Fires when the value has been changed.

#### Example
    <kendo:comboBox change="handle_change">
    </kendo:comboBox>
    <script>
        function handle_change(e) {
            // Code to handle the change event.
        }
    </script>

### close `String`

Fires when the drop-down list is closed

#### Example
    <kendo:comboBox close="handle_close">
    </kendo:comboBox>
    <script>
        function handle_close(e) {
            // Code to handle the close event.
        }
    </script>

### dataBound `String`

Fires when the ComboBox has received data from the data source.

#### Example
    <kendo:comboBox dataBound="handle_dataBound">
    </kendo:comboBox>
    <script>
        function handle_dataBound(e) {
            // Code to handle the dataBound event.
        }
    </script>

### open `String`

Fires when the drop-down list is opened

#### Example
    <kendo:comboBox open="handle_open">
    </kendo:comboBox>
    <script>
        function handle_open(e) {
            // Code to handle the open event.
        }
    </script>

### select `String`

Triggered when a Li element is selected.

#### Example
    <kendo:comboBox select="handle_select">
    </kendo:comboBox>
    <script>
        function handle_select(e) {
            // Code to handle the select event.
        }
    </script>


## Event Tags
 
### <kendo:comboBox-change>

Fires when the value has been changed.

#### Example
    <kendo:comboBox>
        <kendo:comboBox-change>
            <script>
                function(e) {
                    // Code to handle the Change event.
                }
            </script>
        </kendo:comboBox-change>
    </kendo:comboBox>
 
### <kendo:comboBox-close>

Fires when the drop-down list is closed

#### Example
    <kendo:comboBox>
        <kendo:comboBox-close>
            <script>
                function(e) {
                    // Code to handle the Close event.
                }
            </script>
        </kendo:comboBox-close>
    </kendo:comboBox>
 
### <kendo:comboBox-dataBound>

Fires when the ComboBox has received data from the data source.

#### Example
    <kendo:comboBox>
        <kendo:comboBox-dataBound>
            <script>
                function(e) {
                    // Code to handle the DataBound event.
                }
            </script>
        </kendo:comboBox-dataBound>
    </kendo:comboBox>
 
### <kendo:comboBox-open>

Fires when the drop-down list is opened

#### Example
    <kendo:comboBox>
        <kendo:comboBox-open>
            <script>
                function(e) {
                    // Code to handle the Open event.
                }
            </script>
        </kendo:comboBox-open>
    </kendo:comboBox>
 
### <kendo:comboBox-select>

Triggered when a Li element is selected.

#### Example
    <kendo:comboBox>
        <kendo:comboBox-select>
            <script>
                function(e) {
                    // Code to handle the Select event.
                }
            </script>
        </kendo:comboBox-select>
    </kendo:comboBox>
 

## Child JSP Tags

### [<kendo:comboBox-animation>](/api/wrappers/jsp/combobox/animation)

Animations to be used for opening/closing the popup. Setting to false will turn off the animation.

#### Example

    <kendo:comboBox>
        <kendo:comboBox-animation></kendo:comboBox-animation>
    </kendo:comboBox>
      
