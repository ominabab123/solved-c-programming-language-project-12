Download Link: https://assignmentchef.com/product/solved-c-programming-language-project-12
<br>
In this project you have to sort all the people given in “disordered_people.txt”. You will get the sort column from the user and write the ordered people in “orderedFile.txt”.

Standart sort is as shown:

<table width="620">

 <tbody>

  <tr>

   <td width="102">ID</td>

   <td width="94">NAME</td>

   <td width="94">SIR NAME</td>

   <td width="329">MAIL</td>

  </tr>

  <tr>

   <td width="102">4564765…..</td>

   <td width="94">Andria</td>

   <td width="94">MALLE</td>

   <td width="329"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="e3828180a3848e828a8fcd808c8e">[email protected]</a></td>

  </tr>

 </tbody>

</table>

The row selected by the user will be placed on the first column and the order will be made according to it. Sample:

<table width="620">

 <tbody>

  <tr>

   <td width="291">Give a Sort Metric (I = ID                N= NAME</td>

   <td width="142">S= SIR NAME</td>

   <td width="188">M=MAIL) : M</td>

  </tr>

  <tr>

   <td width="291">File output file will be as shown:MAIL                                     ID                            NAME</td>

   <td width="142">SIR NAME</td>

   <td width="188"> </td>

  </tr>

  <tr>

   <td width="291"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="b7d6d5d4f7d0dad6dedb99d4d8da">[email protected]</a>                 4564765               Andria…..</td>

   <td width="142">MALLE</td>

   <td width="188"> </td>

  </tr>

  <tr>

   <td width="291">Give a Sort Metric (I = ID                N= NAME</td>

   <td width="142">S= SIR NAME</td>

   <td width="188">M=MAIL) : N</td>

  </tr>

  <tr>

   <td width="291">File output file will be as shown:NAME                    ID                          SIR NAME</td>

   <td width="142">MAIL</td>

   <td width="188"> </td>

  </tr>

  <tr>

   <td width="291">Andria                    4564765             MALLE……</td>

   <td width="142"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="6302010023040e020a0f4d000c0e">[email protected]</a></td>

   <td width="188"> </td>

  </tr>

 </tbody>

</table>

The order of ascii table will be used in the sorting. Detailed in the next page.

Rules:

<ul>

 <li>Console inputs must be accept upper case charcter “N,M,İ,S”. Can be accept lower case character “n,m,i,s”</li>

 <li>Output file name: txt</li>

 <li>Input file name is: txt</li>

</ul>

Sorting Example :

Given char arrays: Aa, aaa, ve Aaa, bb, a, c, a a, 112, 45 Charcter on asci table :

<table width="604">

 <tbody>

  <tr>

   <td width="302">Character</td>

   <td width="302">Ascii (Decimal)</td>

  </tr>

  <tr>

   <td width="302">A</td>

   <td width="302">65</td>

  </tr>

  <tr>

   <td width="302">a</td>

   <td width="302">97</td>

  </tr>

  <tr>

   <td width="302">b</td>

   <td width="302">98</td>

  </tr>

  <tr>

   <td width="302">SPACE “ ”</td>

   <td width="302">32</td>

  </tr>

  <tr>

   <td width="302">c</td>

   <td width="302">99</td>

  </tr>

  <tr>

   <td width="302">1</td>

   <td width="302">49</td>

  </tr>

  <tr>

   <td width="302">2</td>

   <td width="302">50</td>

  </tr>

  <tr>

   <td width="302">4</td>

   <td width="302">52</td>

  </tr>

  <tr>

   <td width="302">5</td>

   <td width="302">53</td>

  </tr>

 </tbody>

</table>

Unordered char arrays:

<table width="604">

 <tbody>

  <tr>

   <td width="302">Sample char array</td>

   <td width="302">As Asci Number</td>

  </tr>

  <tr>

   <td width="302">Aa</td>

   <td width="302">65 ,97</td>

  </tr>

  <tr>

   <td width="302">aaa</td>

   <td width="302">97, 97, 97</td>

  </tr>

  <tr>

   <td width="302">Aaa</td>

   <td width="302">65 ,97</td>

  </tr>

  <tr>

   <td width="302">bb</td>

   <td width="302">98, 98</td>

  </tr>

  <tr>

   <td width="302">a</td>

   <td width="302">97</td>

  </tr>

  <tr>

   <td width="302">c</td>

   <td width="302">99</td>

  </tr>

  <tr>

   <td width="302">a a</td>

   <td width="302">97, 32, 97</td>

  </tr>

  <tr>

   <td width="302">112</td>

   <td width="302">49, 49, 50</td>

  </tr>

  <tr>

   <td width="302">45</td>

   <td width="302">52, 53</td>

  </tr>

 </tbody>

</table>

Ordered char arrays:

<table width="604">

 <tbody>

  <tr>

   <td width="302">Sample Char array</td>

   <td width="302">As Asci Number</td>

  </tr>

  <tr>

   <td width="302">112</td>

   <td width="302">49, 49, 50</td>

  </tr>

  <tr>

   <td width="302">45</td>

   <td width="302">52, 53</td>

  </tr>

  <tr>

   <td width="302">Aa</td>

   <td width="302">65 ,97</td>

  </tr>

  <tr>

   <td width="302">Aaa</td>

   <td width="302">65 ,97, 97</td>

  </tr>

  <tr>

   <td width="302">a</td>

   <td width="302">97</td>

  </tr>

  <tr>

   <td width="302">a a</td>

   <td width="302">97, 32, 97</td>

  </tr>

  <tr>

   <td width="302">aaa</td>

   <td width="302">97, 97, 97</td>

  </tr>

  <tr>

   <td width="302">bb</td>

   <td width="302">98, 98</td>

  </tr>

  <tr>

   <td width="302">c</td>

   <td width="302">99</td>

  </tr>

 </tbody>

</table>

<strong>Good Luck! </strong>