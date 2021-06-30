<template>
  <section class="section">
    <img src="../assets/soccer.png" >
    <div style="position:relative;">

         <movable class="testmove" posTop="4"  posLeft="0" :grid="20"><span class="move-text"><p>カズ</p></span></movable>
         <movable class="testmove" posTop="4"  posLeft="80" :grid="20"><span class="move-text"><p>武田</p></span></movable>
         <movable class="testmove" posTop="4" posLeft="160" :grid="20"><span class="move-text"><p>ラモス</p></span></movable>
         <movable class="testmove" posTop="4" posLeft="240" :grid="20"><span class="move-text"><p>呂比須</p></span></movable>
         <movable class="testmove" posTop="4" posLeft="320" :grid="20"><span class="move-text"><p>井原</p></span></movable>
         <movable class="testmove" posTop="4" posLeft="400" :grid="20"><span class="move-text"><p>北澤</p></span></movable>
         <movable class="testmove" posTop="84" posLeft="0" :grid="20"><span>grid:20</span></movable>
         <movable class="testmove" posTop="84" posLeft="80" :grid="20"><span>grid:20</span></movable>
         <movable class="testmove" posTop="84" posLeft="160" :grid="20"><span>grid:20</span></movable>
         <movable class="testmove" posTop="84" posLeft="240" :grid="20"><span>grid:20</span></movable>
         <movable class="testmove" posTop="84" posLeft="320" :grid="20"><span>grid:20</span></movable>

         <movable class="testmove-away" posTop="84" posLeft="400" :grid="20"><span class="move-text"><p>バレージ</p></span></movable>
         <movable class="testmove-away" posTop="4"  posLeft="480" :grid="20"><span class="move-text"><p>バッジョ</p></span></movable>
         <movable class="testmove-away" posTop="4"  posLeft="560" :grid="20"><span class="move-text"><p>マルディーニ</p></span></movable>
         <movable class="testmove-away" posTop="4" posLeft="640" :grid="20"><span class="move-text"><p>ゾラ</p></span></movable>
         <movable class="testmove-away" posTop="4" posLeft="720" :grid="20"><span class="move-text"><p>コンテ</p></span></movable>
         <movable class="testmove-away" posTop="4" posLeft="800" :grid="20"><span class="move-text"><p>ディノ・バッジョ</p></span></movable>
         <movable class="testmove-away" posTop="84" posLeft="480" :grid="20"><span>grid:20</span></movable>
         <movable class="testmove-away" posTop="84" posLeft="560" :grid="20"><span>grid:20</span></movable>
         <movable class="testmove-away" posTop="84" posLeft="640" :grid="20"><span>grid:20</span></movable>
         <movable class="testmove-away" posTop="84" posLeft="720" :grid="20"><span>grid:20</span></movable>
         <movable class="testmove-away" posTop="84" posLeft="800" :grid="20"><span>grid:20</span></movable>
    </div>
  </section>
</template>

<script>
import Card from '~/components/Card'

export default {
  name: 'HomePage',

  components: {
    Card
  }
}
</script>
<style>
  .testmove {
    display:block;
    position: absolute;
    top: 0;
    height: 60px;
    width: 60px;
    /* margin: 200px; */
    background: rgb(121, 162, 250);
    color: white;
    border-radius: 80px;
  }

  .testmove-away {
    display:block;
    position: absolute;
    top: 0;
    height: 60px;
    width: 60px;
    /* margin: 200px; */
    background: red;
    color: white;
    border-radius: 80px;
  }

  .move-text{
    font-size: 20px;
    text-align: center;
    font-weight: 900;
  }
  .modaltitle {
    background: rgb(121, 162, 250);
    display:block;
    width:100%;
    color: white;
  }
</style>
