<template>
    <div class="foot">
        <p>We operate in many other citiies</p>
        <div class="india">
            <h4>INDIA</h4>
            <ul>
                <li>Bangalore</li>
                <li>Pune</li>
                <li>Delhi NCR</li>
                <li>Mumbai</li>
                <li>Chennai</li>
                <li>Hyderabad</li>
                <li>Chandigarh</li>
                <li>Kolkata</li>
                <li>Ahmedabad</li>
                <li>Coimbatore</li>
                <li>Indore</li>
                <li>Jaipur</li>
                <li>Mangalore</li>
                <li>Mysore</li>
                <li> Vizag</li>
            </ul>
        </div>
        <div class="places">
            <div class="egypt"><h4>EGYPT</h4></div>
            <div class="vietnam"><h4>VIETNAM</h4></div>
            <div class="indo"><h4>INDONASIA</h4></div>
        </div>
    </div>
</template>
<script>
export default{
    name:'footerBar'
}
</script>
<style scoped>
.foot{
    font-family:sans-serif;
    padding:20px;
    color:white;
    max-width:100%;
    display:flex;
    flex-direction:column;
    background-color:#666666;
}
.places{
    display:grid;
    grid-template-columns: 1fr 1fr;
}

.india ul{
    display:grid;
    grid-template-columns:auto auto;
    padding:0;
    gap:10px;
}
li{
    list-style-type:none;
    margin:0;
}

</style> 