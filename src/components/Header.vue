<template>
    <header class="flex justify-between border-b border-slate-300 px-10 py-8">
        <div class="flex items-center gap-4">
            <img src="/img/logo.png" alt="Logo" class="w-10">
            <div>
                <h2 class="text-xl font-bold uppercase">Rangle Store</h2>
                <p class="text-slate-400">Магазин лучших кроссовок</p>
            </div>
        </div>

        <ul class="flex items-center gap-10">
            <li class="flex items-center gap-3 text-gray-500 cursor-pointer hover:text-black">
                <img src="/img/cart.svg" alt="">
                <b>1250 руб.</b>
            </li>

            <li class="flex items-center gap-3 text-gray-500 cursor-pointer hover:text-black">
                <img src="/img/heart.svg" alt="">
                <span>Закладки</span>
            </li>

            <li class="flex items-center gap-3 text-gray-500 cursor-pointer hover:text-black">
                <img src="/img/user.svg" alt="">
                <span>Профиль</span>
            </li>
        </ul>
    </header>
</template>