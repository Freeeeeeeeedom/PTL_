<template>
<div>
  <div class="Black">
    <h3 class = "hh3"><pre><br>  <br>    Advanced quantitative models<br>
      continue to generate value for investors<br>
      </pre></h3>
  </div>
  <div class = "White">
    <h3 class = "hh3 "><br>         The two flagship fund adapt to different risk preferences <br><br>    <hr class='hori-line' /><pre>Beta revenue                                                  Alpha revenue</pre>
    <hr class='hori-line' /><pre>        Pursuit of stability                                         Pursuit of excess return</pre>
    <pre>Arbitrage transcation                                            Trend tracking   </pre>
    <pre>Multi index hedging strategy                                       CTA strategy    </pre>
    <pre>10-20% annualized maximum pullback within 2%              Absolute return without limitation</pre>
    </h3>  
  </div>
  <br>
  <div class = "Black">
    <br>
    <h3 class = "hh3" ><br>Excellent back test performance<br><br>
    The practical transaction is also bright enough<br></h3>
  <br>
  </div>
  <br>
  <br>
  <div class = "White">
     <h3 class = "hh3" ><br>Invest money then push it to the limit right now !<br></h3>
     <hr class='hori-line' />
  <br>

  </div>
</div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style >
.hh3{
  text-align: center;
}

.Black{
  background-color:rgba(5, 16, 51, 0.048);
  text-emphasis-color: Black;
  }
.White{
  
  background-color: rgb(255, 255, 255);
}
</style>
