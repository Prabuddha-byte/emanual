
모터의 최대 출력 제한 값입니다.  
0 ~ 1,023 (0x3FF) 까지 사용 가능하며, 단위는 약 0.1%입니다.  
예를 들어, 값이 512이면 약 50%이고 최대 출력 대비 50%만 사용하겠다는 의미입니다.  
전원이 켜지면 Torque Limit(Address 34, 35)는 이 값을 초기 값으로 사용합니다.