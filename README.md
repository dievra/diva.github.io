## Pool Info :

<script  src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script>
$.getJSON('https://js.adapools.org/pools/d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43/summary.json', function(data) { 
$.each( data.data, function( i, val ) { 
		a=new Array('tax_fix','pledge','total_stake');
		if(parseInt(val) > 100000) val=Math.round(parseInt(val)/1000000);
		if(i=='blocks_lifetime') val=parseInt(val) + parseInt(data.data.blocks_epoch);

		$('#d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_'+i).html(val).text();   
}); 
		});
</script>

Pool ID: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_pool_id"></span><br>
		Ticker: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_db_ticker"></span><br>
		Name: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_db_name"></span><br>
		Description: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_db_description"></span><br>
		Total Stake: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_total_stake"></span><br>
		Last Reward Epoch: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_rewards_epoch"></span><br>
		Tax Ratio: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_tax_ratio"></span><br>
		Tax Fix: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_tax_fix"></span><br>
		ROA: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_roa">%</span><br>
		Blocks Lifetime: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_blocks_lifetime"></span><br>
		Blocks in epoch: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_blocks_epoch"></span><br>
		Pledge: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_pledge"></span><br>
		Rank: <span id="d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43_rank"></span><br>
		More info on <a href="https://adapools.org/pool/d1f84ed69e422531edc277f027f2d8d66d0ad4daa0348496a69c4a43">ADApools.org</a>.

## Mission : 

* security : We set up our pools with all the necessary security measures.
* consistency : We are striving to produce consistent blocks and to keep up with the evolution of the cardano eco-system.
* availability : We are striving to keep our servers up and running with the least possible down-time.
* profitability :  We are striving to provide our delegators with as much profits as possible while keeping our fees low.

## Why the name STYX ?

In Greek mythology STYX is the name of the River or Swamp that forms the boundary between Earth and the Underworld.
Several names out of the cardano ecosystem are derived from ancient Greek mythology :


- Daedalus : Official wallet of Cardano platform   /   skillful craftsman and artist /  Daedalus the father of Icarus
- Icarus : Icarus is a reference implementation for a lightweight wallet. Yoroi is the first to use the reference./   Son of Daedalus
- Ourobouros : Proof of stake protocol (originated in ancient Egyptian iconography but entered western tradition via Greek magical tradition
- Plutus : Plutus is a strictly typed pure functional programming language used for defining smart contracts in Cardano /Plutus (Ploutos, literally "wealth") was the god of wealth in ancient Greek religion and Greek mythology.

We thought it would be cool to continue that tradition. That's how we came up with the name STYX.


Check out other names that are commonly used in the cardano eco-system
[https://cardanowiki.info/wiki/Cardano_Names](https://cardanowiki.info/wiki/Cardano_Names)


