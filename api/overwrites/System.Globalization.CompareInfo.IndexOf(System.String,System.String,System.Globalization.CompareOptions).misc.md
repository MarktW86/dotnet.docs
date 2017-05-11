---
uid: System.Globalization.CompareInfo.IndexOf(System.String,System.String,System.Globalization.CompareOptions)
additional_notes.usage: *content
---

<p>Character sets include ignorable characters, which are characters that are not considered when performing a linguistic or culture-sensitive sort. In a culture-sensitive search (that is, if <code>options</code> is not <xref href="System.Globalization.CompareOptions.Ordinal"></xref> or <xref href="System.Globalization.CompareOptions.OrdinalIgnoreCase"></xref>), if <code>value</code> contains an ignorable character, the result is equivalent to searching with that character removed. If <code>value</code> consists only of one or more ignorable characters, the <xref href="System.Globalization.CompareInfo.IndexOf(System.String,System.String,System.Globalization.CompareOptions)"></xref> method always returns 0 (zero) to indicate that the match is found at the beginning of <code>source</code>. In the following example, the <xref href="System.Globalization.CompareInfo.IndexOf(System.String,System.String,System.Globalization.CompareOptions)"></xref> method is used to find three substrings (a soft hyphen (U+00AD), a soft hyphen followed by "n", and a soft hyphen followed by "m") in two strings. Only one of the strings contains a soft hyphen. Because the soft hyphen is an ignorable character, a culture-sensitive search returns the same value that it would return if the soft hyphen were not included in the search string. An ordinal search, however, successfully finds the soft hyphen in one string and reports that it is absent from the second string.  
  
 [!code-csharp[System.Globalization.CompareInfo.IndexOf#6](~/samples/snippets/csharp/VS_Snippets_CLR_System/system.Globalization.CompareInfo.IndexOf/CS/ignorable5.cs#6)]
 [!code-vb[System.Globalization.CompareInfo.IndexOf#6](~/samples/snippets/visualbasic/VS_Snippets_CLR_System/system.Globalization.CompareInfo.IndexOf/VB/ignorable5.vb#6)]</p>

