<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128643102/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1663)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# WPF Dock Layout Manager - Create a Complex Layout of Dock Panels

This example combines the following panels into [LayoutGroups](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutGroup) to create a dock UI:

- _RootGroup_ arranges _LayoutGroup1_ and _LayoutGroup3_ horizontally.

    - _LayoutGroup1_ arranges _LayoutGroup2_ and [TabbedGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.TabbedGroup) vertically.

        - _LayoutGroup2_ arranges three [LayoutPanels](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutPanel) horizontally.

    - _LayoutGroup3_ arranges two [LayoutPanels](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutPanel) vertically.

The following image shows the created structure of dock panels:

![image](https://user-images.githubusercontent.com/12169834/173858667-34ce8555-b158-43ab-8604-67972af88ed0.png)

<!-- default file list -->
## Files to Look At

- [Window1.xaml](./CS/CreateLayoutGroups/Window1.xaml) (VB: [Window1.xaml](./VB/CreateLayoutGroups/Window1.xaml))
<!-- default file list end -->

## Documentation

- [Dock UI Items](https://docs.devexpress.com/WPF/7209/controls-and-libraries/layout-management/dock-windows/dock-items)
- [LayoutPanel](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutPanel)
- [LayoutGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutGroup)
- [TabbedGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.TabbedGroup)
- [Create a Simple Layout of Dock Panels](https://docs.devexpress.com/WPF/6654/controls-and-libraries/layout-management/dock-windows/getting-started/how-to-create-a-simple-layout-of-dock-panes)

## More Examples
- [WPF Dock Layout Manager - Create a Simple Layout of Dock Panes](https://github.com/DevExpress-Examples/how-to-create-a-simple-layout-of-dock-panes-e1600)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-docklayoutmanager-create-a-complex-dock-ui&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-docklayoutmanager-create-a-complex-dock-ui&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
