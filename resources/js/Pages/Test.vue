<script setup></script>
<template>
    <main
        class="md:flex items-center justify-between hidden px-5 py-3 bg-neutral-100 text-neutral-600 rounded-lg"
    >
        <h1 class="text-8xl text-neutral-800">Looggo</h1>
        <div class="flex gap-2">
            <a
                href="#"
                class="hover:bg-neutral-300 transition-all duration-300 p-2"
                >Home</a
            >
            <a
                href="#"
                class="hover:bg-neutral-300 transition-all duration-300 p-2 rounded-sm"
                >About</a
            >
            <a
                href="#"
                class="hover:bg-neutral-300 transition-all duration-300 p-2 rounded-sm"
                >Contact</a
            >
            <a
                href="#"
                class="hover:bg-neutral-300 transition-all duration-300 p-2 rounded-sm"
                >Login</a
            >
            <a
                href="#"
                class="hover:bg-neutral-300 transition-all duration-300 p-2 rounded-sm"
                >Register</a
            >
        </div>
        <!-- ...Hero Section -->
    </main>
    <div
        class="flex  bgImage justify-between items-center flex-col md:flex-row p-4 max-w-7xl mx-auto md:min-h-screen gap-4"
    >
        <div class="flex flex-col gap-2 md:max-w-[50%] z-10">
            <h1
                class="font-bold text-indigo-500 text-4xl space-y-4 md:text-5xl tracking-wider"
            >
                Welcome
                <span class="text-blue-500">{{ "Guest" }}</span>
            </h1>
            <p
                class="font-medium text-lg  leading-10 tracking-wider selection:bg-indigo-100"
            >
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Velit
                quo dolorem ab recusandae ipsa dolores pariatur inventore atque
                magnam doloremque at facilis sit, nobis veniam unde esse
                assumenda consectetur hic.
            </p>
        </div>
        <div class="bg-neutral-100 p-4 z-10">
            <img
                class="w-full h-80 md:h-96"
                src="https://images.unsplash.com/photo-1580489944761-15a19d654956?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=774&q=80"
                alt=""
            />
        </div>
    </div>
    <!-- About -->
    <div class="p-8 pt-10">
        <h1 class="text-6xl font-extrabold text-gray-800">About</h1>
        <p
            class="font-medium text-lg leading-10 tracking-wider selection:bg-indigo-100"
        >
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Velit quo
            dolorem ab recusandae ipsa dolores pariatur inventore atque magnam
            doloremque at facilis sit, nobis veniam unde esse assumenda
            consectetur hic.
        </p>
    </div>
</template>
<style lang="css" scoped>
.bgImage {
  position: relative;
   background:red url("/bg.jpg") no-repeat center /cover;
   background-clip: text;
  
  z-index: 0;
}

.bgImage::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
 
  background: rgba(0, 0, 0, 0.6);
}
</style>
