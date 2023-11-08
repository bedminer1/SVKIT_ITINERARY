<script>
    let cityLocations = [
        {
            name:'Chang Kai Shek Memorial Hall',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Longshan Temple',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Bopiliao Historical Block',
            imgSrc:'',
            description:'',
            location: ''
        },
        {
            name:'Taipei101',
            imgSrc:'',
            description:'',
            location: ''
        },
    ]


</script>

<div class=''>
    <h1 class="text-center">VIEWS & NERDING</h1>
    {#each cityLocations as place, index}
        <div class="w-full h-20">
            <h2>{index + 1}. {place.name}</h2>
            <p class="pl-3 text-2xl">{place.description}</p>
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