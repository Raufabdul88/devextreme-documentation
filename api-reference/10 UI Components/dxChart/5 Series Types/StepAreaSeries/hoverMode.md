---
id: dxChartSeriesTypes.StepAreaSeries.hoverMode
acceptValues: 'nearestPoint' | 'includePoints' | 'excludePoints' | 'none'
type: String
default: 'nearestPoint'
---
---
##### shortDescription
Specifies series elements to be highlighted when a user points to a series.

---
When a user points to a series, it may react in one of the following ways depending on the value of the **hoverMode** option.

<table class="dx-table">
    <tr>
        <th>hoverMode</th>
        <th>Result</th>
    </tr>
    <tr>
        <td><i>"nearestPoint"</i></td>
        <td><img src="/images/ChartJS/hoverMode/series/steparea/nearestPoint.png" /></td>
    </tr>
    <tr>
        <td><i>"includePoints"</i></td>
        <td><img src="/images/ChartJS/hoverMode/series/steparea/includePoints.png" /></td>
    </tr>
    <tr>
        <td><i>"excludePoints"</i></td>
        <td><img src="/images/ChartJS/hoverMode/series/steparea/excludePoints.png" /></td>
    </tr>
    <tr>
        <td><i>"none"</i></td>
        <td><img src="/images/ChartJS/hoverMode/series/steparea/none.png" /></td>
    </tr>
</table>

[note]Points in step area series are hidden by default. To make them visible, assign **true** to the **point**.**visible** option.

#include common-ref-enum with {
    enum: "`ChartSeriesHoverMode`",
    values: "`NearestPoint`, `IncludePoints`, `ExcludePoints`, and `None`"
} Note that although this enum accepts more values, only the listed ones can be applied to a step area series.

#####See Also#####
- [hoverStyle](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/StepAreaSeries/hoverstyle/hoverStyle.md '/Documentation/ApiReference/UI_Components/dxChart/Series_Types/StepAreaSeries/hoverStyle/') - specifies the appearance of series in the hover state.
- **point**.[hoverMode](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/CommonSeries/point/hoverMode.md '/Documentation/ApiReference/UI_Components/dxChart/Series_Types/StepAreaSeries/point/#hoverMode') - specifies the hover mode of series points.