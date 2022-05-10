<template>
  <div class="bg-cyan relative h-screen z-0 overflow-hidden">
    <div class="absolute -left-1/4 bottom-1/2 overflow-hidden">
      <img src="/bg-pattern-top.svg" class="pointer-events-none" alt="">
    </div>
    <div class="absolute -right-1/4 top-1/2 overflow-hidden z-10">
      <img src="/bg-pattern-bottom.svg" class="" alt="">
    </div>



    <div class="flex justify-center items-center mx-auto min-h-screen">
      <div class="w-4/5 text-center rounded-[40px] sm:max-w-[350px] bg-white z-50">
        <div>
          <img src="/bg-pattern-card.svg" class="w-full rounded-t-[40px]" alt="">
        </div>
        <div>
          <div class="-translate-y-1/2">
            <div class="inline-block bg-white rounded-full">
              <img src="/image-victor.jpg" class="rounded-full border-8 border-white" alt="">
            </div>
          </div>
          <span class="block -mb-4 -translate-y-full">
            <span class="font-bold">
              Victor Crest
            </span>
            <span class="font-light">26</span><br>
            <span class="text-sm font-extralight">
              London 
            </span>
          </span>
        </div>
        <hr>
        <div class="flex justify-between w-full p-10 md:p-8">
          <div>
            <span class="font-bold text-xl">80K </span><br> 
            <span class="text-xs font-light text-slate-400">Followers</span> 
          </div>
          <div>
            <span class="font-bold text-xl">803K </span><br> 
            <span class="text-xs font-light text-slate-400">Likes</span> 
          </div>
          <div>
            <span class="font-bold text-xl">1.4K </span><br> 
            <span class="text-xs font-light text-slate-400">Photos</span> 
          </div>
        </div>
      </div>
    </div>
      
  </div>
</template>

<style>
.bg-cyan {
  background-color: #19A1AE;
}
</style>
