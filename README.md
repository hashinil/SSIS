# SSIS

1. Installation
>- SQL Server developer 2022
>- SQL Server Management Studio
>- Visual Studio 2022
>- SSIS in Visual Studio 2022

2. Exploring SSMS ans SSIS on VS

3. Creating Simple Data Extraction and Load [Output](#3)
>- Create new Package/ Project
>- Extract data from table
>- Load restult to table

  >  - Create connection to DB
  >  - Add OLE DB Source Task
  >  - Add OLE DB Destination
  >  - Add Data Viewer

4. Data transformation
>- 1. Explicit convertion 
>- 2. Data conversion [Output](#4_2)
>- 3. Derived Column [Output](#4_3)
>- 4. Aggregation [Output](#4_4)
>- 5. Multi-cast [Output](#4_5)
>- 6. Conditional Split [Output](#4_6)
>- 7. Sampling - Row sampling/ Precentage sampling [Output](#4_7)
>- 8. Sort [Output](#4_8)
>- 9. Union All [Output](#4_9)
>- 10. Merging [Output](#4_10)

5. Error handling [Output](#5)
>- Ignore faliure
>- redirect now - derived column

6. Adding another data sources [Output](#6)
>- Excel
>- Text File

7. Auditing [Output](#7)

8. Adding Control Flow Tasks
>- 1. Adding Variables and Row Count [Output](#8_1)
>- 2. Script component [Output](#8_2)


### 3
![image](https://github.com/hashinil/SSIS/assets/33922245/9bc08f79-1c83-4214-96db-039ff8e15c76)

![image](https://github.com/hashinil/SSIS/assets/33922245/08acc1a1-a0f2-471e-9ed6-ab5c71f9250f)


### 4_2
![image](https://github.com/hashinil/SSIS/assets/33922245/bbc7bd37-f427-4a80-9c23-31f413bd7a89)

![image](https://github.com/hashinil/SSIS/assets/33922245/4d6986ca-d5db-4e84-b587-d23279352c92)


### 4_3
![image](https://github.com/hashinil/SSIS/assets/33922245/d3d3479d-ab15-4ead-bda9-6aff5b60202a)

![image](https://github.com/hashinil/SSIS/assets/33922245/72249073-f16b-4584-89a8-75cbef739789)


### 4_4
![image](https://github.com/hashinil/SSIS/assets/33922245/d7537284-4e8c-404b-bc2d-0a5f547edcf7)

![image](https://github.com/hashinil/SSIS/assets/33922245/cb449c51-a943-460f-84bf-6749fd13652b)

![image](https://github.com/hashinil/SSIS/assets/33922245/6129090a-81b4-4d7a-bfae-d8e169a7b73d)


### 4_5
![image](https://github.com/hashinil/SSIS/assets/33922245/48e2cbef-e77c-4f25-aad9-7207e9f50025)

![image](https://github.com/hashinil/SSIS/assets/33922245/e9487c7c-af09-426a-9c3a-65371a3a94e5)


### 4_6
![image](https://github.com/hashinil/SSIS/assets/33922245/54b9ba29-9113-44f5-bbd5-a00736e96300)

![image](https://github.com/hashinil/SSIS/assets/33922245/1df3c07e-d47c-4a57-a1a6-9aea3c322505)


### 4_7
![image](https://github.com/hashinil/SSIS/assets/33922245/8c414e1c-713f-4aac-85b0-7e3db85a26e8)

![image](https://github.com/hashinil/SSIS/assets/33922245/12af5b33-451c-4861-ab8b-15bb5a094113)

![image](https://github.com/hashinil/SSIS/assets/33922245/3115cbf8-9369-4427-9f03-c6bf8db642bb)

![image](https://github.com/hashinil/SSIS/assets/33922245/c8a0f35a-b010-4bbd-a959-9567655001e2)


### 4_8
![image](https://github.com/hashinil/SSIS/assets/33922245/ebd24839-4df4-4b82-8a1d-ab776efd3d85)

![image](https://github.com/hashinil/SSIS/assets/33922245/0357ccbd-e696-4775-92d4-66e927c8b57f)


### 4_9
![image](https://github.com/hashinil/SSIS/assets/33922245/1ee4e33a-f928-4441-8645-3d30c5c25eb5)

![image](https://github.com/hashinil/SSIS/assets/33922245/939a340c-ba7c-4865-97ac-02560978243d)


### 4_10
![image](https://github.com/hashinil/SSIS/assets/33922245/9852fde4-4980-453b-a988-2aac76d9fd9f)

![image](https://github.com/hashinil/SSIS/assets/33922245/7caa441b-7bce-44d0-bba1-6d5bf246dbe5)


### 5
Implemented in Conditional Split [Output](#4_6)


### 6
![image](https://github.com/hashinil/SSIS/assets/33922245/1dfef462-2c61-4e2c-b823-6fa7302246c9)

![image](https://github.com/hashinil/SSIS/assets/33922245/4e293abf-4982-4e8f-9256-220d846f490d)

![image](https://github.com/hashinil/SSIS/assets/33922245/905a0a41-cf84-428f-9b9e-702d47b4bdc7)


### 7
![image](https://github.com/hashinil/SSIS/assets/33922245/f59ade34-8ad5-4ec3-915c-2e1b7811f267)

![image](https://github.com/hashinil/SSIS/assets/33922245/4430811f-4d89-481f-8984-801a8d6eed19)


### 8_1
![image](https://github.com/hashinil/SSIS/assets/33922245/b29d4719-6c27-4015-9c2b-e96cf670fb80)

![image](https://github.com/hashinil/SSIS/assets/33922245/673a2d88-8deb-48df-b071-a08900201322)

![image](https://github.com/hashinil/SSIS/assets/33922245/86627d71-3a92-47fd-933d-e88b30bb14d7)


### 8_2
![image](https://github.com/hashinil/SSIS/assets/33922245/5374139e-80c8-40bb-b9dd-310a9b50a0d8)

![image](https://github.com/hashinil/SSIS/assets/33922245/978e9f73-8543-4c3c-bf63-f27095b24a13)

![image](https://github.com/hashinil/SSIS/assets/33922245/9d6e16d1-f750-427a-8b05-2cd205ab473d)


