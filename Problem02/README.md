# Problem02
다음 코드는 여러 개의 문법 오류를 가지고 있습니다. 

```
#include <iostream>

int main()
{
    /////////////////////////////////////////////
    /// 문제 영역
    int results[2] = {0, 0};
    int array1[2] = {1, 2}
    int array2[3] = {4, 3};
    
    for(int i = 0; i < 2; i++)
    {
        for(int j = 0; j < 2; j++)
        {
            results[i] += array1[i] * array2[j];    
        }
        
        cout << result[i] << endl;
    }
    /////////////////////////////////////////////
    
    return 0;
}
```
