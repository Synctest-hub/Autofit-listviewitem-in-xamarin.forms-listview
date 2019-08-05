# AutoFitMode of ListView

AutoFit considers height of the item when [SfListView.Orientation](https://help.syncfusion.com/cr/cref_files/xamarin/Syncfusion.SfListView.XForms~Syncfusion.ListView.XForms.SfListView~Orientation.html) is vertical. When `SfListView.Orientation` is horizontal, it considers width of the item. The [SfListView.GridLayout](https://help.syncfusion.com/cr/cref_files/xamarin/Syncfusion.SfListView.XForms~Syncfusion.ListView.XForms.GridLayout.html) AutoFit all the items in a row and takes the maximum item height of the row and applies to all other items in the row.

```
<ContentPage xmlns:syncfusion="clr-namespace:Syncfusion.ListView.XForms;assembly=Syncfusion.SfListView.XForms">
  <syncfusion:SfListView x:Name="listView" 
                    ItemSize="200"
                    AutoFitMode="Height"
                    ItemsSource="{Binding BookInfo}" />
</ContentPage>
```
To know more about item size customization in ListView, please refer [here](https://help.syncfusion.com/xamarin/sflistview/item-size-customization).