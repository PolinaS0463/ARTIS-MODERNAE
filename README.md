># Artis Modernae
>## A training website layout / Тренировочная верстка сайта

Реализованы __Scroll Smoother__, __Scroll Trigger__ и так называемые __Floating Images__ при скролле. Для этого были использованы библиотеки __js__:
```
<script src="libs/gsap/gsap.min.js" defer></script>   
<script src="libs/gsap/ScrollTrigger.min.js" defer></script>  
<script src="libs/gsap/ScrollSmoother.min.js" defer></script>
```
Параметры _задержки_, _триггера_ и т.д. используются, например, так:
```
<img data-lag=".5" data-speed=".6" class="hero" src="img/hero.png" alt="Alt">
```