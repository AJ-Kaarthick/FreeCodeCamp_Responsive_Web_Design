📊 Workshop 16: Exams Table

This project is a structured data matrix built to master semantic data organization, tabular layouts, and column spanning configurations in HTML5.
📝 Project Description

The Calculus Exams Table focuses on transforming raw statistical records into a clean, accessible tabular dashboard. It practices proper data architecture by separating structural layout boundaries into distinct header, body, and summary footer segments, while mapping matching structural identifiers to maximize clarity for screen readers and modern browsers.
🧠 Core Technical Takeaways

    Tabular Landmark Scoping: Implemented explicit tabular containment sections using <thead> for metadata identifiers, <tbody> for main record entries, and <tfoot> for data summary evaluations.

    Column Spanning Layouts: Mastered horizontal footprint adjustments by applying the colspan="2" attribute to a single cell, allowing data text to bridge across multiple structural boundaries cleanly.

    Accessible Matrix Context: Incorporated the structural <caption> element to provide a clear, descriptive title attached directly to the table container, enhancing semantic markup visibility.

🛠️ Code Snippet Spotlight

Here is how the summary footer elements were condensed and formatted using column alignment attributes:

<tfoot>
  <tr>
    <td colspan="2">Average Grade</td>
    <td>78.8</td>
  </tr>
</tfoot>