---
title: grid-column
slug: jsp-grid-column
tags: api, java
publish: true
---

# \<kendo:grid-column\>
A JSP tag representing Kendo Column.

#### Example
    <kendo:grid-columns>
        <kendo:grid-column></kendo:grid-column>
    </kendo:grid-columns>


## Configuration Attributes


### command `String`

Definition of command column. The supported built-in commands are: "create", "cancel", "save", "destroy".

#### Example
    <kendo:grid command="command">
    </kendo:grid>



### editor `String`

Provides a way to specify custom editor for this column.

#### Example
    <kendo:grid editor="handle_editor">
    </kendo:grid>
    <script>
        function handle_editor(e) {
            // Code to handle the editor event.
        }
    </script>



### encoded `boolean`

Specified whether the column content is escaped. Disable encoding if the data contains HTML markup.

#### Example
    <kendo:grid encoded="encoded">
    </kendo:grid>



### field `String`

The field from the datasource that will be displayed in the column.

#### Example
    <kendo:grid field="field">
    </kendo:grid>



### filterable `boolean`

Specifies whether given column is filterable.

#### Example
    <kendo:grid filterable="filterable">
    </kendo:grid>



### format `String`

The format that will be applied on the column cells.

#### Example
    <kendo:grid format="format">
    </kendo:grid>



### sortable `boolean`

Specifies whether given column is sortable. Related tag: [\<kendo:grid-sortable\>](#kendo-grid-sortable). 

#### Example
    <kendo:grid sortable="sortable">
    </kendo:grid>



### template `String`

The template for column's cells.

#### Example
    <kendo:grid template="template">
    </kendo:grid>



### aggregates `Object`

The aggregates to be used when grouping is applied

#### Example
    <kendo:grid aggregates="aggregates">
    </kendo:grid>



### groupHeaderTemplate `String`

The template for group header item.

#### Example
    <kendo:grid groupHeaderTemplate="groupHeaderTemplate">
    </kendo:grid>



### groupFooterTemplate `String`

The template for column's cell in group footer item.

#### Example
    <kendo:grid groupFooterTemplate="groupFooterTemplate">
    </kendo:grid>



### footerTemplate `String`

The template for column's cell in footer item.

#### Example
    <kendo:grid footerTemplate="footerTemplate">
    </kendo:grid>



### headerTemplate `String`

The template for column's cell in header item.

#### Example
    <kendo:grid headerTemplate="headerTemplate">
    </kendo:grid>



### title `String`

The text that will be displayed in the column header.

#### Example
    <kendo:grid title="title">
    </kendo:grid>



### width `String`

The width of the column.

#### Example
    <kendo:grid width="width">
    </kendo:grid>



## Child JSP Tags

### [\<kendo:grid-column-command\>](/api/wrappers/jsp/grid/column-command)

Definition of command column. The supported built-in commands are: "create", "cancel", "save", "destroy".

#### Example

    <kendo:grid-column>
        <kendo:grid-column-command></kendo:grid-column-command>
    </kendo:grid-column>
  
