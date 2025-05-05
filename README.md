# info5100-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [INFO5100 Assignment 2 Solved](https://www.ankitcodinghub.com/product/info5100-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94977&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;INFO5100 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Create separate class(java file) for each problem

2. Test your solution with few examples in main method

3. Try to avoid writing logic in the main method, create separate method for the logic to execute

4. Create different folder for problems for each assignment

5. Try to include edge cases in your logic

Q1) Create a Shape class and two sub classes Rectangle and Square Shape :

Fields : name, color, area, perimeter

Constructors :

Shape(name, color)

Shape(name, color, perimeter, area)

Methods : printShape() Rectangle: Inherits Shape Fields : width, height

Constructors:

Rectangle(side)→If single side is given then set width and height to same value. Rectangle(width, height)

Rectangle(name, color, width, height)

Square: Inherits Shape Fields: side

Constructors: Square(side) Square(name, color, side)

<ol>
<li>1) &nbsp;Create getter and setter methods for all classes.</li>
<li>2) &nbsp;Create printShape() method in Shape class that returns desired string output.</li>
<li>3) &nbsp;Override the getArea() and getPerimeter() getter methods of Shape in Rectangle and
Square to give desired output.
</li>
</ol>
4)Use the Shape tester class to test your classes.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
public class ShapeTester {

public static void main(String[] args) {

Shape shape1 = new Shape(“Shape1”, “pink”); System.out.println(“shape1”); System.out.println(shape1.printShape());

Shape shape2 = new Shape(“Shape2”, “orange”, 20, 30);

System.out.println(“shape2”);

System.out.println(“area : ” + shape2.getArea() + ” perimeter : ” + shape2.getPerimeter()); System.out.println(shape2.printShape());

Rectangle rectangle1 = new Rectangle(2);

System.out.println(“rectangle1”);

System.out.println(“area : ” + rectangle1.getArea() + ” perimeter : ” + rectangle1.getPerimeter());

Rectangle rectangle2 = new Rectangle(“Rectangle”, “Purple”,4, 7); System.out.println(“rectangle2”);

System.out.println(“area : ” + rectangle2.getArea() + ” perimeter : ” + rectangle2.getPerimeter()); System.out.println(rectangle2.printShape());

Square square1 = new Square(3);

System.out.println(“square1”);

System.out.println(“area : ” + square1.getArea() + ” perimeter : ” + square1.getPerimeter());

Square square2 = new Square(“Square” , “black”, 7);

System.out.println(“square2”);

System.out.println(“area : ” + square2.getArea() + ” perimeter : ” + square2.getPerimeter()); System.out.println(square2.printShape());

} }

Output:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>shape1
The Shape1 has a pink color
shape2
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>area : 30 perimeter : 20
The Shape2 has a orange color
rectangle1
area : 4 perimeter : 8
rectangle2
area : 28 perimeter : 22
The Rectangle has a Purple color
square1
area : 9 perimeter : 12
square2
area : 49 perimeter : 28
The Square has a black color
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Q2) Create a Sum class with methods to get desired output. Use the below function to test the output.

public static void main(String[] args){

Sum sum = new Sum();

System.out.println(sum.add(2, 3)); //output : 5 System.out.println(sum.add(4, 9, 12));//output : 25 System.out.println(sum.add(4, 5.0));//output : 9.0 System.out.println(sum.add(15.5, 5));//output : 20.5 System.out.println(sum.add(1.0, 6.4));//output : 7.4

}

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
LeetCode :

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
1) Transpose Matrix : https://leetcode.com/problems/transpose-matrix/

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Given a 2D integer array matrix, return the transpose of matrix.

The transpose of a matrix is the matrix flipped over its main diagonal, switching the matrix’s row and

column indices.

Example 1:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Input: matrix = [[1,2,3],[4,5,6],[7,8,9]] Output: [[1,4,7],[2,5,8],[3,6,9]]

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Input: matrix = [[1,2,3],[4,5,6]] Output: [[1,4],[2,5],[3,6]]

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
• •

</div>
</div>
<div class="layoutArea">
<div class="column">
• • •

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>m == matrix.length
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>n == matrix[i].length
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>1 &lt;= m, n &lt;= 1000
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 &lt;= m * n &lt;= 105

</div>
</div>
<div class="layoutArea">
<div class="column">
-109 &lt;= matrix[i][j] &lt;= 109

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
2) Shortest Word Distance : https://leetcode.com/problems/sign-of-the-product-of-an- array/

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Given an array of strings and two different strings that already exist in the array word1 and word2, return the shortest distance between these two words in the list.

Example 1:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
wordsDict

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Input: wordsDict = [“practice”, “makes”, “perfect”, “coding”, “makes”], word1 = “coding”, word2 = “practice”

Output: 3

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Input: wordsDict = [“practice”, “makes”, “perfect”, “coding”, “makes”], word1 = “makes”, word2 = “coding”

Output: 1

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
•

•

• consists of lowercase English letters. • word1 and word2 are in wordsDict.

•

</div>
</div>
<div class="layoutArea">
<div class="column">
1 &lt;= wordsDict.length &lt;= 3 * 104

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>1 &lt;= wordsDict[i].length &lt;= 10
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>wordsDict[i]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>word1 != word2
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3) Move Zeroes : https://leetcode.com/problems/move-zeroes/

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Given an integer array nums, move all 0’s to the end of it while maintaining the relative order of the non-zero elements.

Note that you must do this in-place without making a copy of the array.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: nums = [0,1,0,3,12] Output: [1,3,12,0,0]

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: nums = [0] Output: [0]

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
<div class="layoutArea">
<div class="column">
• •

</div>
</div>
<div class="layoutArea">
<div class="column">
1 &lt;= nums.length &lt;= 104

</div>
</div>
<div class="layoutArea">
<div class="column">
-231 &lt;= nums[i] &lt;= 231 – 1

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
4) Rotate Image – https://leetcode.com/problems/rotate-image/

</div>
</div>
<div class="layoutArea">
<div class="column">
You are given an n x n 2D matrix representing an image, rotate the image by 90 degrees

</div>
</div>
<div class="layoutArea">
<div class="column">
(clockwise).

</div>
</div>
<div class="layoutArea">
<div class="column">
You have to rotate the image in-place, which means you have to modify the input 2D matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
directly. DO NOT allocate another 2D matrix and do the rotation.

</div>
</div>
<div class="layoutArea">
<div class="column">
Example 1:

</div>
</div>
<div class="layoutArea">
<div class="column">
Input: matrix = [[1,2,3],[4,5,6],[7,8,9]] Output: [[7,4,1],[8,5,2],[9,6,3]]

</div>
</div>
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
<div class="layoutArea">
<div class="column">
Input: matrix = [[5,1,9,11],[2,4,8,10],[13,3,6,7],[15,14,12,16]] Output: [[15,13,2,5],[14,3,4,1],[12,6,8,9],[16,7,10,11]]

</div>
</div>
<div class="layoutArea">
<div class="column">
Example 3:

</div>
</div>
<div class="layoutArea">
<div class="column">
Input: matrix = [[1]] Output: [[1]]

</div>
</div>
<div class="layoutArea">
<div class="column">
Example 4:

</div>
</div>
<div class="layoutArea">
<div class="column">
Input: matrix = [[1,2],[3,4]] Output: [[3,1],[4,2]]

</div>
</div>
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
• • • •

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>matrix.length == n
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>matrix[i].length == n
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 &lt;= n &lt;= 20

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>-1000 &lt;= matrix[i][j] &lt;= 1000
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Spiral Matrix – https://leetcode.com/problems/spiral-matrix/

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="section">
<div class="layoutArea">
<div class="column">
Given an

</div>
</div>
<div class="layoutArea">
<div class="column">
, return all elements of the

</div>
</div>
<div class="layoutArea">
<div class="column">
in spiral order.

</div>
</div>
<div class="layoutArea">
<div class="column">
Example 1:

</div>
</div>
<div class="layoutArea">
<div class="column">
m x n matrix matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
Input: matrix = [[1,2,3],[4,5,6],[7,8,9]] Output: [1,2,3,6,9,8,7,4,5]

</div>
</div>
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
<div class="layoutArea">
<div class="column">
Input: matrix = [[1,2,3,4],[5,6,7,8],[9,10,11,12]] Output: [1,2,3,4,8,12,11,10,9,5,6,7]

</div>
</div>
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
• • • •

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>m == matrix.length
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>n == matrix[i].length
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 &lt;= m, n &lt;= 10

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>-100 &lt;= matrix[i][j] &lt;= 100
</pre>
</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Isomorphic Strings

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
– https://leetcode.com/problems/isomorphic-strings/

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Given two strings s and t, determine if they are isomorphic.

Two strings s and t are isomorphic if the characters in s can be replaced to get t.

All occurrences of a character must be replaced with another character while preserving the order of characters. No two characters may map to the same character, but a character may map to itself.

Example 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = “egg”, t = “add” Output: true

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = “foo”, t = “bar” Output: false

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 3:

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 7">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = “paper”, t = “title” Output: true

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
•

•

• s and t consist of any valid ascii character.

</div>
</div>
<div class="layoutArea">
<div class="column">
1 &lt;= s.length &lt;= 5 * 104

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>t.length == s.length
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
7) Add Strings – https://leetcode.com/problems/add-strings/

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Given two non-negative integers, num1 and num2 represented as string, return the sum of num1 and num2 as a string.

You must solve the problem without using any built-in library for handling large integers (such as BigInteger). You must also not convert the inputs to integers directly.

Example 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: num1 = “11”, num2 = “123” Output: “134”

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: num1 = “456”, num2 = “77” Output: “533”

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 3:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: num1 = “0”, num2 = “0” Output: “0”

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
•

<ul>
<li>num1 and num2 consist of only digits.</li>
<li>num1 and num2 don’t have any leading zeros except for the zero itself.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 &lt;= num1.length, num2.length &lt;= 104

</div>
</div>
<div class="layoutArea">
<div class="column">
8) Valid Palindrome – https://leetcode.com/problems/valid-palindrome/

</div>
</div>
<div class="layoutArea">
<div class="column">
Given a string s, determine if it is a palindrome, considering only alphanumeric characters and ignoring cases.

</div>
</div>
</div>
<div class="page" title="Page 8">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = “A man, a plan, a canal: Panama”

Output: true

Explanation: “amanaplanacanalpanama” is a palindrome.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = “race a car” Output: false

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Explanation: “raceacar” is not a palindrome.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
•

• s consists only of printable ASCII characters.

</div>
</div>
<div class="layoutArea">
<div class="column">
1 &lt;= s.length &lt;= 2 * 105

</div>
</div>
<div class="layoutArea">
<div class="column">
9) Reverse words in a String – https://leetcode.com/problems/reverse-words-in-a-string/

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Given an input string s, reverse the order of the words.

A word is defined as a sequence of non-space characters. The words in s will be separated by at

least one space.

Return a string of the words in reverse order concatenated by a single space.

Note that s may contain leading or trailing spaces or multiple spaces between two words. The returned string should only have a single space separating the words. Do not include any extra spaces.

Example 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = “the sky is blue” Output: “blue is sky the”

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = ” hello world ”

Output: “world hello”

Explanation: Your reversed string should not contain leading or trailing spaces.

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 9">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 3:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = “a good example” Output: “example good a”

Explanation: You need to reduce multiple spaces between two words to a single space in the reversed string.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 4:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = ” Bob Loves Alice ”

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Output: “Alice Loves Bob”

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 5:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: s = “Alice does not even like bob” Output: “bob like even not does Alice”

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
•

<ul>
<li>s contains English letters (upper-case and lower-case), digits, and spaces ‘ ‘.</li>
<li>There is at least one word in s.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 &lt;= s.length &lt;= 104

</div>
</div>
<div class="layoutArea">
<div class="column">
10) String Compression – https://leetcode.com/problems/string-compression/

</div>
</div>
<div class="layoutArea">
<div class="column">
Given an array of characters chars, compress it using the following algorithm:

Begin with an empty string s. For each group of consecutive repeating characters in chars:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>If the group’s length is 1, append the character to s.</li>
<li>Otherwise, append the character followed by the group’s length.</li>
</ul>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
The compressed string s should not be returned separately, but instead, be stored in the input

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
character array chars. Note that group lengths that are 10 or longer will be split into multiple characters in chars.

After you are done modifying the input array, return the new length of the array.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
You must write an algorithm that uses only constant extra space.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: chars = [“a”,”a”,”b”,”b”,”c”,”c”,”c”]

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 10">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Output: Return 6, and the first 6 characters of the input array should be: [“a”,”2″,”b”,”2″,”c”,”3″]

Explanation: The groups are “aa”, “bb”, and “ccc”. This compresses to “a2b2c3”.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 2:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: chars = [“a”]

Output: Return 1, and the first character of the input array should be: [“a”]

Explanation: The only group is “a”, which remains uncompressed since it’s a single character.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 3:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: chars = [“a”,”b”,”b”,”b”,”b”,”b”,”b”,”b”,”b”,”b”,”b”,”b”,”b”] Output: Return 4, and the first 4 characters of the input array should be:

[“a”,”b”,”1″,”2″].

Explanation: The groups are “a” and “bbbbbbbbbbbb”. This compresses to “ab12”.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Example 4:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input: chars = [“a”,”a”,”a”,”b”,”b”,”a”,”a”]

Output: Return 6, and the first 6 characters of the input array should be:

<pre>["a","3","b","2","a","2"].
</pre>
Explanation: The groups are “aaa”, “bb”, and “aa”. This compresses to “a3b2a2”. Note that each group is independent even if two groups have the same character.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Constraints:

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
• •

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>1 &lt;= chars.length &lt;= 2000
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
is a lowercase English letter, uppercase English letter, digit, or symbol.

</div>
</div>
<div class="layoutArea">
<div class="column">
chars[i]

</div>
</div>
</div>
