# Pie Chart props

| Prop                 | Type           | Description                                                                      | Default value |
| -------------------- | -------------- | -------------------------------------------------------------------------------- | ------------- |
| data                 | Array of items | An item object represents a section in the Pie chart. Descibed in the next table | \_            |
| radius               | number         | Radius of the Pie chart                                                          | 120           |
| isThreeD             | Boolean        | If set to true, it rotates and translates the chart to give it a 3D effect       | false         |
| shadow               | Boolean        | Shadow to the Pie chart, when set to true, it enhances the 3D effect             | false         |
| shadowColor          | ColorValue     | Color of the shadow                                                              | lightgray     |
| shadowWidth          | number         | Width of the shadow                                                              | radius\*4/3   |
| strokeWidth          | number         | Stroke (line) width for the Pie chart and its section                            | 0             |
| strokeColor          | ColorValue     | Stroke (line) color                                                              | gray          |
| backgroundColor      | ColorValue     | Background color of the container that contains the Pie chart                    | white         |
| showText             | Boolean        | When set to true, displays text on the Pie sections                              | false         |
| textColor            | ColorValue     | Color of the label texts                                                         | random colors |
| textSize             | number         | Size of the label texts (max allowed: radius / 5)                                | 16            |
| showTextBackground   | Boolean        | When set to true, displays background for text on the Pie sections               | false         |
| textBackgroundColor  | ColorValue     | Background color for the label texts                                             | white         |
| textBackgroundRadius | number         | Radius for the background of the text labels                                     | textSize      |
| showValuesAsLabels   | Boolean        | When set to true, the values of the Pie sections are displayed as labels         | false         |

### Item description

| Prop                 | Type       | Description                                                            |
| -------------------- | ---------- | ---------------------------------------------------------------------- |
| value                | number     | Value of the item, representing a section of the Pie chart             |
| shiftX               | number     | Translates (shifts) the particular section horizontally by given value |
| shiftY               | number     | Translates (shifts) the particular section vertically by given value   |
| color                | ColorValue | Color (background color) of the section                                |
| text                 | string     | Label text for the sections                                            |
| textColor            | ColorValue | Color of the text (label) inside the section                           |
| textSize             | number     | Size of the text (label) inside the section                            |
| textBackgroundColor  | ColorValue | Background color for the label text                                    |
| textBackgroundRadius | number     | Radius for the background of the text label                            |

### Donut chart related props

| Prop                   | Type       | Description                                                   | Default value                        |
| ---------------------- | ---------- | ------------------------------------------------------------- | ------------------------------------ |
| donut                  | Boolean    | When set to true, renders a Donut chart (makes an inner ring) | false                                |
| innerRadius            | number     | Radius of the inner ring                                      | radius/2                             |
| innerCircleColor       | ColorValue | Color of the inner ring                                       | white                                |
| innerCircleBorderWidth | number     | Stroke (border) width of the inner ring                       | props.innerCircleBorderColor ? 5 : 0 |
| innerCircleBorderColor | ColorValue | Stroke (border) color of the inner ring                       | gray                                 |
| shiftInnerCenterX      | number     | Shifts the inner ring horizontally to enhance the 3D effect   | 0                                    |
| shiftInnerCenterY      | number     | Shifts the inner ring vertically to enhance the 3D effect     | 0                                    |