<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* [Program.cs](./CS/Program.cs) (VB: [Program.vb](./VB/Program.vb))
* [Form1.cs](./CS/XRPivotGridEvents/Form1.cs) (VB: [Form1.vb](./VB/XRPivotGridEvents/Form1.vb))
* [Program.cs](./CS/XRPivotGridEvents/Program.cs) (VB: [Program.vb](./VB/XRPivotGridEvents/Program.vb))
* [XtraReport1.cs](./CS/XRPivotGridEvents/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/XRPivotGridEvents/XtraReport1.vb))
* [XtraReport1.cs](./CS/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/XtraReport1.vb))
<!-- default file list end -->
# How to use the XRPivotGrid control's Print* events to conditionally adjust its appearance in Print Preview


<p>This example demonstrates how to change the appearance of <a href="http://documentation.devexpress.com/#XtraReports/CustomDocument4094">XRPivotGrid</a> cells, headers and value fields based on their values (or, captions).</p><p>This can be achieved by handling the special <a href="http://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXRPivotGrid_PrintCelltopic">PrintCell</a>, <a href="http://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXRPivotGrid_PrintHeadertopic">PrintHeader</a>, and <a href="http://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXRPivotGrid_PrintFieldValuetopic">PrintFieldValue</a> events.</p><p>Note that the report's <a href="http://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXtraReport_VerticalContentSplittingtopic">VerticalContentSplitting</a> is set to <strong>Exact</strong>, to fit XRPivotGrid columns precisely to a page's width.</p>

<br/>


