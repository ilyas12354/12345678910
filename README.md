# 12345678910
1 + вывод идентификаторов не пройденных тестовых примеров. Позволяет
локализовать тестовые примеры, потенциально выявившие дефект
Invoking test case 1 … Passed
Invoking test case 2 … Failed
Invoking test case 3 … Failed
<…>
Invoking test case 200 … Passed
Final stats:
180 test cases passed
20 test cases failed
200 test cases total



---
Invoking test case 2 … Failed
Expected values: Actual values:
 A = 200 A = 0
 B = 450 B = 0 
50
 Message = “Submenu 1” Message = “”
---
Invoking test case 3 … Failed
Expected values: Actual values:
 A = 0 A = 200
 B = 0 B = 300
 Message = “” Message = “Main Menu”
---
<…>
Invoking test case 200 … Passed
---
Final Stats
180 test cases passed
20 test cases failed
200 test cases total








Invoking test case 1 … Passed
 A = 0 A = 0 P
 B = 0 B = 0 P
 C = 500 C = 500 P
 D = 600 D = 600 P
 Message = “” Message = “” P
---
Invoking test case 2 … Failed
51
Expected values: Actual values:
 A = 200 A = 0 FAIL
 B = 450 B = 0 FAIL
 C = 500 C = 500 P
 D = 600 D = 600 P
 Message = “Submenu 1” Message = “” FAIL
---
Invoking test case 3 … Failed
Expected values: Actual values:
 A = 0 A = 200 FAIL
 B = 0 B = 300 FAIL
 C = 500 C = 500 P
 D = 600 D = 600 P
 Message = “” Message = “Main Menu” FAIL
---
<…>
Invoking test case 200 … Passed
 Message = “Submenu 1” Message = “Submenu 1 P
 Prompt = “>” Prompt = “>” P
---
Final Stats
180 test cases passed
20 test cases failed
200 test cases total



