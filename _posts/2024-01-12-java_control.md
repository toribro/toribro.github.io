---
title:  자바_제어문
categories: Java
---
## 조건문
 - 조건식을 통해 참 또는 거짓을 판단하여 참일경우 해당하는 코드를 실행
 - 조건문에는 if문과 switch이 있다.

### if 문
  ```java
    if(조건식){
        //실행문1
    }else if(조건식2) {
       //실행문2
    }
    else{
       //실행문3
    }

  ```


### switch문
  ```java
   switch(비교대상(정수,문자,문자열)){
            case 값1 : 실행코드; break;
            case 값2 : 실행코드2; break;
                    // ...
            default: 위의 값들이 모두 일치하지 않았을때 실행하는 코드;
    }
  ```
      
    
## 반복문
 - 프로그램 수행 흐름을 바꾸는 역할을 하는 제어문중 하나로 특정 문장들을   반복해서 수행하도록 한다.
 - for,while,do while문이 있다


### for 문 
 - 길이가 제한된 반복에 사용


    ```java
     for (초기식;조건식;증감식){
                //본문 내용
     }
    
    ```
       
    
### while 문
- 제한없는 반복문에도 사용 (횟수를 모를때)


    ```java
      while(초기식){
        //본문내용
        증감식;
      }
    
     ```
     
### do while 문
 - 조건에 관계없이 무조건 한번은 실행

    ```java
       do{
            //본문내용
            증감식;

        }while(초기식);
        
    
    ```