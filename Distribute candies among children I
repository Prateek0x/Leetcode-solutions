class Solution {
public:
    // time/space: O(limit^2)/O(1)
    int distributeCandies(int n, int limit) {
        int result = 0;
        for (int i = 0; i <= limit; i++) {
            for (int j = 0; j <= limit; j++) {
                int k = n - (i + j);
                if ((0 <= k) && (k <= limit)) result++;
            }
        }
        return result;
    }
};
