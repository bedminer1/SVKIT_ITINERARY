<script>
    let shopAreaLocations = [
        {
            name:"Da'an District",
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Zhong Shan District',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Ximen',
            imgSrc:'',
            description:'NIKE',
            location: ''
        },
        {
            name:'Guanghua',
            imgSrc:'',
            description:'tech',
            location: ''
        },
        {
            name:'ZhongXiao Dunhua',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Shilin Night Market',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Xinyi/Taipei101 area',
            imgSrc:'',
            description:'',
            location: ''
        },
    ]


</script>

<div class=''>
    <h1 class="text-center">SHOPPING AREAS</h1>
    {#each shopAreaLocations as place ,index}
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