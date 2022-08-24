<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <header>
    <h1>Gelir Takibi</h1>
    <div class="total-income">£{{totalIncome}} </div>
  </header>
</template>

<script>
export default {
    props: {
        totalIncome: Number
    }

}
</script>

<style scoped>
header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    background-color:#FFD100 ;
    border-bottom: 5px solid #333533;

}
header h1 {
    color: #202020;
    font-size: 28px;
}

header .total-income {
    font-family: 'FiraCode', 'Fira Sans', sans-serif;
    background-color:#333533 ;
    color: #ffed31;
    font-size: 20px;
    font-weight: 900;
    padding: 5px 10px;
    min-width: 100px;
    text-align: center;
    border-radius: 8px;
    box-shadow: inset 0px 0px 6px rgba(0, 0, 0, 0.25);
    text-shadow: 0px 3px 3px rgba(0,0,0,0.25);
}


</style>