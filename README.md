<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/568838706/22.2.2%2B)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Blazor Accordion – Use the component to organize navigation in the application

You can use the Accordion component to set up navigation between pages in your application.

![Accordion - synchronize links](/accordion-url-sync.png)

This example is based on the DevExpress Blazor project template. In the _NavMenu.razor_ file, replace the `DxTreeView` component with `DxAccordion`. Populate the Accordion with items and specify the [NavigateUrl](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordionItem.NavigateUrl) property for items that correspond to pages. The Accordion can automatically select an item whose `NavigateUrl` property value matches the current page's URL. To activate this functionality, specify the [UrlMatchMode](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordion.UrlMatchMode) property on the component or item level and allow item selection on the component level ([SelectionMode](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordion.SelectionMode) property). You can also use the [AllowSelection](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordionItem.AllowSelection) property on the item level to prevent certain items from being selected. 

## Files to Review

[NavMenu.razor](/CS/NavigationAccordion/NavigationAccordion/Shared/NavMenu.razor)

## Documentation

[DxAccordion - Select Items](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxAccordion#select-items)
