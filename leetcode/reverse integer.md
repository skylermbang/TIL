        class Solution:
            def reverse(self, x: int) -> int:


                string_x= str(x)
                if x <0:
                    x=abs(x)
                    string_x=str(x)
                    result= int(string_x[::-1])
                    result= -1*result

                else:

                    result=int(string_x[::-1])

                if result not in range(-2**31,2**31):
                    result=0
                return result
                
                
   

* remember to have constraints parts     -2^31 <x < 2^31

 

time complexity  O(N)?
