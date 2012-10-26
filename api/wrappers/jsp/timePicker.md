---
title: timePicker
slug: timePicker
tags: api, java
publish: true
---

# <kendo:timePicker>
A JSP tag representing Kendo TimePicker.

## Configuration Attributes


### culture `String`

Specifies the culture info used by the widget.

#### Example
    <kendo:timePicker culture="culture">
    </kendo:timePicker>



### dates `Object`

Specifies a list of dates, which are shown in the time drop-down list. If not set, the DateTimePicker will auto-generate the available times.

#### Example
    <kendo:timePicker dates="dates">
    </kendo:timePicker>



### format `String`

Specifies the format, which is used to format the value of the TimePicker displayed in the input. The format also will be used to parse the input.

#### Example
    <kendo:timePicker format="format">
    </kendo:timePicker>



### interval `float`

Specifies the interval, between values in the popup list, in minutes.

#### Example
    <kendo:timePicker interval="interval">
    </kendo:timePicker>



### max `java.util.Date`

Specifies the end value in the popup list.

#### Example
    <kendo:timePicker max="max">
    </kendo:timePicker>



### min `java.util.Date`

Specifies the start value in the popup list.

#### Example
    <kendo:timePicker min="min">
    </kendo:timePicker>



### parseFormats `Object`

Specifies the formats, which are used to parse the value set with the value method or by direct input. If not set the value of the options.format will be used. Note that value of the format option is always used.

#### Example
    <kendo:timePicker parseFormats="parseFormats">
    </kendo:timePicker>



### value `java.util.Date`

Specifies the selected time.

#### Example
    <kendo:timePicker value="value">
    </kendo:timePicker>



### change `String`

Triggered when the underlying value of a TimePicker is changed.

#### Example
    <kendo:timePicker change="handle_change">
    </kendo:timePicker>
    <script>
        function handle_change(e) {
            // Code to handle the change event.
        }
    </script>



### close `String`

Fires when the time drop-down list is closed

#### Example
    <kendo:timePicker close="handle_close">
    </kendo:timePicker>
    <script>
        function handle_close(e) {
            // Code to handle the close event.
        }
    </script>



### open `String`

Fires when the time drop-down list is opened

#### Example
    <kendo:timePicker open="handle_open">
    </kendo:timePicker>
    <script>
        function handle_open(e) {
            // Code to handle the open event.
        }
    </script>



### Event Attributes


### change `String`

Triggered when the underlying value of a TimePicker is changed.

#### Example
    <kendo:timePicker change="handle_change">
    </kendo:timePicker>
    <script>
        function handle_change(e) {
            // Code to handle the change event.
        }
    </script>



### close `String`

Fires when the time drop-down list is closed

#### Example
    <kendo:timePicker close="handle_close">
    </kendo:timePicker>
    <script>
        function handle_close(e) {
            // Code to handle the close event.
        }
    </script>



### open `String`

Fires when the time drop-down list is opened

#### Example
    <kendo:timePicker open="handle_open">
    </kendo:timePicker>
    <script>
        function handle_open(e) {
            // Code to handle the open event.
        }
    </script>


## Event Tags
 

### <kendo:timePicker-change>

Triggered when the underlying value of a TimePicker is changed.

#### Example
    <kendo:timePicker>
        <kendo:timePicker-change>
            <script>
                function(e) {
                    // Code to handle the change event.
                }
            </script>
        </kendo:timePicker-change>
    </kendo:timePicker>

 

### <kendo:timePicker-close>

Fires when the time drop-down list is closed

#### Example
    <kendo:timePicker>
        <kendo:timePicker-close>
            <script>
                function(e) {
                    // Code to handle the close event.
                }
            </script>
        </kendo:timePicker-close>
    </kendo:timePicker>

 

### <kendo:timePicker-open>

Fires when the time drop-down list is opened

#### Example
    <kendo:timePicker>
        <kendo:timePicker-open>
            <script>
                function(e) {
                    // Code to handle the open event.
                }
            </script>
        </kendo:timePicker-open>
    </kendo:timePicker>

 

## Child JSP Tags

### [<kendo:timePicker-animation>](/api/wrappers/jsp/timepicker/animation)

Animations to be used for opening/closing the popup. Setting to false will turn of the animation.

#### Example

    <kendo:timePicker>
        <kendo:timePicker-animation></kendo:timePicker-animation>
    </kendo:timePicker>
    
