class Solution {
public:
    vector<int> pivotArray(vector<int>& nums, int pivot) {

        if(nums.size() == 1) return nums;

        vector<int> result;
        int count = 0;
        for(int i=0; i<nums.size(); i++) {
            if(nums[i] < pivot) {
                result.push_back(nums[i]);
            }

            if(nums[i] == pivot) {
                count++;
            }
        }

        for(int i=0; i<count;i++) {
            result.push_back(pivot);
        }    

        for(int i=0; i<nums.size(); i++) {
            if(nums[i] > pivot) {
                result.push_back(nums[i]);
            }
        }

        return result;

    }
};
