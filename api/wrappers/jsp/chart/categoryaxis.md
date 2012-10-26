---
title: chart-categoryAxis
slug: chart-categoryAxis
tags: api, java
publish: true
---

# <kendo:chart-categoryAxis>
A JSP tag representing Kendo CategoryAxis.

## Configuration Attributes


### axisCrossingValue `float`

Category index at which the first value axis crosses this axis.

#### Example
    <kendo:chart axisCrossingValue="axisCrossingValue">
    </kendo:chart>



### axisCrossingValues `Object`

Category indicies at which the value axes cross the category axis.

#### Example
    <kendo:chart axisCrossingValues="axisCrossingValues">
    </kendo:chart>



### categories `Object`

Array of category names.

#### Example
    <kendo:chart categories="categories">
    </kendo:chart>



### color `String`

Color to apply to all axis elements. Any valid CSS color string will work here, including hex and rgb.
Individual color settings for line and labels take priority.

#### Example
    <kendo:chart color="color">
    </kendo:chart>



### field `String`

The data field containing the category name.

#### Example
    <kendo:chart field="field">
    </kendo:chart>



### justified `boolean`

Positions categories and series points on major ticks. This removes the empty space before and after the series.

#### Example
    <kendo:chart justified="justified">
    </kendo:chart>



### name `String`

The unique axis name.

#### Example
    <kendo:chart name="name">
    </kendo:chart>



### plotBands `Object`

The plot bands of category axis.
The plot band fields:

#### Example
    <kendo:chart plotBands="plotBands">
    </kendo:chart>



### reverse `boolean`

Reverses the axis direction -
categories are listed from right to left and from top to bottom.

#### Example
    <kendo:chart reverse="reverse">
    </kendo:chart>



### type `String`

The axis type.

#### Example
    <kendo:chart type="type">
    </kendo:chart>



### autoBaseUnitSteps `Object`

Specifies the discrete

#### Example
    <kendo:chart autoBaseUnitSteps="autoBaseUnitSteps">
    </kendo:chart>



### baseUnit `String`

The base time interval for the axis.
The default baseUnit is determined automatically from the minimum difference
between subsequent categories. Available options:

#### Example
    <kendo:chart baseUnit="baseUnit">
    </kendo:chart>



### baseUnitStep `Object`

Sets the step (interval) between categories in base units.
Specifiying "auto" will set the step to such value that the total number of categories does not exceed

#### Example
    <kendo:chart baseUnitStep="baseUnitStep">
    </kendo:chart>



### max `java.util.Date`

The last date displayed on the axis.
By default, the minimum date is the same as the last category.
This is often used in combination with the

#### Example
    <kendo:chart max="max">
    </kendo:chart>



### min `java.util.Date`

The first date displayed on the axis.
By default, the minimum date is the same as the first category.
This is often used in combination with the

#### Example
    <kendo:chart min="min">
    </kendo:chart>



### roundToBaseUnit `boolean`

By default, the first and last dates will be rounded off to the nearest base unit.
Specifying

#### Example
    <kendo:chart roundToBaseUnit="roundToBaseUnit">
    </kendo:chart>



### weekStartDay `float`

Specifies the week start day when

#### Example
    <kendo:chart weekStartDay="weekStartDay">
    </kendo:chart>



### maxDateGroups `float`

Specifies the maximum number of groups (categories) to produce when
either

#### Example
    <kendo:chart maxDateGroups="maxDateGroups">
    </kendo:chart>



### visible `boolean`

The visibility of the axis.

#### Example
    <kendo:chart visible="visible">
    </kendo:chart>



### Event Attributes

## Event Tags
       

## Child JSP Tags

### [<kendo:chart-categoryAxis-labels>](/api/wrappers/jsp/chart/categoryaxis-labels)

Configures the axis labels.

#### Example

    <kendo:chart-categoryAxis>
        <kendo:chart-categoryAxis-labels></kendo:chart-categoryAxis-labels>
    </kendo:chart-categoryAxis>
 
### [<kendo:chart-categoryAxis-line>](/api/wrappers/jsp/chart/categoryaxis-line)

Configures the axis line. This will also effect major and minor ticks, but not gridlines.

#### Example

    <kendo:chart-categoryAxis>
        <kendo:chart-categoryAxis-line></kendo:chart-categoryAxis-line>
    </kendo:chart-categoryAxis>
 
### [<kendo:chart-categoryAxis-majorGridLines>](/api/wrappers/jsp/chart/categoryaxis-majorgridlines)

Configures the major grid lines. These are the lines that are an extension of the major ticks through the
body of the chart.

#### Example

    <kendo:chart-categoryAxis>
        <kendo:chart-categoryAxis-majorGridLines></kendo:chart-categoryAxis-majorGridLines>
    </kendo:chart-categoryAxis>
 
### [<kendo:chart-categoryAxis-majorTicks>](/api/wrappers/jsp/chart/categoryaxis-majorticks)

The major ticks of the axis.

#### Example

    <kendo:chart-categoryAxis>
        <kendo:chart-categoryAxis-majorTicks></kendo:chart-categoryAxis-majorTicks>
    </kendo:chart-categoryAxis>
 
### [<kendo:chart-categoryAxis-minorGridLines>](/api/wrappers/jsp/chart/categoryaxis-minorgridlines)

Configures the minor grid lines.  These are the lines that are an extension of the minor ticks through
the body of the chart.

#### Example

    <kendo:chart-categoryAxis>
        <kendo:chart-categoryAxis-minorGridLines></kendo:chart-categoryAxis-minorGridLines>
    </kendo:chart-categoryAxis>
 
### [<kendo:chart-categoryAxis-minorTicks>](/api/wrappers/jsp/chart/categoryaxis-minorticks)

The minor ticks of the axis.

#### Example

    <kendo:chart-categoryAxis>
        <kendo:chart-categoryAxis-minorTicks></kendo:chart-categoryAxis-minorTicks>
    </kendo:chart-categoryAxis>
 
### [<kendo:chart-categoryAxis-title>](/api/wrappers/jsp/chart/categoryaxis-title)

The title of the category axis.

#### Example

    <kendo:chart-categoryAxis>
        <kendo:chart-categoryAxis-title></kendo:chart-categoryAxis-title>
    </kendo:chart-categoryAxis>
 
