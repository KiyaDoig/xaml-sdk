##Track Ball Synced Charts##
You can use the Position property and the PositionChanged event in order to sync trackballs in different charts. 
When the plot area size of the charts is the same and the ranges of the axes is the same, you can use a simple two way binding for the Position (ChartsWithSamePlotAreaSize.xaml).
If the charts have different plot area sizes or the ranges of the axes differ, you can utilize the TrackInfoUpdated event.

<keywords: barseries, databinding, mvvm, charttrackballbehavior, synctrackballtooltip, tooltip, pieseries, radpiechart, syncplotarea, keyboardnavigation>