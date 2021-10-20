# Problem03 의미론적 오류를 지닌 프로그램을 수정하시오. 

다음 코드는 의미론적 오류를 가지고 있습니다. 
```
#include <iostream>

int main()
{   
    int lines = 7;
    
    for(int i = 0;i < lines;i++)
    {
        for(int blank = 0;blank < lines + i;blank++)
        {
            std::cout<< " ";
        }
        for(int k = 0;k <= 2*i;k++)
        {   
            if(k%2*i == i){
                if(i == 0)
                {
                    std::cout<< "*";
                }
                else{
                    std::cout<<i;
                }
            }
            else
            {
            std::cout<< "*";
            }
        }
        std::cout<<std::endl;
    }
}
```

원래 프로그래머가 의도한 결과는 다음과 같습니다. 
```
       *
      *1*
     *2*2*
    *3*3*3*
   *4*4*4*4*
  *5*5*5*5*5*
 *6*6*6*6*6*6*
 ```

 본래 프로그래머의 의도대로 프로그램이 동작하도록 코드를 수정하시오. 