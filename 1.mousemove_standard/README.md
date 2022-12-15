## 마우스 이동하는 이벤트는 window.addEventListener('mousemove')
- mousemove 이벤트의 event.clientX / event.clientY => 마우스의 x좌표, y좌표 

## 성능이 좋은 애니메이션 구현 방법 window.requestAnimationFrame

## 마우스 반응을 점진적으로 표현하려면 
 - 공식처럼 외우자 
 ```js
            mouseX += (x - mouseX) * speed;
            mouseY += (y - mouseY) * speed;
 ```

 ## 마우스 좌표를 중간으로 위치하려면
 ```js
     x = (e.clientX - window.innerWidth / 2);
     y = (e.clientY - window.innerHeight / 2); 
 ```