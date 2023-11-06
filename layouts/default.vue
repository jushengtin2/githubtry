
<template>
    <div>

        <button @click="toggleMenu">
            <svg xmlns="http://www.w3.org/2000/svg" id="menu" width="3em" height="3em" viewBox="0 0 24 24"><path fill="currentColor" d="M4 18q-.425 0-.713-.288T3 17q0-.425.288-.713T4 16h16q.425 0 .713.288T21 17q0 .425-.288.713T20 18H4Zm0-5q-.425 0-.713-.288T3 12q0-.425.288-.713T4 11h16q.425 0 .713.288T21 12q0 .425-.288.713T20 13H4Zm0-5q-.425 0-.713-.288T3 7q0-.425.288-.713T4 6h16q.425 0 .713.288T21 7q0 .425-.288.713T20 8H4Z"></path></svg>     
        </button>

        <div :class="{ 'sidebar': true, 'active': menuVisible }" >
      
           
                <div id="list1">
                    <svg xmlns="http://www.w3.org/2000/svg" width="5em" height="5em" viewBox="0 0 256 256"><path fill="currentColor" d="M172 120a44 44 0 1 1-44-44a44.05 44.05 0 0 1 44 44Zm60 8A104 104 0 1 1 128 24a104.11 104.11 0 0 1 104 104Zm-16 0a88.09 88.09 0 0 0-91.47-87.93C77.43 41.89 39.87 81.12 40 128.25a87.65 87.65 0 0 0 22.24 58.16A79.71 79.71 0 0 1 84 165.1a4 4 0 0 1 4.83.32a59.83 59.83 0 0 0 78.28 0a4 4 0 0 1 4.83-.32a79.71 79.71 0 0 1 21.79 21.31A87.62 87.62 0 0 0 216 128Z"></path></svg>
                </div>

                <div id="list2">
                    <NuxtLink to="/about" >首頁</NuxtLink>                
                </div>

                <div id="list3">        
                    <svg xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" viewBox="0 0 24 24"><path fill="currentColor" d="M3.354 16.894q-.166-.165-.153-.356t.153-.332l4.813-4.87q.46-.478 1.137-.478t1.156.479l2.42 2.426q.174.174.424.174t.442-.174l5.585-5.515H16.5q-.213 0-.357-.143T16 7.748q0-.213.143-.357q.144-.143.357-.143h3.692q.348 0 .578.23q.23.23.23.578v3.692q0 .214-.143.357q-.144.143-.357.143t-.357-.134t-.143-.347V8.956l-5.56 5.56q-.46.459-1.136.459q-.677 0-1.137-.46l-2.42-2.42q-.174-.174-.443-.174t-.442.173l-4.8 4.8q-.16.16-.354.16q-.195 0-.354-.16Z"></path></svg>
                    <NuxtLink to="/contact">熱門</NuxtLink>
                </div>
            
                <div id="list4">
                    <svg xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" viewBox="0 0 1231.051 1000"><path fill="currentColor" d="M1231.051 118.453q-51.422 76.487-126.173 130.403q.738 14.46.738 32.687q0 101.273-29.53 202.791q-29.53 101.519-90.215 194.343q-60.685 92.824-144.574 164.468q-83.889 71.644-201.677 114.25q-117.788 42.606-252.474 42.606q-210.2 0-387.147-113.493q31.406 3.495 60.242 3.495q175.605 0 313.687-108.177q-81.877-1.501-146.654-50.409q-64.777-48.907-89.156-124.988q24.097 4.59 47.566 4.59q33.782 0 66.482-8.812q-87.378-17.5-144.975-87.04q-57.595-69.539-57.595-160.523v-3.126q53.633 29.696 114.416 31.592q-51.762-34.508-82.079-89.999q-30.319-55.491-30.319-120.102q0-68.143 34.151-126.908q95.022 116.607 230.278 186.392q135.258 69.786 290.212 77.514q-6.609-27.543-6.621-57.485q0-104.546 73.994-178.534Q747.623 0 852.169 0q109.456 0 184.392 79.711q85.618-16.959 160.333-61.349q-28.785 90.59-110.933 139.768q75.502-8.972 145.088-39.677z"></path></svg>
                    <NuxtLink to="/contact">追蹤</NuxtLink>
                </div>

                <div id="list5">
                    <svg xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" viewBox="0 0 32 32"><path fill="currentColor" d="M26 12h-6V6a3.003 3.003 0 0 0-3-3h-2.133a2.01 2.01 0 0 0-1.98 1.717l-.845 5.917L8.465 16H2v14h21a7.008 7.008 0 0 0 7-7v-7a4.005 4.005 0 0 0-4-4ZM8 28H4V18h4Zm20-5a5.006 5.006 0 0 1-5 5H10V17.303l3.958-5.937l.91-6.366H17a1 1 0 0 1 1 1v8h8a2.002 2.002 0 0 1 2 2Z"></path></svg>
                    <NuxtLink to="/contact">典藏</NuxtLink>
                </div>

                <div id="list6">
                    <svg xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" viewBox="0 0 14 14"><path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" d="M7 13.5a9.26 9.26 0 0 0-5.61-2.95a1 1 0 0 1-.89-1V1.5A1 1 0 0 1 .85.74a1 1 0 0 1 .79-.23A9.3 9.3 0 0 1 7 3.43Zm0 0a9.26 9.26 0 0 1 5.61-2.95a1 1 0 0 0 .89-1V1.5a1 1 0 0 0-.35-.76a1 1 0 0 0-.79-.23A9.3 9.3 0 0 0 7 3.43Z"></path></svg>
                    <NuxtLink to="/contact">作品</NuxtLink>
                </div>

                <div id="list7">
                    <svg xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" viewBox="0 0 24 24"><path fill="currentColor" d="M5 21q-.825 0-1.413-.588T3 19V5q0-.825.588-1.413T5 3h8.925l-2 2H5v14h14v-6.95l2-2V19q0 .825-.588 1.413T19 21H5Zm7-9Zm-3 3v-4.25l9.175-9.175q.3-.3.675-.45t.75-.15q.4 0 .763.15t.662.45L22.425 3q.275.3.425.663T23 4.4q0 .375-.138.738t-.437.662L13.25 15H9ZM21.025 4.4l-1.4-1.4l1.4 1.4ZM11 13h1.4l5.8-5.8l-.7-.7l-.725-.7L11 11.575V13Zm6.5-6.5l-.725-.7l.725.7l.7.7l-.7-.7Z"></path></svg>
                    <NuxtLink to="/contact">創作</NuxtLink>
                </div>

           

        </div>

    </div>
    
    <NuxtPage></NuxtPage>

</template>


<style>

    .sidebar {
    position: fixed;
    left: 0;
    top: 0;
    bottom: 0;
    width: 35%;
    background: #eee;
   
    /* 初始化状态为隐藏 */
    transform: translateX(-100%);
    transition: transform 0.5s ease;
    

    }
    
    .sidebar.active {
    transform: translateX(0);
    }

  

    .sidebar > div {
  
    margin: 15px 0; /* 设置上下间隔为 10px */
    }
 


</style>


<script>

    export default {
    name: 'MaterialSymbolsMenuRounded'
    }

</script>

<script setup>

    import { ref } from 'vue';
    const menuVisible = ref(false);
    function toggleMenu() {
    menuVisible.value = !menuVisible.value;
    }

</script>
        
