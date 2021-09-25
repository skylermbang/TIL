
1.  Two Sum :
     
                 class Solution:
              def twoSum(self, nums: List[int], target: int) -> List[int]:

                  for i in range (len(nums)):
                      for j in range(i+1,len(nums)):
                          if nums[i]+nums[j]== target:
                              return[i,j]
 
 
 Obiously its the simplist and not "smart" answer.   It has o(n^2) time complexity but this is my first algorithms questions 
 and I was having trouble implementing  line6&7
I know there is way to make those loop but coudlnt do it because i forgot to use the in range- 
there is better and more effecient answer. 
