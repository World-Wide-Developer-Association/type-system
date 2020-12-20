## Basic
<table>
  <thead>
    <tr>
      <th>Category</th><th>Type</th><th>Description</th><th>SQL Std. / Ext.</th><th>HTML5</th><th>PHP / Doctrine</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="5">Integer</th><td>bool</td><td>0, 1 or True, False, or Yes, No</td><td>Bit</td><td>boolean</td><td>bool</td>
    </tr>
    <tr>
      <td>tinyint</td><td>0~255</td><td>Tinyint</td><td rowspan="4">range, number</td><td rowspan="4">int / smallint, integer, bigint</td>
    </tr>
    <tr>
      <td>smallint</td><td>-2<sup>15</sup>~2<sup>15</sup></td><td>Smallint</td>
    </tr>
    <tr>
      <td>int</td><td>-2<sup>31</sup>~2<sup>31</sup></td><td>Int</td>
    </tr>
    <tr>
      <td>bigint</td><td>-2<sup>64</sup>~2<sup>64</sup></td><td>/ Bigint</td>
    </tr>
    <tr>
      <th rowspan="2">Float</th><td>float</td><td>mantissa >= 7</td><td>Real</td><td></td><td></td>
    </tr>
    <tr>
      <td>double</td><td>mantissa >= 15</td><td>Double, Float</td><td></td><td>float, double, real / float</td>
    </tr>
    <tr>
      <th>Decimal / Numeric</th><td>decimal</td><td>-10<sup>38</sup>~10<sup>38</sup></td><td>Decimal</td><td></td><td> / decimal</td>
    </tr>
    <tr>
      <th rowspan="3">Text</th><td>char</td><td>fixed length</td><td>Char</td><td></td><td></td>
    </tr>
    <tr>
      <td>varchar</td><td></td><td>Varchar</td><td>text</td><td rowspan="2">string / string, text</td>
    </tr>
    <tr>
      <td>text</td><td></td><td>Text</td><td>textarea</td>
    </tr>
    <tr>
      <th rowspan="2">Binary</th><td>binary</td><td></td><td>Binary</td><td></td><td> / binary</td>
    </tr>
    <tr>
      <td>image</td><td></td><td>Image</td><td>file</td><td> / blob</td>
    </tr>
    <tr>
      <th rowspan="3">Datetime</th><td>time</td><td></td><td>Time</td><td>time</td><td> / time</td>
    </tr>
    <tr>
      <td>date</td><td></td><td>Date</td><td>date</td><td> / date</td>
    </tr>
    <tr>
      <td>datetime</td><td></td><td>Datetime</td><td>datetime</td><td>Datetime / datetime</td>
    </tr>
  </tbody>
</table>
