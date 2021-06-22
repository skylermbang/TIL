<h1> Question </h1>

<h2> List Questions That I dont Understand   </h2>


Algorithm question : 
Q. 다음과 같이 영어로 되어 있는 문자열이 있을 때, 이 문자열에서 반복되지 않는 첫번째 문자를 반환하시오. 만약 그런 문자가 없다면 _ 를 반환하시오.
```python
"abadabac" # 반복되지 않는 문자는 d, c 가 있지만 "첫번째" 문자니까 d를 반환해주면 됩니다!
```

<hr>
백준문제 1110  다시풀기 
<hr>

what is list[-1:] ?

          def flip(some_list):
              # base case
              if len(some_list) == 0 or len(some_list) == 1:
                  return some_list

              # recursive case
              return some_list[-1:] + flip(some_list[:-1]) # i dont understand

                 #테스트
              some_list = [1, 2, 3, 4, 5, 6, 7, 8, 9]
              some_list = flip(some_list)
              print(some_list)
