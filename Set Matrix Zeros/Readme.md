## QuestionLink => https://leetcode.com/problems/set-matrix-zeroes/


Given an ``m x n ``integer matrix matrix, if an element is `0`, set its entire row and column to` 0'`s.

You must do it in place.

![mat1](https://github.com/abhishekbhonde/ReviseWithArsh-CrackYourPlacement/assets/113115756/b82a33b5-708a-4491-a454-a0925308dfcb)





``
Input: matrix = [[1,1,1],[1,0,1],[1,1,1]] 
Output: [[1,0,1],[0,0,0],[1,0,1]]
``





![mat2](https://github.com/abhishekbhonde/ReviseWithArsh-CrackYourPlacement/assets/113115756/9c44470c-497f-48b3-bd5d-2d4b3dc73578)


`
Input: matrix = [[0,1,2,0],[3,4,5,2],[1,3,1,5]]
Output: [[0,0,0,0],[0,4,5,0],[0,3,1,0]]
`


### Constraints:
`
m == matrix.length
n == matrix[0].length
1 <= m, n <= 200
-231 <= matrix[i][j] <= 231 - 1
 `

### Follow up:
`
A straightforward solution using O(mn) space is probably a bad idea.
A simple improvement uses O(m + n) space, but still not the best solution.
Could you devise a constant space solution?
`
