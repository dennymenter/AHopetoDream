<script>
    function toggleMe() {
    var x = document.getElementById("menu-col-1");
    if (x.style.display === "none") {
        x.style.display = "block";
    } else {
        x.style.display = "none";
    }


}
</script>


<p class="mb-10 text-center">Testing playground!</p>

<p>Trying to do a drop down menu</p>


<div>
    <div class="border-black border-1 bg-slate-500  hover:text-white"><p on:click="{toggleMe}">Tasks drop down</p></div>
    <div class="border-black border-1" id="menu-col-1" style ="display:none">
        <p class="border-1 pl-4 bg-slate-500 hover:text-white">test1</p>
        <p class="border-1 pl-4 bg-slate-500 hover:text-white">test2</p>
        <p class="border-1 pl-4 bg-slate-500 hover:text-white">test3</p>
    </div>
</div>

