# 게임 명: SlimeSurvival_SourceCode

## 게임 설명
**스테이지마다 다가오는 슬라임을 쓰러트려 살아남는 서바이벌 게임**

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
