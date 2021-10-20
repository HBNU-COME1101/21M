# Problem05 고장난 타자기
본 문제는 고장난 타자기를 만드는 프로그램입니다. 고장난 타자기는 알파벳으로 문자열을 입력하였을 시에 모음을 출력하지 않고 자음만 출력하는 프로그램입니다. 즉, abcdef를 입력하였다면 bcdf만 출력합니다. 
 * 입력되는 문자열은 100글자를 넘길 수 없습니다. 
 * 입력되는 문자열은 영어만 입력됩니다. 
 * 다양한 문자열 관련 함수를 사용할 수 있습니다. 

다음 코드 구조를 확인하길 바랍니다. 
```
#include <iostream>
#include <cstring>
#include <stdlib.h>

int main(int argc, char** argv)
{ 
	char buff[1000];
    std::cout << "Enter a string " << std::endl;
    std::cout << ">>";










    return 0;
}
```

힌트) 
* strlen 함수를 사용하면 문자열의 길이를 알 수 있습니다. 
* 영문에서 모음은 aeiou입니다.