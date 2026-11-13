class Solution {
    public int countDigits(int num) {
        int z = num, count = 0;
        while (z != 0) {
            if (num % (z % 10) == 0) count++;
            z /= 10;
        }
        return count;
    }
}
