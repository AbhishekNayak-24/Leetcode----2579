# Leetcode----2579
Count Total Number of Colored Cells
//code in java 
class Solution {
    public long coloredCells(int n) {
        return (long) n * n + (long) (n - 1) * (n - 1);
    }
}
