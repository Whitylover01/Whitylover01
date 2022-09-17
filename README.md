- 👋 Hi, I’m @Whitylover01
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Whitylover01/Whitylover01 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
row_num = int(input( "Input number of rows: ")) 
Number of rows= 3
Col_num = int(input( " Input number of columns: ")) 
Number of columns = 4
Multi_list = [[0 for col on range(col_num)] for row in range(row_num) ]
for row in range(row_num) : 
  for col in range(col_num) :
    Multi_list[row][col]= row*col
Print(multi_list) 
