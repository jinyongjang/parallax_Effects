# Parallax Effects
-------------------------------

![parallaxEffects 썸네일이미지](/img/parallax-page.png)

##### 스크롤에 따른 여러 효과를 javascript와 gsap로 각각 구현해보았습니다.    
##### gsap는 ScrollTrigger를 만들어 애니메이션을 다루었습니다.    
##### pin효과, scrub등을 사용하여 다양하게 구현했습니다.

### 완성된 site 주소 : [ParallaxEffects][parallaxlink]
[parallaxlink]: https://jinyongjang.github.io/web2023/javascript/parallax/parallaxEffect01.html "go parallaxEffects"

------------------------------
## 사용 스택
- gsap : (https://greensock.com/gsap/)를 사용하여 타임라인 애니메이션을 만들고 ScrollTrigger로 제어했습니다.
- lenis : (https://lenis.studiofreight.com/)를 사용하여 부드러운 스크롤 효과를 구현했습니다.
- javascript의 메서드를 사용해 scrollTop값을 구해 값에 따른 효과를 구현했습니다.
- html, css 를 사용하여 기본적인 페이지를 구성했습니다.

-----------------------------------
## GSAP    
gsap의 애니메이션 효과를 사용해 스크롤함에 따라 해당하는 대상에 애니메이션을 추가할 수 있고, 일정 스크롤 동안 대상을 고정(pin)시킬 수 있습니다.
gsap의 애니메이션 효과를 사용해 스크롤함에 따라 화면이 가로로 스크롤 되는 듯한 효과를 구현할 수 있고, 세로 + 가로 + 세로 모드의 구현이 가능합니다.
gsap의 snap기능을 조절하여 스크롤 중단 시, 화면에 맞게 구현할 수 있습니다.
