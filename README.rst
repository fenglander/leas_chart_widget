=============
Document Page
=============


This Module Enables Displaying Data Charts Through Widget.

**Example**

.. contents::
   :local:

XML
============
.. code-block:: XML
    widget="leas_echarts" options="{'dark': 1}"

    widget="leas_stackedHBar" options="{'width': 240, 'height': 150, 'show_catg': true}"


dark: To specify whether it's dark mode.

height: Set Chart Height, Unit: px

width: Set Chart Width, Unit: px

Recognizable Field Data
=============

leas_stackedHBar

.. code-block:: json
    [
        {
            "category": "Punching",
            "Available Quantity": 12.0,
            "In-Process Quantity": 0.0,
            "Completed Quantity": 0.0
        },
        {
            "category": "Sheet Metal",
            "Available Quantity": 0.0,
            "In-Process Quantity": 0.0,
            "Completed Quantity": 0.0
        },
        {
            "category": "Cutting Sheet",
            "Available Quantity": 0.0,
            "In-Process Quantity": 0.0,
            "Completed Quantity": 0.0
        },
    ]



leas_echarts:

This widget will directly hand over the JSON to ECharts for processing, so you just need to generate JSON that conforms to the ECharts format. For details, you can refer to https://echarts.apache.org/examples/.


Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/fenglander/leas_chart_widget/issues>`_.
If you encounter an issue, please check here to see if your problem has already been reported.
If you are the first to discover the issue, please help us resolve it by providing detailed information.


Other
=======


Contributors & Maintainers
~~~~~~~~~~~

* Fung <fung24081@gmail.com>