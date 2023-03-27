# 2023_OSS
## 2023 OSS 수업
***
### 3주차 git  
### 이미지  
![kau](https://github.com/heg-git/2023_OSS/blob/main/img/kau/kau.png)
### 링크  
[LMS](https://lms.kau.ac.kr/login.php)  
#### ProGit 링크
[ProGit](https://git-scm.com/book/ko/v2)  
  
##### 주요 git 명령어  
* add: 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용  
  * 예) git add  
* commit  
* branch  
* merge  
* status  
* log  
  * 예) git log --oneline --decorate --graph --all  
***  

### 2주차 숙제  
```Bash
#!/usr/bin/env/bash
echo “----------”
echo “name :”
echo 

echo “----------”
echo “student id :”
echo -e “----------\n”

echo “file path:”
path=$(find /home/kau2 -name “w2_homework.txt” 2> /dev/null)
echo $path

echo -e “\n----------”
echo “line number :”
echo $(cat $path | wc -l)

echo -e “\n----------”
echo “last line :”
echo $(tail $path -n 1)
```  

## 마크다운  
### 목록  
#### 번호 있는 목록 : 내림차순 정렬  
1. 첫번째
2. 세번째
3. 두번째
#### 번호 없는 목록: *, -, +
* 첫번째  
 
* 세번째  

* 두번째  
***  
* 빨강
  * 녹색  
    * 파랑  
#### 강조
*single asterisks*  
_single underscores_  
**double asterisks**  
__double underscores__  
~~cancelline~~  



