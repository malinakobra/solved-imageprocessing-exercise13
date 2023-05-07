Download Link: https://assignmentchef.com/product/solved-imageprocessing-exercise13
<br>
Exercise 13a. Implement the program ‘exercise_13a_minimum’ that checks whether or not the flat zone (piecewise-constant region) of a pixel (x,y) is a regional minimum.

exercise_13a_minimum exercise_13a_input_01.txt exercise_13a_input_01.pgm exercise_13 a_output_01.pgm

The input file ‘exercise_13a_input_01.txt’ is an input file with

<table>

 <tbody>

  <tr>

   <td colspan="2" width="64">4 lines</td>

   <td colspan="3" width="116">of parameters:</td>

   <td width="57"> </td>

   <td width="163"> </td>

   <td width="60"> </td>

   <td width="212"> </td>

  </tr>

  <tr>

   <td width="28">-At</td>

   <td width="36">line</td>

   <td width="27">1:</td>

   <td width="25">an</td>

   <td width="64">integer</td>

   <td width="57">number</td>

   <td width="163">‘x’ that denotes the</td>

   <td width="60">column</td>

   <td width="212">of the pixel.</td>

  </tr>

  <tr>

   <td width="28">-At</td>

   <td width="36">line</td>

   <td width="27">2:</td>

   <td width="25">an</td>

   <td width="64">integer</td>

   <td width="57">number</td>

   <td width="163">‘y’ that denotes the</td>

   <td width="60">row of</td>

   <td width="212">the pixel.</td>

  </tr>

  <tr>

   <td width="28">-At</td>

   <td width="36">line</td>

   <td width="27">3:</td>

   <td width="25">an</td>

   <td width="64">integer</td>

   <td width="57">number</td>

   <td width="163">‘connectivity’ that</td>

   <td width="60">denotes</td>

   <td width="212">the</td>

  </tr>

 </tbody>

</table>

connectivity number employed (4 or 8, corresponding to 4-connectivity or 8-connectivity, respectively).

The program should write 1 or 0 to an output file called exercise_13a_output_01.txt depending on whether or not the flat zone of pixel (x,y) is a regional minimum.

(Note: regional minimum: flat zone whose neighboring regions all have greater intensity values.)

Note: 8-connectivity can be assumed.

To check this program:

-immed_gray_inv_20051218_frgr4.pgm   (input image)

-For pixel (column=90, row=40), the result should be 1 (the flat zone is a regional minimum).

-For pixel (column=60, row=35), the result should be 0 (the flat zone is not a regional minimum).

(Note: pixel (column=0, row=0) is that at the upper-left corner.)

Exercise 13b. Similarly, implement the program ‘exercise_13a_maximum’ that checks whether or not the flat zone (piecewise-constant region) of a pixel (x,y) is a regional maximum.

exercise_13b_maximum exercise_13b_input_01.txt exercise_13b_input_01.pgm exercise_13 b_output_01.pgm

The input file ‘exercise_13b_input_01.txt’ is described in the previous exercise.

The program should write 1 or 0 to an output file called exercise_13b_output_01.txt depending on whether or not the flat zone of pixel (x,y) is a regional maximum.

(Note: regional maximum: flat zone whose neighboring regions all have lesser intensity values.)

Note: 8-connectivity can be assumed.

To check this program:

-immed_gray_inv_20051218_frgr4.pgm   (input image)

-For pixel (column=35, row=20), the result should be 1 (the flat zone is a regional maximum).

-For pixel (column=20, row=15), the result should be 0 (the flat zone is not a regional maximum).

(Note: pixel (column=0, row=0) is that at the upper-left corner.)