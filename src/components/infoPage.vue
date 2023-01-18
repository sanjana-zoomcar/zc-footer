<template>
    <!--<div class="allInfo">
    <div v-show="1==1" class="aboutUs">
        <h4>Header</h4>
        <p>No more worries about petrol mileage, fuel costs, insurance, and car breakdowns! Zoomcar has enabled driving convenience for travellers around the country and is fast expanding its reach to cities including Ahmedabad, Bangalore, Chandigarh, Chennai, Coimbatore, Delhi-NCR, Hyderabad, Jaipur, Kochi, Kolkata, Ludhiana, Mangalore, Mumbai, Mysore, Pune, Siliguri and Vizag.  Self drive cars from Zoomcar.</p>
    </div>
    <div v-show="index==2" class="blogs"><h4>Blogs</h4></div>
    <div v-show="index==3" class="career"><h4>Career</h4></div>
    <div v-show="index==4" class="contact"><h4>Contact</h4></div>
    </div>-->
</template>
<script>
export default({
    name: 'infoPage',
    prop:{
        index: Number
    }
})
</script>
<style>
.allInfo{
    font-family:sans-serif;
    font-weight:lighter;
    padding:20px;
    max-width:100%;
    height:100%;
    color:white;

    background-color:#383838;
}
p{
    font-size: 12px;
}
h4{
    margin:0;
}
</style>