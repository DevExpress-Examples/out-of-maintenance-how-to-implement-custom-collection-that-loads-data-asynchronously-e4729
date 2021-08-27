<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/134261181/18.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4729)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# How to implement Custom Collection that loads data asynchronously


<p><b>Note:</b> In version <b>18.1</b>, we implemented ready-to-use  <a href="https://documentation.devexpress.com/WPF/10803/Controls-and-Libraries/Data-Grid/Binding-to-Data/Binding-to-any-Data-Source-with-Virtual-Sources">Virtual Source</a> classes that allow you to populate <b>GridControl</b> on demand and, if required, support certain data operations (sorting, filtering). Now, this is a recommended approach to populating your grid on demand if  <a href="https://documentation.devexpress.com/WPF/9588/Controls-and-Libraries/Data-Grid/Binding-to-Data/Server-Mode">Server Mode</a> components are not sufficient.

<p>This examples demonstrates how you can implement a custom IList descendant that provides the capability to load data on demand.</p>


<br/>
