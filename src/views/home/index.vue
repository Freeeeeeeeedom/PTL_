<template>
  <div>

<h1 class = "txt1"> 
   <pre>   Welcome to the PTL-LAB</pre></h1>
<h3 class = "txt2">
    <pre>   PTL-LAB a team focusing on diversified investments such as<br>   equency trading, trend tracking and risk-free arbitrage in the cryptocurrency market.</pre></h3>

<h3 class = "txt2"><pre>   The team is committed to achieving more stable returns in the cryptocurrency market through<br>   diversified investment.And through the empirical research of a large number of data, the
<br>   development of a variety of venture fund portfolios can help investors obtain excess returns.</pre>
</h3>

<h4 class = "txt4"><pre>   See the FUND page for more information</pre></h4>
<h3 class = "txt2"><pre>   The team uses advanced machine learning algorithms <br>   and integrates practical financial andtrading ideas to ensure that the model can capture market <br>   fluctuations as much as possible.</pre></h3>
<h4 class = "txt4"><pre>   See the TECH page for more information</pre></h4>

  </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
  name: 'Home',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style >
.txt2{
    text-align: left;
    line-height: 150%;
}
.txt1{
    text-align: left;
    line-height: 100%;
}
.txt4{
    text-align: left;
    line-height: 100%;
}
</style>
