---
summary: Reads XML schema and data into the <xref href="System.Data.DataTable"></xref>.
remarks: "The <xref:System.Data.DataTable.ReadXml%2A> method provides a way to read either data only, or both data and schema into a <xref:System.Data.DataTable> from an XML document, whereas the <xref:System.Data.DataTable.ReadXmlSchema%2A> method reads only the schema. To read both data and schema, use one of the `ReadXML` overloads that include the `XmlReadMode` parameter, and set its value to `ReadSchema`.  \n  \n Note that the same is true for the <xref:System.Data.DataTable.WriteXml%2A> and <xref:System.Data.DataTable.WriteXmlSchema%2A> methods, respectively. To write XML data, or both schema and data from the `DataTable`, use the `WriteXml` method. To write just the schema, use the `WriteXmlSchema` method.  \n  \n> [!NOTE]\n>  An <xref:System.InvalidOperationException> will be thrown if a column type in the `DataRow` being read from or written to implements <xref:System.Dynamic.IDynamicMetaObjectProvider> and does not implement <xref:System.Xml.Serialization.IXmlSerializable>."
uid: System.Data.DataTable.ReadXml*
---