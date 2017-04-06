public class Solution {
    public int[] twoSum(int[] nums, int target) {
        int i=0;
        int j=nums.length-1;
        int k=nums[i]+nums[j];
        while(true){
          k=nums[i]+nums[j];
          if(k==target){
              break;
          }
          j=j-1;
          if(i==j){
              i=i+1;
              j=nums.length-1;
          }
        }
        int[] a={i,j};
        return a;
    }
    
}
