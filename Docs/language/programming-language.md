# Programming Language
### Level
Programming Languages are broadly classified into two type
| High-Level | Low-Level |
|---|--|
| close to the human | close to the hardware |
| High-Level Languages are easy to learn and understand. | Low-Level Languages are challenging to learn and understand. 
| They are executed slower than lower level languages because they require a translator program.	| They execute with high speed.|
| They do not provide many facilities at the hardware level.	| They are very close to the hardware and help to write a program at the hardware level.|
| For writing programs, hardware knowledge is not required.	| For writing programs, hardware knowledge is a must.|
| The programs are easy to modify.	| Modifying programs is difficult.|
| A single statement may execute several instructions.	| The statements can be directly mapped to processor instructions.|
| BASIC, Perl, Pascal, COBOL, Ruby etc are examples of High-Level Languages.	| Machine language and Assembly language are Low-Level Languages.|

https://www.w3schools.in/difference-between-high-level-language-and-low-level-language

### 타이핑
| 강 타입 | 약 타입 |
|---|--|
| 자료형 정적 | 자료형 동적 |
| 자료형을 명시해야하기 때문에 약 타입 보다 제한적 | 자유롭게 개발가능 |
| 컴파일 단계에서 문제 확인 가능 | 실행 하기전까지 확인 불가 |
| 일반적으로 상용화하는 툴에 적합, 안전성 높음 | 타입 변경에 따른 의도가 명확하지 않을 수 있음(문자->숫자), 오류 발생률 높음 |
| C, C++, C#, Java | javascript |

### 메모리 관리
| 매니지드 | 언매니지드 |
|---|--|
| 메모리반환을 프로그래밍언어에서 자동으로 관리 | 메모리반환을 프로그래머가 직접 관리 |
| 언매니지드 언어보다 비효율적이기 성능이 떨어짐 | 메모리반환을 직접관리 하기 때문에 효율적(성능 중시) |
| 자동으로 관리를 해주기에 메모리 누수 등의 실수가 적음 | 프로그래머의 실수에 따른 누수가 발생 |
| C#, JAVA | C, C++ |

### 번역
| 컴파일러 | 인프리터 |
|---|--|
|프로그램 전체를 스캔하여 기계어로 변역|한 문장씩 번역, 빠른 개발가능|
|최적화, 플랫폼에 따른 실행파일필요(32x,64x,Mac),컴파일 과정에서 문제를 검출|실행해야 오류검출 가능|
|C, C++, Java|Python, Javascript|
|---|--|
