class Solution {
    public int[][] largestLocal(int[][] grid) {
        int x = grid.length-2;
        int[][] maxLocal = new int[x][x];
        for(int i = 0; i < x; i++){
            for(int j = 0; j < x; j++){
                int max = Integer.MIN_VALUE;
                for(int r = i; r <= i+2; r++){
                    for(int s = j; s <= j+2; s++){
                        if(grid[r][s] > max) max = grid[r][s];
                    }
                }
                maxLocal[i][j] = max;
            }
        }
        return maxLocal;
    }
}
