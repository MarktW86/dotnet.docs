---
uid: System.Math.Round(System.Double)
additional_notes.usage: *content
---

<p>Because of the loss of precision that can result from representing decimal values as floating-point numbers or performing arithmetic operations on floating-point values, in some cases the <xref href="System.Math.Round(System.Double)"></xref> method may not appear to round midpoint values to the nearest even integer. In the following example, because the floating-point value .1 has no finite binary representation, the first call to the <xref href="System.Math.Round(System.Double)"></xref> method with a value of 11.5 returns 11 instead of 12.  
  
 [!code-csharp[System.Math.Round#1](~/samples/snippets/csharp/VS_Snippets_CLR_System/system.math.round/cs/round2.cs#1)]
 [!code-vb[System.Math.Round#1](~/samples/snippets/visualbasic/VS_Snippets_CLR_System/system.math.round/vb/round2.vb#1)]</p>

