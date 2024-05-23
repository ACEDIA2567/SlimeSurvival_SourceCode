# 프로젝트 명: SlimeSurvival

## 프로젝트 설명
- **설명: 스테이지마다 다가오는 슬라임을 쓰러트려 살아남는 서바이벌 게임**    
- **컨셉: 물량 막기**    
- **장르: 슬라임으로부터 살아남는 서바이벌**    

- **멤버: 이재형, 강수지, 서영현, 최도규**

## 프로젝트 사진
| 처음 화면 | 진행 화면 | 엔딩 화면 |
| ------------ | ------------- |------------- |
| ![image](https://github.com/ACEDIA2567/SlimeSurvival_SourceCode/assets/101154683/abe48437-097c-4138-952c-b9c21f9a8a95) | ![image](https://github.com/ACEDIA2567/SlimeSurvival_SourceCode/assets/101154683/c357cf12-bfcc-4034-a65a-4314ae3dc8f7)  | ![image](https://github.com/ACEDIA2567/SlimeSurvival_SourceCode/assets/101154683/e9fdefb7-cef7-4a18-8554-2ea37dc4fdca)  |

## 프로젝트 진행 순서
![image](https://github.com/ACEDIA2567/SlimeSurvival_SourceCode/assets/101154683/196a6f5d-b9d5-4327-89f3-2bc3fe8a66e1)    

## 진행 방식
![SlimeGif](https://github.com/ACEDIA2567/SlimeSurvival_SourceCode/assets/101154683/a2897f92-019c-4a95-96f0-e243c5a7761c)    
**다가오는 슬라임을 향해 공격하여 슬라임으로부터 살아남으세요!**    

![image](https://github.com/ACEDIA2567/SlimeSurvival_SourceCode/assets/101154683/839adba9-db70-4f3e-93f2-6f87d94400c0)    
**강화를 하여 더욱 강해져 오랫동안 버텨보세요!**    

## 조작법
**이동: WASD**  
**공격: 우클릭**  
**상호작용: F**  


## 📌Code Setting
>📦Assets     
 ┣ 📂ScriptableObjects    
 ┃ ┣ 📂Scripts ▶ ScriptableObject를 이용한 스크립트       
 ┃ ┃ ┣ 📜AttackSO.cs    
 ┃ ┃ ┣ 📜RangedAttackSO.cs    
 ┗ 📂Scripts    
 ┃ ┣ 📂Entities    
 ┃ ┃ ┣ 📂Behaviors ▶ MonoBehaviors를 이용한 스크립트    
 ┃ ┃ ┃ ┣ 📜CharacterInteraction.cs    
 ┃ ┃ ┃ ┣ 📜DestoryOnDeath.cs    
 ┃ ┃ ┃ ┣ 📜HealthSystem.cs    
 ┃ ┃ ┃ ┣ 📜NPC.cs    
 ┃ ┃ ┃ ┣ 📜ProjectileController.cs    
 ┃ ┃ ┃ ┣ 📜TopDownAimRotation.cs    
 ┃ ┃ ┃ ┣ 📜TopDownMovement.cs    
 ┃ ┃ ┃ ┣ 📜TopDownShooting.cs    
 ┃ ┃ ┣ 📂Controllers ▶ 움직임 제어 스크립트    
 ┃ ┃ ┃ ┣ 📜AnimationController.cs    
 ┃ ┃ ┃ ┣ 📜PlayerInputController.cs    
 ┃ ┃ ┃ ┣ 📜TopDownAnimationController.cs    
 ┃ ┃ ┃ ┣ 📜TopDownContactEnemyController.cs    
 ┃ ┃ ┃ ┣ 📜TopDownController.cs    
 ┃ ┃ ┃ ┣ 📜TopDownEnemyController.cs    
 ┃ ┣ 📂GameManager ▶ 게임을 진행시켜주는 스크립트       
 ┃ ┃ ┣ 📜GameManager.cs    
 ┃ ┃ ┣ 📜SoundManager.cs    
 ┃ ┃ ┣ 📜StageManager.cs    
 ┃ ┃ ┣ 📜UIManager.cs    
 ┃ ┣ 📂Status ▶ 캐릭터의 정보에 대한 스크립트       
 ┃ ┃ ┣ 📜CharacterStatus.cs    
 ┃ ┃ ┣ 📜CharacterStatusHandler.cs    
 ┃ ┣ 📂Util ▶ 그 외의 기능에 대한 스크립트    
 ┃ ┃ ┣ 📜ButtonInfo.cs    
 ┃ ┃ ┣ 📜ObjectPool.cs    
