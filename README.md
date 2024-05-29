# SDF-TopoNet
Code for Siyi Wu's master's thesis SDF-TopoNet. Contains a total of nine results from three methods run on three datasets.

<table>
  <tr>
    <th colspan="2">Method</th>
    <th>Model</th>
    <th>SDF</th>
    <th>Loss</th>
    <th>Alpha</th>
  </tr>
  <tr>
    <td colspan="2">U-net baseline</td>
    <td>U-net</td>
    <td>disable</td>
    <td>MSE</td>
    <td>1.0</td>
  </tr>
  <tr>
    <td colspan="2">Topology baseline</td>
    <td>U-net</td>
    <td>enable</td>
    <td>MSE + topo</td>
    <td>0.99</td>
  </tr>
  <tr>
    <td rowspan="2">SDF-TopoNet</td>
     <td>U-net</td>
    <td>Pre-train</td>
    <td>enable</td>
    <td>MSE</td>
    <td>1.0</td>
  </tr>
  <tr>
    <td>Fine-tune</td>
    <td>U-net + DS</td>
    <td>disable</td>
    <td>MSE + topo</td>
    <td>0.9</td>
  </tr>
</table>
