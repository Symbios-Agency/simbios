<div class="container-custom">
    <div class="w-full h-[1px] bg-[#27282B]"></div>
    <div class="flex mt-20">
        <h1 class="basis-1/2 font-euclid font-medium text-5xl">УСЛУГИ</h1>
        <div class="basis-1/2">
            <p class="font-euclid text-[22px] font-regular">Создаем сайты с нуля с адаптацией под поисковые системы и запросы пользователей.Продвигаем бизнес в сети интернет уже с существуещим сайтом.</p>
            <ul class="font-euclid font-bold text-4xl mt-20 services">
                <li class="flex justify-between"><p class="my-auto">Разработка сайта</p> <span><slot /></span></li>
                <li class="flex justify-between"><p class="my-auto">Дизайн андентика</p> <span><slot /></span></li>
                <li class="flex justify-between"><p class="my-auto">Мобильная разработка</p> <span><slot /></span></li>
                <li class="flex justify-between"><p class="my-auto">Чат-боты</p> <span><slot /></span></li>
            </ul>
        </div>
    </div>
</div>