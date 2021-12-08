<template>
  <header class="header">
    
      <div class="">
        <a href="#accueil" class="">
          <img src="" alt="">
        </a>
    
        <nav class="">
          <ul class="">
            <li class="">
              <a href="" class="">
              </a>
            </li>
    
            <li class="">
              <a href="" class="">
              </a>
            </li>
          </ul>
        </nav>
      </div>
    
      <nav class="">
        <ul class="">
          <li class="">
            <a href="#menu" class=""><span>Notre carte</span></a>
          </li>
          <li class="">
            <a href="#place" class=""><span>Le restaurant</span></a>
          </li>
          <li class="">
            <a href="#team" class=""><span>Notre équipe</span></a>
          </li>
          <li class="">
            <a href="#food" class=""><span>La cuisine</span></a>
          </li>
          <li class="">
            <a href="#cabout" class=""><span>Venir à notre table</span></a>
          </li>
        </ul>
      </nav>
    
      <div class="">
        <a href="" class="">réserver</a>
      </div>
    
      <a href="" class="">À emporter</a>
    
    </header>
</template>

<script>
export default {
  name: 'Header',
  
}
</script>


<style scoped lang="scss">
.header {
  position: fixed;
  z-index: z(header);
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100vw;
  min-width: 660px;
  padding: 0 2rem;

  // 90degree menu
  flex-direction: row-reverse;
  width: 100vh;
  transform-origin: top left;
  transform: rotate(-90deg) translateX(-100%);

 
}


</style>
