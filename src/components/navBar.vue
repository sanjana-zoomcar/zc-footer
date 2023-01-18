<template>
<div>
    <div class="navB">
        <button id="F1" v-on:click="change('F1div')" >ABOUT US</button>
        <button id="F2" v-on:click="change('F2div')"> BLOGS </button>
        <button id="F3" v-on:click="change('F3div')">CAREERS</button>
        <button id="F4" v-on:click="change('F4div')" >CONTACT</button>
    </div>
    <div id="info" class="allInfo">
        <h4>Header</h4>
            <p>No more worries about petrol mileage, fuel costs, insurance, and car breakdowns! Zoomcar has enabled driving convenience for travellers around the country and is fast expanding its reach to cities including Ahmedabad, Bangalore, Chandigarh, Chennai, Coimbatore, Delhi-NCR, Hyderabad, Jaipur, Kochi, Kolkata, Ludhiana, Mangalore, Mumbai, Mysore, Pune, Siliguri and Vizag.  Self drive cars from Zoomcar.</p>
    </div>

    <div >
        <div id="F1div" class="allInfo" style="display:none;"><h4>Header</h4>
            <p>No more worries about petrol mileage, fuel costs, insurance, and car breakdowns! Zoomcar has enabled driving convenience for travellers around the country and is fast expanding its reach to cities including Ahmedabad, Bangalore, Chandigarh, Chennai, Coimbatore, Delhi-NCR, Hyderabad, Jaipur, Kochi, Kolkata, Ludhiana, Mangalore, Mumbai, Mysore, Pune, Siliguri and Vizag.  Self drive cars from Zoomcar.</p>
        </div>
        <div id="F2div" class="allInfo" style="display:none;" ><h4>Blogs</h4></div>
        <div id="F3div" class="allInfo" style="display:none;"><h4>Career</h4></div>
        <div id="F4div" class="allInfo" style="display:none;"><h4>Contact</h4></div>
    </div>
</div>

</template>

<script scoped>

export default{
    name:'navBar',
    methods:{
        change: function(idx){

            //let divs=document.getElementsByClassName("allInfo");
            //for(let i=0;i<divs.length;i++){
              //  divs[i].style.dispaly = "none";
                //alert(divs[i]);
            //}
                document.getElementById('info').innerHTML = document.getElementById(idx).innerHTML;
    
        }
    }

            

        }
    
    
</script>
<style scoped>
.navB{
    padding:10px;
    max-width:100%;
    color:white;
    display:flex;
    background-color:#383838;
}
button{
    border:none;
    width:25%;
    height: 36px;
    padding:10px;
    font-family: Sans-serif;
    font-size: 12px;
    text-decoration: none;
    color: var(--white);
    background-color:#383838;
}
button:hover{
    border-bottom: 2px solid white;
}
button:active{
    border-bottom: 2px solid white;
}

.allInfo{
    font-family:sans-serif;
    font-weight:lighter;
    padding:20px;
    max-width:100%;
    height:100%;
    color:white;
    background-color:#383838;
}

</style> 