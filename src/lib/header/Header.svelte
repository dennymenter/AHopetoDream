<script>
    import Donate from '$lib/components/donate.svelte';
    import "/src/css/main.css"
</script>

<div class="flex  items-center AHTD-background shadow-black" style="background-color: rgb(33, 67, 104);">
    <div class="bg-transparent text-white  min-w-max">
        <div class=" p-0 ">
            <a href="/">
                <img src="src\images\AHTDLogo.jpg" alt ="">
            </a>
        </div>
    </div>
    <div class="bg-transparent text-white  items-center pr-8 min-w-max">
        <img src="src\images\founded-by.png" alt="">
    </div>
    <div class="bg-transparent text-white flex-1 text-center pl-1 border-show tracking-widest">
        <a href="whoweare">WHO WE ARE</a>
    </div>
    <div class="bg-transparent text-white flex-1 text-center pl-1 border-show tracking-widest">
        <a href="getinvolved">GET INVOLVED</a>

    </div>
    <div class="bg-transparent text-white flex-1 text-center pl-1 border-show tracking-widest ">
        <a href="media">MEDIA</a>
    </div>
    <div class="bg-transparent text-white flex-1 text-right border-show tracking-widest">
        <Donate/>        
    </div>
    <div class="">
        <a href="#">
            <img src="src\images\hamburger.jpg" alt="" class="p-0 sm:visible md:invisible">
        </a>
    </div>
</div>
<div class="m-20 border-t-2 border-black">
<p class="pt-2"><a href="todo">To Do list</a> || <a href="test">Testing ground</a></p>
</div>