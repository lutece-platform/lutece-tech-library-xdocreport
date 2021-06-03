# Library XDocReport

This library allows to use [XDocReport](https://github.com/opensagres/xdocreport) to merge XML template document created with MS Office (docx, pptx) or OpenOffice (odt), LibreOffice (odt) with a Java model to generate a new XML document.

Generation is performed by calling the `public static ByteArrayOutputStream produceDocument (InputStream inputStream, Map <String, Object> model)` method in the XDocReportService class.
Template is provided as an inputstream by your code. The library does not have any template document management service.

One may see the [wiki dedicated to the XDocReport project](https://github.com/opensagres/xdocreport/wiki) and in particular the User's Guide for more information on how to create templates document.
