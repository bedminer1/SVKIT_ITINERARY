<script>
    let lunchLocations = [
        {
            name:'Chun Shui Tang',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Yuan Fang Guabao',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Raohe',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'DTF',
            imgSrc:'',
            description:'chocolate xiao long bao, have to reserve',
            location: ''
        },
    ]

    let dessertLocations = [
        {
            name:'Sesami Mochi Pancake from Taipei Main Station',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Bulao Hakka Traditional Mochi',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Summer Savage',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Looproom',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'After5_',
            imgSrc:'',
            description:'',
            location: ''
        },
    ]

</script>

<div class=''>
    <h1 class="text-center">MEATS</h1>
    {#each lunchLocations as place, index}
        <div class="w-full h-20">
            <h2>{index + 1}. {place.name}</h2>
            <p class="pl-3 text-2xl">notes: {place.description}</p>
            <p>{place.location}</p>
        </div>
    {/each}
    <h1 class="text-center">DESSERT</h1>
    {#each dessertLocations as place, index}
        <div class="w-full h-20">   
            <h2>{index + 1}. {place.name}</h2>
            <p class="pl-3 text-2xl">notes: {place.description}</p>
            <p>{place.location}</p>
        </div>
    {/each}
</div>

<style>
    h1 {
        font-size: 60px;
    }

    h2 {
        font-size: 40px;
        padding-left: 20px;
    }
</style>