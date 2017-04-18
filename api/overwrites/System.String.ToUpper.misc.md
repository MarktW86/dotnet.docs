---
uid: System.String.ToUpper
additional_notes.usage: *content
---

<p>As explained in [Best Practices for Using Strings](~/docs/standard/base-types/best-practices-strings.md), we recommend that you avoid calling string casing methods that substitute default values and instead call methods that require parameters to be explicitly specified. To convert a string to uppercase by using the casing conventions of the current culture, call the <xref href="System.String.ToUpper(System.Globalization.CultureInfo)"></xref> method overload with a value of <xref href="System.Globalization.CultureInfo.CurrentCulture"></xref> for its <code>culture</code> parameter.</p>


