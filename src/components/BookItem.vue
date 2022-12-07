<template>

    <div>
        <h1>{{book.mylist}}</h1>
        <h2> Recently added : {{book.recentlyadded}}</h2>
        <h4> Trending: {{book.trending}}</h4>
        <h4> Different Genre : {{book.diffgenre}}</h4>
        <h4> Top Searches : {{book.topsearches}}</h4>
        <h4> Downloads : {{book.downloads}}</h4>

        
    </div>

</template>

<script>




export default{
    name: 'BookItem',
    props:{
        book: Array
    }
}


</script>

<style scoped>

h2{
    text-align: center;
}

h1{
    text-align: center;
}
h4{
    text-align: center;
}

#body{
  background-color: #e6ff00;
}
div{
    background-color: #a09eff;
    color: black;
    padding: 1em;
}

.red{
background-color: orangered !important;

}
.green{
    color: white;
}


</style>
