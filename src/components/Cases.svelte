<script>
    import Card from '../components/Card.svelte'
</script>
<div class="container-custom mt-32">
    <div class="w-full h-[1px] bg-[#27282B]"></div>
    <div class="flex justify-between mt-32  ">
        <div class="basis-2/3 grid grid-cols-12">
            <h1 class="col-span-5 font-euclid font-medium text-5xl">НАШИ КЕЙСЫ</h1>
            <div class="w-[40px] h-[1px] bg-[#27282B] my-auto"></div>
            <div class="my-auto flex justify-center items-center w-[97px] h-[44px] border-inherit border-[1px] rounded-[60px]">
                <p class="font-euclid">4 - 20</p>
            </div>
        </div>
        <button class="flex justify-center w-[330px] h-[44px] border-[1px] border-inherit rounded-[60px]">
            <p class="font-euclid my-auto font-medium text-lg">Перейти к нашим кейсам</p>
            <span class="my-auto ml-3"><slot name="arrow"/></span>
        </button>
    </div>
    <div class="grid grid-cols-2 grid-rows-2">
        <Card />
        <Card />
        <Card />
        <Card />
    </div>
</div>