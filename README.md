<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/568838706/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1128991)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Blazor Accordion – Manage navigation within your Blazor application

You can use the DevExpress Accordion component to organize/manage navigation within a Blazor-powered application.

![Accordion - synchronize links](/accordion-url-sync.png)

This example is based on the DevExpress Blazor project template. In the _NavMenu.razor_ file, replace the `DxTreeView` component with `DxAccordion`. Populate the Accordion with individual items and specify the [NavigateUrl](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordionItem.NavigateUrl) property for each item (corresponding to pages within the app). The Accordion can automatically select an item when its NavigateUrl property value matches the current page's URL. To enable this functionality, specify the [UrlMatchMode](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordion.UrlMatchMode) property on the component or item level and allow item selection on the component level ([SelectionMode](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordion.SelectionMode) property). You can also use the [AllowSelection](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordionItem.AllowSelection) property at the item level to prevent item selection.

## Files to Review

[NavMenu.razor](/CS/NavigationAccordion/NavigationAccordion/Shared/NavMenu.razor)

## Documentation

[DxAccordion - Select Items](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordion#select-items)
