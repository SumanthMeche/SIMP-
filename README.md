Coded a 2D implementation of the Solid Isotropic Material with Penalization (SIMP) method as part of my course work, originally developed by Prof. Ole Sigmund.
It includes filtering and penalization, with adjustable parameters located in the 'p case' dictionary.
The code is set up to print results at every 5th iteration, allowing for periodic monitoring of the optimization process.

Local node numbering starts at left bottom corner of a quad element and goes in a anti clockwise fashion
Global node numbering is column wise starting at left corner first from bottom to top.

In the local node numbering system (used only quadrilateral element), numbering starts at the bottom left corner and proceeds in an anti-clockwise direction.
This means that the bottom left node is  0,1 (for x, y), the bottom right as 2,3, the top right as 4,5, and the top left as 6,7.

Global node numbering follows a column-wise pattern, starting from the leftmost column of the mesh. Within each column,
numbering begins at the bottom and moves to the top. After reaching the top node of a column, numbering continues at the bottom node of the next column to the right.

*** Code was written under the guidance of Prof. Tian Chen, who established the thematic framework.
*** And I was responsible for the detailed implementation and development of the code.
